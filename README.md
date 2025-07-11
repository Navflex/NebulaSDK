# Vzense Nebula Software Development Kit (SDK)

A comprehensive software development kit for Vzense Time-of-Flight (ToF) depth cameras, providing APIs and tools for developing applications with depth sensing capabilities.

## 📋 Table of Contents

- [Supported Devices](#supported-devices)
- [Supported Platforms](#supported-platforms)
- [Quick Start](#quick-start)
- [SDK Structure](#sdk-structure)
- [Getting Help](#getting-help)

## 🎯 Supported Devices

The following Vzense ToF cameras are supported:

| Device Model | Minimum Firmware Version |
|--------------|-------------------------|
| **DS77** | DS77_S_20220530_B16 and later |
| **DS77C** | DS77_S_20220530_B16 and later |
| **DS86** | DS86_R_20230321 and later |
| **DCAM650** | DCAM650_R_20231214_B06 and later |

## 💻 Supported Platforms

Choose the appropriate SDK package for your development environment:

| Platform | Architecture | Compiler | Notes |
|----------|--------------|----------|-------|
| **AArch64** | ARM64 | aarch64-linux-gnu (v7.5.0) | For ARM64-based systems |
| **Ubuntu 16.04** | x86_64 | x86_64-linux-gnu (v5.4.0) | For Intel/AMD 64-bit systems |
| **Ubuntu 18.04** | x86_64 | x86_64-linux-gnu (v7.5.0) | Compatible with Ubuntu 20.04 |
| **Windows 10/11** | x86_64 | Visual Studio 2017 | For Windows development |

## 🚀 Quick Start

1. **Choose your platform**: Select the appropriate SDK folder based on your operating system
2. **Install dependencies**: Follow the platform-specific installation instructions
3. **Run samples**: Explore the provided sample projects to understand the API usage
4. **Build your application**: Use the samples as a starting point for your own projects

## 📁 SDK Structure

Each platform folder contains the following components:

### Core Components
- **Include/**: Header files for C/C++ development
- **Lib/**: Library files and drivers
- **Samples/**: Example projects demonstrating various features
- **Document/**: User guides and documentation

### Sample Categories
- **Base/**: Fundamental API usage examples
- **OpenCV/**: Computer vision integration examples
- **Multi-threading**: Concurrent device handling examples

### Additional Resources
- **Python/**: Python bindings and examples
- **CSharp/**: .NET framework examples
- **ROS/**: Robot Operating System integration
- **ROS2/**: ROS2 integration examples

## 🔧 Development Guidelines

- **Choose the right branch**: Ensure you're using the correct SDK version for your device
- **Start with samples**: Use the provided sample projects as reference
- **Check documentation**: Refer to the user guides for detailed API information
- **Test thoroughly**: Verify compatibility with your specific hardware and firmware versions

## 📚 Resources

### Official Resources
- **Company Website**: [https://www.vzense.com/](https://www.vzense.com/)
- **Documentation**: [Vzense ToF Sensor and Application](https://vzense.com/Downloads.html)
- **Purchase**: [https://www.vzense.com/](https://www.vzense.com/)

### Development Tools
- **GitHub**: [https://github.com/Vzense](https://github.com/Vzense)
- **Gitee**: [https://gitee.com/Vzense](https://gitee.com/Vzense)

### Support
- **FAQ & Support**: [Vzense FAQ](https://vzense.com/Newsdispalys_faq.html)

## 📄 License

Please refer to the [LICENSE](LICENSE) file for licensing information.

---

**Note**: Make sure your device firmware is up to date and compatible with the SDK version you're using. For the best development experience, start with the sample projects and gradually build your own applications.
