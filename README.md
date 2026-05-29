# 🖥️ LinkerOS

> A Modern, User-Friendly Operating System Bridging Simplicity and Power

[![GitHub Release](https://img.shields.io/github/v/release/fthwh-bash/LinkerOS?style=flat-square)](https://github.com/fthwh-bash/LinkerOS/releases)
[![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/fthwh-bash/LinkerOS?style=flat-square)](https://github.com/fthwh-bash/LinkerOS/stargazers)

---

## ✨ About LinkerOS

LinkerOS is an open-source operating system designed to be **accessible to beginners** while remaining **powerful for experienced developers**. We believe operating systems shouldn't force you to choose between simplicity and control—LinkerOS gives you both.

Built with pure Bash at its core, LinkerOS emphasizes simplicity without sacrificing power.

### 🎯 Our Mission

To create an OS that is:
- **User-Friendly**: Intuitive interfaces that don't compromise on functionality
- **Developer-Centric**: Powerful tools and APIs for those who want to dig deeper
- **Community-Driven**: Built with and for our users
- **Continuously Evolving**: Regular updates bringing new features and improvements

---

## 🚀 What's New in v3.0

LinkerOS v3.0 is a major milestone featuring:

- ✅ **Redesigned User Interface** - More intuitive and modern
- ✅ **Enhanced Software Compatibility** - Better support for existing applications
- ✅ **Multi-Architecture Support** - i386, amd64, and ARM64 variants
- ✅ **Pure Bash Menu System** - Type `menu` for guided navigation
- ✅ **Pure Bash Disk Mounter** - Simple and efficient disk mounting
- ✅ **Multiple Editions** - Choose the desktop environment (or CLI) that fits your needs
- ✅ **Performance Improvements** - Faster boot times and resource management

[View Full Changelog →](CHANGELOG.md)

---

## 📦 Available Editions

LinkerOS v3.0 comes in multiple editions to suit different needs and hardware:

### **For x86 & x86-64 Systems**

| Edition | Desktop Environment | Architectures | Use Case |
|---------|-------------------|---|----------|
| **LinkerTER OS** | CLI (Pure Bash) | i386, amd64 | Servers, developers, lightweight systems |
| **LinkerOS Minimal** | XFCE | i386, amd64 | Budget-friendly, lightweight desktops |
| **LinkerOS Performance** | MATE | i386, amd64 | Balanced performance and features |
| **LinkerOS Predator** | Cinnamon | amd64 | Modern, feature-rich desktop experience |

### **For ARM64 Systems**

| Edition | Desktop Environment | Architecture | Use Case |
|---------|-------------------|---|----------|
| **LinkerTER UI** | CLI (Pure Bash) | ARM64 | ARM servers, embedded systems |
| **LinkerUI Minimal** | XFCE | ARM64 | ARM boards, lightweight devices |
| **LinkerUI Performance** | MATE | ARM64 | Balanced ARM desktop experience |
| **LinkerUI Predator** | Cinnamon | ARM64 | Feature-rich ARM desktop |

### **Mobile (Coming Soon)**

| Edition | Format | Use Case |
|---------|--------|----------|
| **LinkerOS Mobile** | Generic System Image / Custom ROM | Mobile devices |

---

## ✨ Key Features

### Pure Bash Menu System
```bash
$ menu
# Opens an interactive menu for system navigation and management
```

Simply type `menu` in the terminal and get guided navigation perfect for beginners, while power users can continue with direct commands.

### Pure Bash Disk Mounter
```bash
$ mount-disk
# Simple, intuitive disk mounting tool built entirely in Bash
```

No complex dependencies or bloated utilities—just clean Bash scripts for mounting and managing your disks.

### Core Features

| Feature | Status | Notes |
|---------|--------|-------|
| Pure Bash Core | ✅ Active | Lightweight and portable |
| Interactive Menu System | ✅ Active | Type `menu` for guided navigation |
| Disk Mounter | ✅ Active | Pure Bash disk management |
| Multi-Edition Support | ✅ Active | CLI and multiple desktop environments |
| Multi-Architecture | ✅ Active | i386, amd64, ARM64 support |
| Software Compatibility | ✅ Active | Broad application support |
| System Stability | ✅ Active | Continuous refinement |

---

## ⚡ Quick Start

### Installation

1. **Download the latest release**
   ```bash
   git clone https://github.com/fthwh-bash/LinkerOS.git
   cd LinkerOS
   ```

2. **Build from source**
   ```bash
   make build
   ```

3. **Run**
   ```bash
   make run
   ```

### System Requirements

| Edition | RAM | Storage | Processor |
|---------|-----|---------|-----------|
| **LinkerTER OS** | 512MB | 5GB | i386 or amd64 |
| **LinkerOS Minimal** | 1GB | 8GB | i386 or amd64 |
| **LinkerOS Performance** | 2GB | 10GB | amd64 |
| **LinkerOS Predator** | 4GB | 15GB | amd64 |
| **ARM Variants** | 512MB-2GB | 5GB-15GB | ARM64 |

### First Steps

After installation, check out:
- [Getting Started Guide](docs/getting-started.md)
- [User Manual](docs/user-manual.md)
- [Menu System Guide](docs/menu-system.md)
- [Disk Mounter Guide](docs/disk-mounter.md)
- [API Documentation](docs/api.md)

---

## 🛠️ Development

### For Contributors

We welcome contributions! Here's how to get started:

```bash
# Clone the repository
git clone https://github.com/fthwh-bash/LinkerOS.git

# Create a feature branch
git checkout -b feature/your-feature

# Make your changes and submit a pull request
```

See [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines.

### Project Structure

```
LinkerOS/
├── kernel/          # Core OS kernel
├── drivers/         # Hardware drivers
├── userspace/       # User-facing applications
├── menu/            # Pure Bash menu system
├── disk-mounter/    # Pure Bash disk mounting utility
├── docs/            # Documentation
└── tests/           # Test suite
```

### Building & Testing

```bash
make build          # Build the OS
make test           # Run tests
make docs           # Generate documentation
```

---

## 🗺️ Roadmap

### v3.0 (Current)
- [x] Pure Bash menu system
- [x] Pure Bash disk mounter
- [x] Multiple desktop environment editions
- [x] i386 and amd64 support
- [ ] Complete ARM64 support (in progress)
- [ ] Mobile edition (planned)

### v3.1 (Planned)
- [ ] Enhanced package manager
- [ ] Improved security features
- [ ] Extended hardware support

### Future
- [ ] Better driver support
- [ ] Performance optimization
- [ ] Additional desktop environments

[View Full Roadmap →](docs/ROADMAP.md)

---

## 📚 Documentation

- **[User Manual](docs/user-manual.md)** - Complete guide for end users
- **[Menu System Guide](docs/menu-system.md)** - How to use the Bash menu
- **[Disk Mounter Guide](docs/disk-mounter.md)** - How to use the Bash disk mounter
- **[Developer Guide](docs/developer-guide.md)** - For developers and contributors
- **[API Reference](docs/api.md)** - Complete API documentation
- **[FAQ](docs/faq.md)** - Frequently asked questions
- **[Troubleshooting](docs/troubleshooting.md)** - Common issues and solutions

---

## 🤝 Get Involved

### Ways to Contribute

- **Code**: Submit pull requests with bug fixes or features
- **Documentation**: Help improve our docs and guides
- **Testing**: Report bugs and test new features
- **Feedback**: Share your ideas in [Discussions](https://github.com/fthwh-bash/LinkerOS/discussions)
- **Spread the Word**: Star ⭐ us and share with others!

### Community

- **Discussions**: [GitHub Discussions](https://github.com/fthwh-bash/LinkerOS/discussions)
- **Issues**: [Report Bugs](https://github.com/fthwh-bash/LinkerOS/issues)
- **Contributing Guide**: [CONTRIBUTING.md](CONTRIBUTING.md)

---

## 📄 License

LinkerOS is licensed under the [MIT License](LICENSE) - see the LICENSE file for details.

---

## 💡 Why Choose LinkerOS?

| Aspect | LinkerOS | Others |
|--------|----------|--------|
| Learning Curve | Gentle | Steep |
| Lightweight | ✅ Yes | Often bloated |
| Customization | ✅ Yes | Limited |
| Community Support | Active | Varies |
| Active Development | ✅ Yes | Varies |
| Open Source | ✅ Yes | Mixed |
| Pure Bash | ✅ Yes | Shell scripts |
| Minimal Dependencies | ✅ Yes | Heavy dependencies |

---

## 🌟 Support

If you love LinkerOS, please:
- ⭐ **Star this repository**
- 🐛 **Report issues** you find
- 💬 **Share feedback** in Discussions
- 📢 **Spread the word** on social media

---

**Built with ❤️ and pure Bash by the LinkerOS Community**

[Back to top ↑](#-linker os)