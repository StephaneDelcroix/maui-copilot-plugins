# maui-copilot-plugins

> ⚠️ **Unofficial** — This is a community-maintained collection of Copilot plugins for .NET MAUI development. Not affiliated with GitHub or Microsoft.

Extend GitHub Copilot CLI with plugins tailored for .NET MAUI app development.

## 🔌 Available Plugins

| Plugin | Description |
|--------|-------------|
| [appium-automation](plugins/appium-automation/) | Cross-platform mobile app automation using Appium. Supports iOS Simulator, Android Emulator, and Mac Catalyst. |

## 📦 Installation

```bash
/plugin marketplace add StephaneDelcroix/maui-copilot-plugins
/plugin install appium-automation@maui-copilot-plugins
/skills reload
```

> **Note:** You may need to run `/skills reload` after installing a plugin for it to become available.

## 🤝 Contributing

**Pull requests are welcome!** If you have a plugin that helps with .NET MAUI development, please contribute:

1. Fork this repository
2. Add your plugin under `plugins/<plugin-name>/`
3. Follow the structure of existing plugins
4. Update `.github/plugin/marketplace.json` with your plugin entry
5. Submit a PR with a description of what your plugin does

### Plugin Structure

```
plugins/
└── your-plugin/
    └── skills/
        └── your-skill/
            ├── SKILL.md          # Skill documentation
            ├── pyproject.toml    # Python dependencies (if applicable)
            └── scripts/
                └── your_script.py
```

## 📄 License

MIT License - see [LICENSE](LICENSE) for details.

## 💬 Questions?

Open an issue or start a discussion. Happy to help!
