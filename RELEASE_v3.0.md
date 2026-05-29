# 🎉 LinkerOS v3.0 - Official Release

**Release Date:** May 29, 2026  
**Download Size:** 1.6 GB  
**Status:** ✅ Stable

---

## 📢 What's New in v3.0

LinkerOS v3.0 is here! The pure Bash CLI edition is now production-ready with critical bug fixes and enhanced stability.

### ✨ Major Features

- ✅ **Pure Bash Menu System** - Type `menu` for intuitive guided navigation
- ✅ **Pure Bash Disk Mounter** - Simple, efficient disk management without bloat
- ✅ **i386 & amd64 Support** - Full x86 architecture compatibility
- ✅ **Live Boot Option** - NEW: Boot directly from USB without installation
- ✅ **Enhanced Performance** - Optimized boot times and resource management

---

## 🐛 Bug Fixes

### Keyboard & Language Support
- ✅ Fixed keyboard language detection issues
- ✅ Added support for multiple keyboard layouts (QWERTY, QWERTZ, AZERTY, Turkish, and more)
- ✅ Improved language switching in menu system
- ✅ Fixed character encoding in terminal I/O

### Network Connectivity
- ✅ Fixed network connection initialization issues
- ✅ Improved WiFi and Ethernet detection
- ✅ Resolved DNS resolution failures
- ✅ Enhanced network interface stability
- ✅ Fixed packet loss on weak connections

### Live Boot
- ✅ NEW: Added live boot option to main menu
- ✅ Boot without installation for system testing
- ✅ Persistent storage support via USB
- ✅ Full hardware compatibility testing on live environment

### General Improvements
- ✅ Improved system stability
- ✅ Fixed minor menu navigation bugs
- ✅ Enhanced error handling and user feedback
- ✅ Optimized memory usage
- ✅ Better driver compatibility

---

## 📥 Installation & Download

### System Requirements

| Spec | Minimum | Recommended |
|------|---------|-------------|
| **RAM** | 512MB | 1GB+ |
| **Storage** | 5GB | 10GB+ |
| **Processor** | i386 or amd64 | amd64 |
| **Boot Method** | BIOS or UEFI | UEFI |

### Quick Start

```bash
# Clone the repository
git clone https://github.com/fthwh-bash/LinkerOS.git
cd LinkerOS

# Build from source
make build

# Run
make run
```

### Live Boot (NEW!)

1. Write v3.0 ISO to USB drive
2. Boot from USB
3. Select "Live Boot" from main menu
4. No installation required!

---

## 📚 Documentation

- **[User Manual](docs/user-manual.md)** - Complete guide for end users
- **[Getting Started](docs/getting-started.md)** - First-time setup guide
- **[Menu System Guide](docs/menu-system.md)** - How to use the Bash menu
- **[Disk Mounter Guide](docs/disk-mounter.md)** - How to mount disks
- **[Troubleshooting](docs/troubleshooting.md)** - Common issues and solutions

---

## 🙏 Acknowledgments

Special thanks to:
- The open-source community for feedback and bug reports
- All contributors who helped test v3.0
- The Bash community for continued support

---

## 🚀 What's Next?

### v3.1 (Coming Soon)
- 🔄 XFCE desktop environment (LinkerOS Minimal)
- 🔄 Enhanced package management
- 🔄 Additional language support

### v4.0+ (Future)
- ⚪ ARM64 architecture support
- ⚪ Mobile variants
- ⚪ Additional desktop environments

See the [Full Roadmap](docs/ROADMAP.md) for details.

---

## 📝 Known Issues

None reported yet! If you encounter issues, please [report them here](https://github.com/fthwh-bash/LinkerOS/issues).

---

## 🔗 Links

- **GitHub Repository:** https://github.com/fthwh-bash/LinkerOS
- **Discussions:** https://github.com/fthwh-bash/LinkerOS/discussions
- **Issues:** https://github.com/fthwh-bash/LinkerOS/issues
- **Contributing Guide:** [CONTRIBUTING.md](CONTRIBUTING.md)

---

## 📄 License

LinkerOS is licensed under the [MIT License](LICENSE).

---

**Built with ❤️ by the LinkerOS Community**

⭐ **If you love LinkerOS, please star the repository!**

