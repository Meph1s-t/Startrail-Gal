# 贡献指南 (Contributing Guide)

感谢你对《星轨》项目感兴趣!我们欢迎所有形式的贡献。

[English Version](#english-version) | [中文版本](#中文版本)

---

## 中文版本

### 🌟 如何贡献

#### 1. 美术贡献 🎨

我们需要以下美术资源:
目前我们已有1个美术.

**角色立绘**
- 女鸳鸯(女主): 6种表情 × 多套服装
  - 普通、开心、悲伤、害羞、生气、哭泣
  - 校服、便装、正装等
- 男鸳鸯(男主): 5种表情 × 多套服装
  - 普通、开心、认真、害羞、疲惫
  - 校服、便装、正装等

**背景图** (分辨率: 1920×1080)
- 学校场景: 操场、教室、食堂、图书馆
- 户外场景: 凤岭公园、街道、车站
- 室内场景: 宿舍、咖啡馆、家中
- 特殊场景: 飞机舱内、考场等

**CG插图** (关键场景)
- 优先级高: CG09(凤岭告白), CG15(复合拥抱), CG17(飞机结局)
- 完整列表见 `docs/CG列表.md`[citation needed]

**要求**:
- 格式: PNG (透明背景)
- 风格: 现代青春写实风格
- 分辨率: 角色立绘建议 1000×2000+, 背景1920×1080, CG 1920×1080
- (重要) 确保你拥有版权或已获得授权

#### 2. 音乐贡献 🎵

目前我们已有一个原创音乐提供者.

**BGM需求**
- 日常生活主题 (轻松、温馨), 可能需要两首. 目前已经完成了一个.
- 浪漫主题 (甜蜜、心动), 可能需要两首.
- 告白专用曲 (感人、深情)
- 悲伤主题 (忧郁、伤感)
- 紧张氛围 (压抑、焦虑)
- 重逢主题 (激动、温暖) 可能需要比较长的乐曲.
- 结局主题 (升华、圆满) 可能需要比较长的乐曲.

**音效需求**
- 环境音: 教室、操场、咖啡馆
- 动作音: 脚步声、开门声
- 特殊音效: 心跳、电话铃声、消息提示

**要求**:
- 格式: OGG
- BGM长度: 可循环即可, 10s-5min都可以.
- 音效长度: 1-5秒
- 无需提供原始工程文件(但是请声明创作者状态, 比如AI生成, 或者创作者希望的License类型.)
- (重要) 确保你拥有版权或已获得授权

#### 3. 编程贡献 💻

**当前需求**
- [ ] 完善存档系统
- [ ] 实现成就系统
- [ ] 开发CG画廊
- [ ] 优化选项系统
- [ ] 添加回想模式
- [ ] 实现数据统计
- [ ] 移动端适配
- [ ] 性能优化

**代码规范**
- 使用Ren'Py标准语法
- 添加必要的注释(中英文)
- 变量命名使用有意义的英文
- 遵循项目现有代码风格

**提交流程**
1. Fork项目
2. 创建功能分支: `git checkout -b feature/your-feature`
3. 编写代码并测试
4. 提交: `git commit -m "feat: add your feature"`
5. 推送: `git push origin feature/your-feature`
6. 创建Pull Request

#### 4. 文案贡献 📝

目前我们还没有文案

**需要帮助的方面**
- 对话润色(使其更自然、生动)
- 心理独白优化
- 书信内容完善
- 英文翻译
- 其他语言本地化

**要求**
- 保持原作的情感基调
- 符合角色性格设定
- 语言流畅、自然
- 适当添加文化背景注释

#### 5. 测试贡献 🎮

目前我们刚刚创建文件夹, 所以无需测试者.

**测试类型**
- 功能测试: 检查功能是否正常
- 剧情测试: 走通所有分支
- 平衡性测试: 检查好感度/矛盾值设置
- 兼容性测试: 不同平台/分辨率
- 体验测试: 提供用户体验反馈

**Bug报告模板**
```markdown
### Bug描述
[简要描述问题]

### 复现步骤
1. 启动游戏
2. 选择...
3. 进入...
4. 看到错误...

### 预期行为
[应该发生什么]

### 实际行为
[实际发生了什么]

### 环境信息
- 操作系统: [如 Windows 11]
- Ren'Py版本: [如 8.1.0]
- 游戏版本: [如 v1.0.0-alpha]

### 截图/日志
[如果可能,附上截图或错误日志]
```

### 📋 提交规范

使用语义化提交信息:

- `feat`: 新功能
- `fix`: Bug修复
- `docs`: 文档更新
- `style`: 代码格式调整
- `refactor`: 重构
- `perf`: 性能优化
- `test`: 测试相关
- `chore`: 构建/工具相关

示例:
```
feat: 添加成就系统
fix: 修复存档加载错误
docs: 更新README中的安装说明
```

### 🔍 代码审查

所有Pull Request都会经过审查:

- 代码质量检查
- 功能完整性验证
- 与现有代码的兼容性
- 文档完整性

请耐心等待审查,我们会尽快回复!

### 💬 交流渠道

- **GitHub Issues**: 用于Bug报告和功能请求
- **GitHub Discussions**: 用于讨论和问答
- **项目Wiki**: 查看详细文档

### 📜 行为准则

- 尊重所有贡献者
- 建设性地提出意见
- 专注于项目改进
- 遵守开源社区规范

### 🎁 贡献者名单

所有贡献者都会被列入项目的贡献者名单中!

感谢你的贡献!

目前的贡献者:

项目创建者, 原创音乐, 歪脖口定写尬了给木超人不过马上就要开始手敲了我草绷不住了还要学如何写尬了给木干脆让我死了算了(?: Meph1s_t
美术, 素材提供: IamusXe
---

## English Version

### 🌟 How to Contribute

#### 1. Art Contributions 🎨

We need the following art assets:

**Character Sprites**
- Female yuanyang (Female Lead): 6 expressions × multiple outfits
  - Normal, Happy, Sad, Shy, Angry, Crying
  - School uniform, casual wear, formal wear, etc.
- Male yuanyang (Male Lead): 5 expressions × multiple outfits
  - Normal, Happy, Serious, Shy, Tired
  - School uniform, casual wear, formal wear, etc.

**Backgrounds** (Resolution: 1920×1080)
- School scenes: Playground, classroom, cafeteria, library
- Outdoor scenes: Fengling Park, streets, station
- Indoor scenes: Dorm room, café, home
- Special scenes: Airplane cabin, exam room, etc.

**CG Illustrations** (Key scenes)
- High priority: CG09 (Confession), CG15 (Reunion), CG17 (Ending)
- Full list in `docs/CG列表.md`[citation needed](?

**Requirements**:
- Format: PNG (transparent background) or JPG
- Style: Modern realistic youth style
- Resolution: Sprites 1000×2000+, Backgrounds 1920×1080, CGs 1920×1080
- Ensure you own copyright or have obtained authorization

#### 2. Music Contributions 🎵

**BGM Requirements**
- Daily life theme (relaxed, warm)
- Romantic theme (sweet, heartwarming)
- Confession theme (touching, affectionate)
- Sad theme (melancholic, sorrowful)
- Tense atmosphere (oppressive, anxious)
- Reunion theme (excited, warm)
- Ending theme (sublime, complete)

**Sound Effect Requirements**
- Ambient sounds: Classroom, playground, café
- Action sounds: Footsteps, door opening
- Special effects: Heartbeat, phone ring, message notification

**Requirements**:
- Format: MP3 (192kbps+) or OGG
- BGM length: 2-4 minutes (loopable)
- SFX length: 1-5 seconds
- Please provide source project files if possible
- Ensure you own copyright or have obtained authorization

#### 3. Programming Contributions 💻

**Current Needs**
- [ ] Improve save system
- [ ] Implement achievement system
- [ ] Develop CG gallery
- [ ] Optimize choice system
- [ ] Add replay mode
- [ ] Implement data statistics
- [ ] Mobile adaptation
- [ ] Performance optimization

**Code Standards**
- Use Ren'Py standard syntax
- Add necessary comments (Chinese/English)
- Use meaningful English variable names
- Follow existing project code style

**Submission Process**
1. Fork the project
2. Create feature branch: `git checkout -b feature/your-feature`
3. Write and test code
4. Commit: `git commit -m "feat: add your feature"`
5. Push: `git push origin feature/your-feature`
6. Create Pull Request

#### 4. Writing Contributions 📝

**Areas Needing Help**
- Dialogue polishing (make it more natural and vivid)
- Internal monologue optimization
- Letter content refinement
- English translation
- Other language localization

**Requirements**
- Maintain original emotional tone
- Match character personalities
- Fluent and natural language
- Add cultural context notes where appropriate

#### 5. Testing Contributions 🎮

**Testing Types**
- Functional testing: Check if features work
- Story testing: Go through all branches
- Balance testing: Check affection/conflict settings
- Compatibility testing: Different platforms/resolutions
- Experience testing: Provide UX feedback

**Bug Report Template**
```markdown
### Bug Description
[Brief description of the issue]

### Steps to Reproduce
1. Launch game
2. Select...
3. Enter...
4. See error...

### Expected Behavior
[What should happen]

### Actual Behavior
[What actually happened]

### Environment
- OS: [e.g., Windows 11]
- Ren'Py Version: [e.g., 8.1.0]
- Game Version: [e.g., v1.0.0-alpha]

### Screenshots/Logs
[Attach screenshots or error logs if possible]
```

### 📋 Commit Convention

Use semantic commit messages:

- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation update
- `style`: Code formatting
- `refactor`: Refactoring
- `perf`: Performance optimization
- `test`: Testing related
- `chore`: Build/tools related

Examples:
```
feat: add achievement system
fix: fix save loading error
docs: update installation guide in README
```

### 🔍 Code Review

All Pull Requests will be reviewed for:

- Code quality
- Functionality completeness
- Compatibility with existing code
- Documentation completeness

Please be patient - we'll respond as soon as possible!

### 💬 Communication Channels

- **GitHub Issues**: For bug reports and feature requests
- **GitHub Discussions**: For discussions and Q&A
- **Project Wiki**: For detailed documentation

### 📜 Code of Conduct

- Respect all contributors
- Provide constructive feedback
- Focus on project improvement
- Follow open source community standards

### 🎁 Contributors

All contributors will be listed in the project's contributor list!

Thank you for your contribution!
