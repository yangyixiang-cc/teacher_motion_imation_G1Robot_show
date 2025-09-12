# 教师动作G1机器人模仿展示

[![GitHub Pages](https://img.shields.io/badge/demo-GitHub%20Pages-blue)](https://yourusername.github.io/teacher-motion-g1-robot/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

这是一个学术论文风格的展示系统，用于全面展示在线课堂视频中教师动作与G1机器人模仿效果的对比结果，包含成功案例和失败案例的分析。

## 🚀 在线演示

访问 [GitHub Pages 演示](https://yourusername.github.io/teacher-motion-g1-robot/) 查看完整效果。

## 📸 预览

![系统预览](https://via.placeholder.com/800x400/f8f9fa/333333?text=Teacher+Motion+G1+Robot+Demo)

*注：请替换为实际的系统截图*

## 功能特点

- **学术风格设计**：采用学术论文标准的排版、字体和配色
- **分类展示**：将实验结果分为成功案例和失败案例两个部分
- **网格化布局**：每行展示两组视频对比，便于详细观察
- **上下对比布局**：每组视频采用上下布局，原视频在上，G1视频在下
- **失败案例分析**：特别标识失败原因（机器人跌倒）
- **智能同步控制**：每对视频自动同步播放、暂停和时间跳转
- **统一尺寸显示**：所有视频采用16:9比例，大小完全一致
- **响应式设计**：适配桌面端和移动端
- **专业配色**：采用学术期刊标准的黑白灰配色方案

## 使用方法

1. **打开网页**：在浏览器中打开 `index.html` 文件
2. **浏览对比**：页面分为两个部分：
   - **成功案例**：18组成功的模仿效果展示
   - **失败案例**：2组机器人跌倒的失败案例
3. **每组包含**：
   - 上方：原始教师视频
   - 下方：G1机器人模仿视频
   - 失败案例会显示失败原因
4. **播放控制**：
   - **自动同步**：点击任意一个视频的播放按钮，对应的另一个视频将自动同步播放
   - **时间同步**：拖动进度条时，另一个视频会自动跟随到相同时间点
   - **暂停同步**：暂停其中一个视频时，另一个视频也会自动暂停

## 视频分类

### 成功案例（18组）

**课堂教学（6组）**
- classroom_man_01~06：课堂男教师视频

**教学比赛（10组）**
- hubei_qingjiao_man_01~04：湖北青椒计划男教师
- hubei_qingjiao_woman_01~06：湖北青椒计划女教师

**一般教学（2组）**
- teacher_woman_01~02：B站教学视频女教师

### 失败案例（2组）

**长时间教学**
- classroom_man_long_02：课堂男教师长视频
- 失败原因：长时间动作导致机器人疲劳跌倒

**体育教学**
- sport_woman_01：体育-广播体操女教师
- 失败原因：大幅度体育动作导致机器人失衡跌倒

## 技术特点

- **学术标准排版**：使用Times New Roman字体，符合学术论文标准
- **专业配色方案**：黑白灰主色调，成功案例深绿色，失败案例深红色
- **分类管理**：成功/失败案例分别展示和分析
- **视觉层次**：清晰的标题层次和视觉引导
- **详细说明**：每个失败案例都标注了具体失败原因
- **纯前端实现**：无需服务器，直接打开HTML即可使用
- **响应式布局**：桌面端每行2组，移动端单列显示
- **自适应加载**：支持MP4视频格式，优雅的错误处理

## 浏览器兼容性

- Chrome 60+
- Firefox 55+
- Safari 11+
- Edge 79+

## 🚀 部署到GitHub Pages

### 方法一：通过GitHub网页界面

1. 在GitHub上创建新仓库
2. 上传所有文件到仓库
3. 进入仓库设置 → Pages
4. 选择源分支（通常是main）
5. 等待部署完成

### 方法二：通过命令行

```bash
# 1. 克隆或初始化仓库
git clone https://github.com/yourusername/teacher-motion-g1-robot.git
cd teacher-motion-g1-robot

# 2. 添加文件
git add .
git commit -m "Add teacher motion G1 robot demo"
git push origin main

# 3. 启用GitHub Pages
# 在GitHub仓库设置中启用Pages功能
```

## 📁 项目结构

```
teacher-motion-g1-robot/
├── index.html              # 主页面
├── README.md               # 项目说明
├── LICENSE                 # MIT许可证
├── .gitignore             # Git忽略文件
└── raw/                    # 视频存储目录
    ├── classroom_man_01_raw.mp4
    ├── classroom_man_01_g1.mp4
    ├── classroom_man_02_raw.mp4
    ├── classroom_man_02_g1.mp4
    └── ... (所有视频文件)
```

## 🤝 贡献

欢迎提交Issue和Pull Request来改进这个项目。

## 📄 许可证

本项目采用 [MIT License](LICENSE) 许可证。

## 注意事项

- 确保视频文件路径正确
- 建议使用现代浏览器获得最佳体验
- 视频文件较大时可能需要等待加载
- 移动设备上建议使用WiFi网络观看
- 失败案例仅用于研究分析，展示技术局限性

## 📧 联系

如有问题或建议，请通过以下方式联系：

- 提交 [GitHub Issue](https://github.com/yourusername/teacher-motion-g1-robot/issues)
- 发送邮件至：your.email@example.com
