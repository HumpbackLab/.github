# HumpbackLab (Whale Studio)

🌐 **Language**: [中文](profile/README.md) | [English](profile/README.en.md)

## About Us

HumpbackLab (Whale Studio) is a research and development team focused on lightweight unmanned vehicle solutions. We are dedicated to lowering the barrier to entry through open-source hardware and software, making technology more accessible and enjoyable for everyone.

## Mission & Vision

### Mission
- **Simplify RC Model Entry**: Reduce the learning curve for beginners through innovative product design
- **Promote Open-Source Ecosystem**: Deeply integrate and optimize excellent open-source projects, giving back to the community
- **Facilitate Technical Sharing**: Provide comprehensive documentation and tutorials to help users master core technologies

### Vision
Become a leading innovator in lightweight unmanned vehicle control, driving industry development through open-source collaboration.

## Core Projects

### 🎮 PocketTX
**Lightweight RC Remote Control Solution for Beginners**

PocketTX is an innovative smart hardware device that transforms Android smartphones into remote transmitters. Compared to traditional dedicated remote controllers, using a smartphone as a remote control lowers entry costs, making it ideal for beginners and lightweight flying.

**Key Features:**
- Plug-and-play, powered directly via smartphone Type-C interface
- Based on the open-source ExpressLRS (ELRS) project
- Supports both virtual joystick and motion control operation modes
- Built-in 1S RC battery charging system

**GitHub Repository:** [HumpbackLab/Android-ELRS-manual](https://github.com/HumpbackLab/Android-ELRS-manual)

### 🛩️ LightFin
**1S Integrated Flight Controller Solution for Differential Fixed-Wing and Lightweight Aircraft**

LightFin is a compact flight controller designed for INAV firmware, integrating AT32F435 main controller with ELRS wireless link. It is suitable for 1S-powered lightweight aircraft, particularly differential-controlled fixed-wing aircraft without flaps (such as modified paper airplanes).

**Key Features:**
- Ultra-compact size (30.2mm × 14.6mm), extremely lightweight
- Onboard ELRS receiver, no external module required
- Complete sensor suite: IMU, barometer, magnetometer
- Power management optimized for 1S lightweight aircraft

**GitHub Repository:** [HumpbackLab/flight-controller-manual](https://github.com/HumpbackLab/flight-controller-manual)

### 🌐 Official Website
**Product Documentation and User Manual Center**

Official website built with VitePress, integrating user manuals and technical documentation for all products.

**GitHub Repository:** [HumpbackLab/website](https://github.com/HumpbackLab/website)

## Technology Stack

### Hardware Platform
- **Microcontroller**: AT32F435 (ARM Cortex-M4)
- **Wireless Communication**: ExpressLRS (2.4GHz), ESP8285 + SX1280
- **Sensors**: LSM6DSOWTR (6-axis IMU), QMC5883P (magnetometer), SPL06-001 (barometer)

### Software Ecosystem
- **Flight Controller Firmware**: [INAV](https://github.com/iNavFlight/inav) - Open-source multi-purpose flight controller firmware
- **Wireless Protocol**: [ExpressLRS](https://github.com/ExpressLRS/ExpressLRS) - Open-source high-performance RC link
- **Documentation System**: [Typst](https://github.com/typst/typst) - Modern document typesetting system
- **Website Framework**: [VitePress](https://github.com/vuejs/vitepress) - Vue-powered static site generator

### Development Tools
- **PCB Design**: KiCad (open-source electronic design automation tool)
- **Firmware Development**: ARM GCC, STM32CubeIDE
- **Version Control**: Git, GitHub

## Open-Source Philosophy

We firmly believe in the power of open-source collaboration. All projects are released under open-source licenses, and community participation and improvements are welcome:

1. **Transparent Development** - All design files, source code, and documentation are publicly visible
2. **Community-Driven** - User feedback and contributions directly influence product development direction
3. **Knowledge Sharing** - Spread technical knowledge through detailed documentation and tutorials
4. **Ecosystem Co-creation** - Build upon mature open-source projects, avoiding reinventing the wheel

## How to Contribute

We welcome contributions in various forms:

### 1. Code Contributions
- Submit Pull Requests to fix bugs or add new features
- Improve documentation and example code
- Write test cases to improve code quality

### 2. Hardware Design
- PCB layout optimization suggestions
- Component selection improvements
- Mechanical structure design

### 3. Documentation Improvements
- User manual translation and proofreading
- Tutorial writing
- API documentation enhancement

### 4. Issue Reporting
- Submit Issues to report bugs
- Propose feature suggestions
- Share usage experiences and tips

### Contribution Process
1. Fork the relevant repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Community & Support

### Official Channels
- **GitHub**: [HumpbackLab](https://github.com/HumpbackLab) - Primary development platform
- **Bilibili**: [座头鲸工作室](https://space.bilibili.com/3690979722791130) - Video tutorials and technical sharing (Chinese video platform)
- **QQ Group**: 763833895 - Chinese user communication group (Chinese instant messaging platform)

### Technical Support
- **Documentation**: Complete user manuals for all products
- **Issue Tracking**: Report problems through GitHub Issues
- **Community Discussion**: Real-time communication in QQ group

### Project Status
- **Active Development**: All projects are actively maintained
- **Regular Updates**: Continuous improvement based on user feedback and needs
- **Long-term Support**: Commitment to long-term support for released products

## License

Unless otherwise specified, HumpbackLab projects adopt the following licenses:

- **Hardware Design**: [CERN Open Hardware Licence Version 2 - Permissive](https://ohwr.org/project/cernohl/wikis/Documents/CERN-OHL-version-2)
- **Software Code**: [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.html)
- **Documentation Content**: [Creative Commons Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/)

Submodules may have specific licenses. Please check each repository's LICENSE file for detailed information.

## Acknowledgments

We sincerely thank the following open-source projects and communities for their support:

- **[INAV](https://github.com/iNavFlight/inav)** - Excellent open-source flight controller firmware
- **[ExpressLRS](https://github.com/ExpressLRS/ExpressLRS)** - High-performance open-source RC link
- **[Typst](https://github.com/typst/typst)** - Modern document typesetting system
- **[KiCad](https://www.kicad.org/)** - Open-source electronic design automation tool

We also thank all contributors, test users, and community members for their support and feedback!

---

**Whale Studio · Making Flight Simpler**
*HumpbackLab · 让飞行更简单*

*Last Updated: February 2026*
*Note: This README will be updated periodically as projects evolve*

🌐 **Other Language Versions**: [Chinese Version](profile/README.md)
