# Stoa CLI

> A command-line personal knowledge management tool designed for shell and Neovim workflows

Stoa is a CLI tool for managing markdown notes, tasks, and journals. Inspired by Obsidian but built for developers who live in the terminal, Stoa provides a consistent interface for personal knowledge management with filtering, tagging, and organization capabilities.

## 🗺️ Roadmap

- [ ] **v0.1.0**: Core note and task management
    - [ ] CLI 

## Project Structure

```
stoa/
├── cmd/                # CLI command implementations
│   ├── add/            # stoa add commands
│   ├── list/           # stoa list commands
│   ├── edit/           # stoa edit commands
│   └── ...
├── internal/           # Private application code
│   ├── config/         # Configuration management
│   ├── store/          # Database operations
│   ├── note/           # Note management logic
│   └── ...
├── pkg/                # Public library code
├── testdata/           # Test fixtures and golden files
└── docs/               # Documentation
```

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by [Obsidian](https://obsidian.md/) for the knowledge management concepts
- Built with [Cobra](https://cobra.dev/) CLI framework

---

**Stoa** - *From the ancient Greek στοά (stoa), meaning "porch" or "covered walkway" where philosophers gathered to share knowledge.*
