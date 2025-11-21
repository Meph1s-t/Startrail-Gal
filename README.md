# 星轨 (Star Trails) - Visual Novel

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![Ren'Py](https://img.shields.io/badge/Ren'Py-8.0+-orange.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Status](https://img.shields.io/badge/status-In%20Development-yellow.svg)

*一个跨越八年的爱情故事*

[English](#english) | [中文](#中文)

</div>

---
# 请注意上方的Status标签:In Development. 该项目目前还未完工, 仍然在制作中. 预计完工在12月31日之前. 我们将会在新年前给大家奉上星轨Gal版, 敬请期待.
# 我们招募一切有志愿加入Startrail开发组的人! 目前我们正在火热招募中(快来吧球球你们了)! 详情可以发送邮件给1@startrailgal.xyz
# 快来吧TAT我们正在奋力制作中如果没人来帮帮我们工期可能延迟的QAQ快来电邮联系我们罢.
<img width="1276" height="422" alt="image" src="https://github.com/user-attachments/assets/7e951579-f873-4fe4-b500-a5fe0b9180d2" />

## 中文

### 📖 关于项目

**《星轨》** 是一款基于真实故事改编的视觉小说游戏,使用Ren'Py引擎开发。这是一个关于初恋、成长、分离与重逢的感人故事,讲述了两个人从初中相识,经历高中恋爱,大学异地分手,最终在成长后重新走到一起的八年情感历程。

这个项目将原作者的回忆录改编为互动式视觉小说,玩家可以通过不同的选择体验多种剧情走向和结局。

### ✨ 故事简介

> *"我从未如此清醒地疯狂:我要和你度过我的漫漫余生。"*

- **时间跨度**: 2019-2025年(初一至大学)
- **主角**: 女鸳鸯(女主) 与 男鸳鸯(男主)
- **主题**: 初恋、成长、沟通、承诺、时间

从初中操场的初次相遇,到凤岭之巅的真挚告白;从甜蜜的高中恋爱,到大学异地的矛盾分手;从各自的成长蜕变,到最终的复合重聚——这是一段真实而动人的青春故事。


### 🎮 游戏特色

#### 核心玩法
- **多分支剧情** - 根据玩家选择触发不同情节
- **多重结局** - True End / Good End / Bad End 等多种结局
- **情感系统** - 好感度和矛盾值影响剧情走向
- **成就系统** - 收集8+个剧情成就
- **CG画廊** - 解锁并回顾精美CG插图

#### 剧情结构
1. **第一章: 小小方圆** - 初中相遇,暗恋萌芽
2. **第二章: 启天之星** - 暧昧升温,青涩互动
3. **第三章: 沅芷澧兰** - 凤岭告白,确立关系
4. **第四章: 凤岭之巅** - 矛盾爆发,大学分离
5. **第五章: 潮起潮落** - 分手疗伤,各自成长
6. **第六章: 翻山越岭** - 蜕变成熟,重新联系
7. **第七章: 回到原点** - 再次表白,决定复合
8. **尾声: 时间的见证** - 未来展望

#### 互动元素
- **20+ 关键选择点** - 影响好感度和剧情发展
- **19+ CG插图** - 记录重要时刻
- **书信系统** - 阅读角色之间的信件
- **回忆录模式** - 重温已通关场景
- **成人内容** - 可选的18+场景(可跳过)

### 🚀 快速开始

#### 系统要求
- **Ren'Py**: 8.0 或更高版本
- **操作系统**: Windows / macOS / Linux
- **Python**: 3.9+ (Ren'Py自带)

#### 安装步骤

1. **克隆仓库**
```bash
git clone https://github.com/Meph1s-t/Startrail-Gal.git
cd Startrail-Gal
```

2. **下载Ren'Py**
   - 访问 [Ren'Py官网](https://www.renpy.org/latest.html)
   - 下载适合你操作系统的版本

3. **导入项目**
   - 打开Ren'Py Launcher
   - 点击 "preferences" -> "Projects Directory"
   - 将本项目文件夹放入项目目录
   - 在启动器中选择 "star-trails-vn" 项目

4. **运行游戏**
   - 点击 "Launch Project" 开始游戏
   - 或点击 "script.rpy" 进行编辑

### 📁 项目结构

```
star-trails-vn/
│
├── game/                          # 游戏主目录
│   ├── script.rpy                # 主脚本入口
│   ├── characters.rpy            # 角色定义
│   ├── variables.rpy             # 变量定义
│   ├── images.rpy                # 图像声明
│   ├── audio.rpy                 # 音频声明
│   │
│   ├── scripts/                  # 章节脚本
│   │   ├── chapter_1.rpy        # 第一章
│   │   ├── chapter_2.rpy        # 第二章
│   │   ├── chapter_3.rpy        # 第三章
│   │   ├── chapter_4.rpy        # 第四章
│   │   ├── chapter_5.rpy        # 第五章
│   │   ├── chapter_6.rpy        # 第六章
│   │   ├── chapter_7.rpy        # 第七章
│   │   └── epilogue.rpy         # 尾声
│   │
│   ├── images/                   # 图像资源
│   │   ├── bg/                  # 背景图
│   │   ├── characters/          # 角色立绘
│   │   ├── cg/                  # CG插图
│   │   └── ui/                  # UI元素
│   │
│   ├── audio/                    # 音频资源
│   │   ├── music/               # BGM
│   │   └── sfx/                 # 音效
│   │
│   ├── gui/                      # GUI资源
│   │   └── [GUI相关文件]
│   │
│   └── tl/                       # 翻译文件
│       └── english/             # 英文翻译
│
├── README.md                     # 本文件
├── README_EN.md                  # 英文说明
├── LICENSE                       # 许可证
├── CONTRIBUTING.md               # 贡献指南
└── docs/                         # 文档目录
    ├── 剧本大纲.md               # 详细剧本
    ├── 角色设定.md               # 角色资料
    ├── CG列表.md                 # CG需求
    └── 开发日志.md               # 开发记录
```

### 🎨 资源需求

当前项目使用占位资源,欢迎贡献以下内容:

#### 图像资源
- **背景图** (约15-20张)
  - 学校操场、教室、食堂
  - 凤岭儿童公园、图书馆
  - 宿舍、街道、机场等
  
- **角色立绘** (每个主要角色5-7种表情)
  - 女鸳鸯: 普通、开心、悲伤、害羞、生气、哭泣
  - 男鸳鸯: 普通、开心、认真、害羞、疲惫
  
- **CG插图** (19张核心场景)
  - CG01: 初次相遇
  - CG09: 凤岭告白 ⭐
  - CG11: 分手夜晚
  - CG15: 复合拥抱 ⭐
  - CG17: 飞机结局 ⭐
  - 更多详见 [CG列表](docs/CG列表.md)

#### 音频资源
- **BGM** (8-10首)
  - 日常主题曲
  - 浪漫主题曲
  - 告白专用曲
  - 悲伤主题曲
  - 紧张氛围曲
  - 重逢主题曲
  
- **音效**
  - 心跳声、电话铃声、消息提示
  - 脚步声、环境音

### 🔧 开发指南

#### 添加新场景

1. 在 `game/scripts/` 创建或编辑对应章节文件
2. 使用标准Ren'Py语法:

```python
label new_scene:
    scene bg_location with fade
    play music bgm_theme fadein 2.0
    
    show character_name expression at position with dissolve
    
    character "对话内容"
    
    menu:
        "选项1":
            $ variable += 10
            jump result_1
        "选项2":
            jump result_2
```

#### 添加新角色

在 `game/characters.rpy` 中添加:

```python
define new_char = Character("角色名", color="#颜色代码", image="image_tag")
```

#### 调整游戏变量

在 `game/variables.rpy` 中修改初始值:

```python
default affection = 0        # 好感度
default conflict_level = 0   # 矛盾值
```

### 🤝 贡献指南

我们欢迎所有形式的贡献!

#### 如何贡献
1. Fork 本项目
2. 创建你的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交你的改动 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启一个 Pull Request

#### 贡献类型
- 🎨 **美术**: 角色立绘、背景、CG、UI设计
- 🎵 **音乐**: BGM创作、音效制作
- 💻 **编程**: 功能实现、Bug修复、性能优化
- 📝 **文案**: 剧本润色、对话优化、翻译
- 🎮 **测试**: Bug报告、平衡性测试、体验反馈
- 📖 **文档**: 完善README、撰写教程

详见 [CONTRIBUTING.md](CONTRIBUTING.md)

### 📋 开发路线图

#### 当前版本: v1.0.0-alpha

- [x] 核心脚本框架
- [x] 7章剧情大纲
- [x] 基础选项系统
- [ ] 完整对话脚本
- [ ] 角色立绘资源
- [ ] 背景图资源
- [ ] CG插图资源
- [ ] BGM音乐资源
- [ ] 音效资源
- [ ] UI/UX设计
- [ ] 存档系统优化
- [ ] 成就系统实现
- [ ] 画廊功能
- [ ] 多语言支持(英文)
- [ ] 测试与平衡

#### 计划中功能
- 📱 移动端适配(Android/iOS)
- 🌐 Steam发布
- 🎤 角色配音(如有资源)
- 📊 数据统计面板
- 🎁 额外DLC内容

### 🐛 已知问题

- [ ] 部分场景使用占位图像
- [ ] 音乐资源未完全添加
- [ ] 部分对话需要润色
- [ ] 存档系统需要优化

请在 [Issues](https://github.com/Meph1s-t/Startrail-Gal/issues) 页面报告新的问题。

### 📄 许可证

本项目采用 MIT 许可证 - 详见 [LICENSE](LICENSE) 文件

#### 特别说明
- **故事内容**: 基于真实经历改编,请尊重原作者版权
- **代码**: 遵循MIT协议,可自由使用和修改
- **资源**: 如使用第三方资源,请遵守相应许可协议

### 🙏 致谢

- **原作者**: 女鸳鸯 - 提供真实故事素材
- **Ren'Py引擎**: [Ren'Py官方](https://www.renpy.org/)
- **社区贡献者**: 感谢所有为本项目做出贡献的开发者

### 📞 联系方式

- **项目主页**: [GitHub Repository](https://github.com/Meph1s-t/Startrail-Gal)
- **问题反馈**: [Issues](https://github.com/Meph1s-t/Startrail-Gal/issues)
- **讨论区**: [Discussions](https://github.com/Meph1s-t/Startrail-Gal/discussions)
- **电子邮件**: 1@startrailgal.xyz

### 🌟 支持项目

如果你喜欢这个项目,欢迎:
- ⭐ 给项目点个Star
- 🔀 Fork并改进
- 🐛 报告Bug
- 💡 提出建议
- 🎨 贡献资源
- 📢 分享给朋友

---

<div align="center">

**用代码书写的爱情故事**

Made with ❤️ and Ren'Py

[⬆ 回到顶部](#星轨-star-trails---visual-novel)

</div>

---

## English

### 📖 About

**Star Trails** is a visual novel game developed with Ren'Py engine, adapted from a true love story. It tells an 8-year emotional journey of two people from their first meeting in middle school, through high school romance, college long-distance separation, to their eventual reunion after personal growth.

### ✨ Story Synopsis

> *"I've never been so lucidly insane: I want to spend the rest of my life with you."*

- **Timeline**: 2019-2025 (Middle School to College)
- **Protagonists**: Female Yuanyang (Female) & Male Yuanyang (Male)
- **Themes**: First Love, Growth, Communication, Commitment, Time

From the first encounter on the middle school playground to the heartfelt confession at Fengling Peak; from sweet high school romance to the painful college long-distance breakup; from individual growth and transformation to the final reunion - this is a genuine and touching youth story.

### 🎮 Features

- **Multiple Story Branches** - Different choices lead to various plot developments
- **Multiple Endings** - True End / Good End / Bad End and more
- **Emotion System** - Affection and conflict levels affect the story
- **Achievement System** - Collect 8+ story achievements
- **CG Gallery** - Unlock and review beautiful CG illustrations
- **7 Chapters + Epilogue** - A complete 8-12 hour gameplay experience
- **Optional Adult Content** - Skippable 18+ scenes with content warnings

### 🚀 Quick Start

#### Requirements
- **Ren'Py**: 8.0 or higher
- **OS**: Windows / macOS / Linux
- **Python**: 3.9+ (included with Ren'Py)

#### Installation

1. **Clone the repository**
```bash
git clone https://github.com/Meph1s-t/Startrail-Gal.git
cd Startrail-Gal
```

2. **Download Ren'Py**
   - Visit [Ren'Py Official Website](https://www.renpy.org/latest.html)
   - Download the version for your OS

3. **Import Project**
   - Open Ren'Py Launcher
   - Click "preferences" -> "Projects Directory"
   - Place project folder in the directory
   - Select "star-trails-vn" in the launcher

4. **Run the Game**
   - Click "Launch Project" to start
   - Or click "script.rpy" to edit

### 🤝 Contributing

We welcome all forms of contribution!

- 🎨 **Art**: Character sprites, backgrounds, CGs, UI design
- 🎵 **Music**: BGM composition, sound effects
- 💻 **Programming**: Feature implementation, bug fixes
- 📝 **Writing**: Script polishing, dialogue improvement, translation
- 🎮 **Testing**: Bug reports, balance testing, feedback
- 📖 **Documentation**: Improve README, write tutorials

See [CONTRIBUTING.md](CONTRIBUTING.md) for details.

### 📋 Roadmap

#### Current Version: v1.0.0-alpha

- [x] Core script framework
- [x] 7-chapter plot outline
- [x] Basic choice system
- [ ] Complete dialogue scripts
- [ ] Character sprite assets
- [ ] Background assets
- [ ] CG illustration assets
- [ ] BGM music assets
- [ ] Sound effect assets
- [ ] UI/UX design
- [ ] Save system optimization
- [ ] Achievement system
- [ ] Gallery feature
- [ ] Multi-language support (English)
- [ ] Testing and balancing

### 📄 License

This project is licensed under the MIT License - see [LICENSE](LICENSE) for details.

#### Special Notes
- **Story Content**: Adapted from real experiences, please respect copyright
- **Code**: MIT License, free to use and modify
- **Assets**: Follow respective licenses for third-party resources

### 🙏 Acknowledgments

- **Original Author**: Sun Yiyang - Providing the true story material
- **Ren'Py Engine**: [Ren'Py Official](https://www.renpy.org/)
- **Community Contributors**: Thanks to all developers contributing to this project

### 📞 Contact

- **Project Homepage**: [GitHub Repository](https://github.com/Meph1s-t/Startrail-Gal)
- **Issue Tracker**: [Issues](https://github.com/Meph1s-t/Startrail-Gal/issues)
- **Discussions**: [Discussions](https://github.com/Meph1s-t/Startrail-Gal/discussions)
- **Email**: 1@startrailgal.xyz

### 🌟 Support

If you like this project:
- ⭐ Star the repository
- 🔀 Fork and improve
- 🐛 Report bugs
- 💡 Suggest features
- 🎨 Contribute assets
- 📢 Share with friends

---

<div align="center">

**A Love Story Written in Code**

Made with ❤️ and Ren'Py

[⬆ Back to Top](#星轨-star-trails---visual-novel)

</div>
