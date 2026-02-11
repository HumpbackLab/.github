# HumpbackLab (座头鲸工作室)

## 关于我们

HumpbackLab（座头鲸工作室）是一个专注于轻量级无人载具解决方案的研发团队。我们致力于通过开源硬件和软件，降低入门门槛，让更多人享受科技的乐趣。

## 使命与愿景

### 使命
- **简化航模入门**：通过创新产品设计，降低新手学习成本
- **推动开源生态**：基于优秀开源项目，深度集成优化，回馈社区
- **促进技术分享**：提供完整文档和教程，帮助用户掌握核心技术

### 愿景
成轻量级无人载具控制领域的领先创新者，通过开源协作推动整个行业发展。

## 核心项目

### 🎮 PocketTX
**面向零基础用户的轻量级航模遥控解决方案**

PocketTX 是一款创新的智能硬件，能够将 Android 手机转化为遥控发射机。相比传统的专用遥控器，使用手机作为遥控器可以降低入门成本，适合新手学习和轻量级飞行。

**主要特性:**
- 即插即用，通过手机 Type-C 接口直接供电
- 基于 ExpressLRS (ELRS) 开源项目
- 支持虚拟摇杆和体感控制两种操作方式
- 内置 1S 航模电池充电系统

**GitHub 仓库:** [HumpbackLab/Android-ELRS-manual](https://github.com/HumpbackLab/Android-ELRS-manual)

### 🛩️ LightFin
**面向差速固定翼与轻量机型的 1S 一体式飞控解决方案**

LightFin 是一款为 INAV 固件设计的小型飞控，集成 AT32F435 主控与 ELRS 无线链路，适用于 1S 供电的轻量机型，特别是差速控制的无襟翼固定翼（如纸飞机改装）。

**主要特性:**
- 超小体积 (30.2mm × 14.6mm)，重量极轻
- 板载 ELRS 接收机，无需外接模块
- 集成 IMU、气压计、磁力计完整传感器套件
- 专为 1S 轻量级机型优化的电源管理

**GitHub 仓库:** [HumpbackLab/flight-controller-manual](https://github.com/HumpbackLab/flight-controller-manual)

## 开源理念

我们坚信开源协作的力量。所有项目均采用开源许可证发布，欢迎社区参与和改进：

1. **透明开发** - 所有设计文件、源代码和文档公开可见
2. **社区驱动** - 用户反馈和贡献直接影响产品发展方向
3. **知识共享** - 通过详细文档和教程传播技术知识
4. **生态共建** - 基于成熟开源项目，避免重复造轮子

## 如何贡献

我们欢迎各种形式的贡献：

### 1. 代码贡献
- 提交 Pull Request 修复 bug 或添加新功能
- 完善文档和示例代码
- 编写测试用例提高代码质量

### 2. 硬件设计
- PCB 布局优化建议
- 元件选型改进
- 机械结构设计

### 3. 文档改进
- 用户手册翻译和校对
- 教程编写
- API 文档完善

### 4. 问题反馈
- 提交 Issue 报告 bug
- 提出功能建议
- 分享使用经验和技巧

### 贡献流程
1. Fork 相关仓库
2. 创建功能分支 (`git checkout -b feature/amazing-feature`)
3. 提交更改 (`git commit -m 'Add some amazing feature'`)
4. 推送到分支 (`git push origin feature/amazing-feature`)
5. 开启 Pull Request

## 社区与支持

### 官方渠道
- **GitHub**: [HumpbackLab](https://github.com/HumpbackLab) - 主要开发平台
- **Bilibili**: [座头鲸工作室](https://space.bilibili.com/3690979722791130) - 视频教程和技术分享
- **QQ 群**: 763833895 - 中文用户交流群

### 技术支持
- **文档**: 所有产品都有完整的用户手册
- **Issue 追踪**: 通过 GitHub Issues 报告问题
- **社区讨论**: QQ 群内实时交流

### 项目状态
- **活跃开发**: 所有项目均在积极维护中
- **定期更新**: 根据用户反馈和需求持续改进
- **长期支持**: 承诺对发布的产品提供长期支持

## 许可证

除非另有说明，HumpbackLab 的项目均采用以下许可证：

- **硬件设计**: [CERN Open Hardware Licence Version 2 - Permissive](https://ohwr.org/project/cernohl/wikis/Documents/CERN-OHL-version-2)
- **软件代码**: [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.html)
- **文档内容**: [Creative Commons Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/)

各子模块可能有特定的许可证，请查看各仓库的 LICENSE 文件了解详细信息。

## 致谢

我们衷心感谢以下开源项目和社区的支持：

- **[INAV](https://github.com/iNavFlight/inav)** - 优秀的开源飞控固件
- **[ExpressLRS](https://github.com/ExpressLRS/ExpressLRS)** - 高性能开源RC链路
- **[Typst](https://github.com/typst/typst)** - 现代化的文档排版系统
- **[KiCad](https://www.kicad.org/)** - 开源电子设计自动化工具

同时感谢所有贡献者、测试用户和社区成员的支持与反馈！

---

**座头鲸工作室 · 让飞行更简单**
*HumpbackLab · Making Flight Simpler*

*最后更新: 2026年2月*
*注: 本README会根据项目发展定期更新*
