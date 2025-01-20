# Neovim Configuration 🚀

Modern and powerful Neovim configuration designed for a delightful development experience.

## ✨ Features

- Modern theme with Catppuccin
- Smart file explorer and fuzzy finder
- LSP support for multiple languages 
- Intelligent code completion
- Auto-formatting and auto-save
- Git integration
- Beautiful indent guides
- AI code assistance

## 🛠 Prerequisites

- Neovim >= 0.8.0
- Git
- Nerd Font
- Node.js
- ripgrep

## 📦 Installation

1. **Backup existing config**
```bash
mv ~/.config/nvim ~/.config/nvim.bak
```

2. **Clone configuration**
```bash
git clone <your-repo> ~/.config/nvim
```

3. **Start Neovim** 
```bash
nvim
```

## ⌨️ Key Bindings

### General
| Key | Action |
|-----|--------|
| `Space` | Leader |
| `<Leader>w` | Save file |
| `<Leader>t` | Terminal |
| `<Tab>` | Next buffer |
| `<S-Tab>` | Previous buffer |

### Navigation  
| Key | Action |
|-----|--------|
| `<C-h/j/k/l>` | Window movement |
| `<C-n>` | Toggle file tree |
| `<Leader>e` | Focus file tree |

### Fuzzy Finding
| Key | Action |
|-----|--------|
| `<Leader>ff` | Find files |
| `<Leader>fg` | Live grep |
| `<Leader>fb` | Find buffers |

## 🔌 Main Plugins

- **Theme**: Catppuccin
- **Explorer**: nvim-tree  
- **Status**: lualine
- **Finder**: telescope
- **LSP**: lsp-zero
- **Git**: gitsigns
- **Format**: formatter.nvim
- **AI**: codeium

## 🔄 Updates

```vim
:Lazy update  " Update plugins
:Lazy clean   " Remove unused
```

## ⚠️ Troubleshooting

1. Update Neovim 
2. Clear plugin cache:
```bash 
rm -rf ~/.local/share/nvim/lazy
```
