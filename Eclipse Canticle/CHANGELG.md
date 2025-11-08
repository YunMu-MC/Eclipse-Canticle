# Changelog | 更新日志

All notable changes to Eclipse Canticle will be documented in this file.

本文档记录 Eclipse Canticle 的所有重要更改。

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

格式基于 [Keep a Changelog](https://keepachangelog.com/zh-CN/1.0.0/)，
本项目遵循 [语义化版本](https://semver.org/lang/zh-CN/spec/v2.0.0.html) 规范。

---

## [Unreleased] | [未发布]

### Planned | 计划中
- New dimensions with unique biomes and structures | 带有独特群系和结构的新维度
- Custom boss entities with advanced AI | 具有高级 AI 的自定义 Boss 实体
- Unique weapon and armor sets | 独特的武器和护甲套装
- Custom enchantments and status effects | 自定义附魔和状态效果
- Dynamic weather systems | 动态天气系统
- Advanced optimization systems | 高级优化系统

---

## [0.0.1-0001-alpha] - 2025-11-07

### Added | 新增
- **Project Structure | 项目结构**
    - Initial project setup with Fabric 1.20.1 | 基于 Fabric 1.20.1 的初始项目设置
    - Complete file structure (288 files) | 完整文件结构（288个文件）
    - Modular architecture design | 模块化架构设计

- **Build System | 构建系统**
    - Gradle build configuration | Gradle 构建配置
    - Gradle wrapper scripts (Unix/Windows) | Gradle 包装器脚本（Unix/Windows）
    - Complete dependency management | 完整的依赖管理
    - Performance-optimized JVM arguments | 性能优化的 JVM 参数

- **Core Framework | 核心框架**
    - Registration system architecture | 注册系统架构
    - Network communication framework | 网络通信框架
    - Configuration system framework | 配置系统框架
    - Event handling system | 事件处理系统

- **Development Tools | 开发工具**
    - Client/Server run configurations | 客户端/服务端运行配置
    - Data generation system | 数据生成系统
    - Custom Gradle tasks | 自定义 Gradle 任务
    - Development documentation | 开发文档

- **Documentation | 文档**
    - Project README (English/Chinese) | 项目说明文档（中英文）
    - MIT License | MIT 许可证
    - Changelog | 更新日志
    - Git ignore configuration | Git 忽略配置

### Technical Details | 技术细节
- **Minecraft Version | Minecraft 版本**: 1.20.1
- **Fabric Loader | Fabric 加载器**: 0.15.11
- **Fabric API**: 0.92.2+1.20.1
- **Java Version | Java 版本**: 17
- **Yarn Mappings | Yarn 映射**: 1.20.1+build.10

---

## Version Format | 版本格式

版本号格式：`MAJOR.MINOR.PATCH[-PRERELEASE]`

- **MAJOR | 主版本号**: 不兼容的 API 更改 | Incompatible API changes
- **MINOR | 次版本号**: 向后兼容的新功能 | Backwards-compatible new features
- **PATCH | 修订号**: 向后兼容的问题修复 | Backwards-compatible bug fixes
- **PRERELEASE | 预发布**: alpha, beta, rc | alpha, beta, rc

### Change Categories | 更改类别

- **Added | 新增**: 新功能 | New features
- **Changed | 变更**: 现有功能的更改 | Changes to existing functionality
- **Deprecated | 弃用**: 即将移除的功能 | Features that will be removed
- **Removed | 移除**: 已移除的功能 | Removed features
- **Fixed | 修复**: 错误修复 | Bug fixes
- **Security | 安全**: 安全问题修复 | Security vulnerability fixes
- **Performance | 性能**: 性能改进 | Performance improvements

---

## Development Roadmap | 开发路线图

### Phase 1: Foundation | 第一阶段：基础框架 (Current | 当前)
- [x] Project structure | 项目结构
- [x] Build system | 构建系统
- [x] Core framework | 核心框架
- [ ] Registration managers | 注册管理器
- [ ] Base classes and interfaces | 基类和接口
- [ ] Network system | 网络系统
- [ ] Configuration system | 配置系统

### Phase 2: World Generation | 第二阶段：世界生成
- [ ] Dimension system | 维度系统
- [ ] Biome system | 群系系统
- [ ] Structure generation | 结构生成
- [ ] Ore generation | 矿石生成
- [ ] Custom features | 自定义地物

### Phase 3: Content - Blocks & Items | 第三阶段：内容 - 方块与物品
- [ ] Custom blocks | 自定义方块
- [ ] Functional blocks | 功能性方块
- [ ] Tools and weapons | 工具和武器
- [ ] Armor sets | 护甲套装
- [ ] Food and crops | 食物和作物

### Phase 4: Entities & Combat | 第四阶段：实体与战斗
- [ ] Custom mobs | 自定义生物
- [ ] Boss entities | Boss 实体
- [ ] Advanced AI system | 高级 AI 系统
- [ ] Projectiles | 投射物
- [ ] Combat mechanics | 战斗机制

### Phase 5: Gameplay Systems | 第五阶段：游戏系统
- [ ] Status effects | 状态效果
- [ ] Enchantments | 附魔
- [ ] Custom recipes | 自定义配方
- [ ] Achievement system | 成就系统
- [ ] Game rules | 游戏规则

### Phase 6: Advanced Features | 第六阶段：高级功能
- [ ] Weather system | 天气系统
- [ ] Celestial bodies | 天体系统
- [ ] Player state system | 玩家状态系统
- [ ] Accessory system | 饰品系统
- [ ] Command system | 指令系统

### Phase 7: Optimization & Polish | 第七阶段：优化与完善
- [ ] Performance optimization | 性能优化
- [ ] Network optimization | 网络优化
- [ ] Memory management | 内存管理
- [ ] Client/Server compatibility | 客户端/服务端兼容性
- [ ] Bug fixes and refinement | 错误修复和完善

### Phase 8: Release Preparation | 第八阶段：发布准备
- [ ] Complete testing | 完整测试
- [ ] Documentation completion | 文档完善
- [ ] Localization | 本地化
- [ ] Beta testing | Beta 测试
- [ ] Public release | 公开发布

---

## Version History | 版本历史

### Alpha Versions | Alpha 版本
- **0.0.1-0001-alpha** (2025-11-07): Initial framework | 初始框架

### Beta Versions | Beta 版本
- Coming soon | 即将推出

### Release Versions | 正式版本
- Coming soon | 即将推出

---

## Notes | 注意事项

- **Breaking Changes | 破坏性更改**: Changes that break backwards compatibility will be clearly marked
  破坏向后兼容性的更改将被明确标记

- **Deprecation Policy | 弃用政策**: Deprecated features will remain for at least one minor version before removal
  弃用的功能在移除前将至少保留一个次版本

- **Support Policy | 支持政策**: Only the latest version will receive active support and updates
  只有最新版本会获得积极的支持和更新

---

## Links | 链接

- [GitHub Repository](https://github.com/yourusername/eclipse-canticle)
- [Issue Tracker](https://github.com/yourusername/eclipse-canticle/issues)
- [Modrinth](Coming Soon)
- [CurseForge](Coming Soon)

---

**Last Updated | 最后更新**: 2025-11-07