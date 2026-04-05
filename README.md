# 🌐 旅冬亦的个人网站

欢迎访问我的个人网站！这是一个展示个人信息、动态主题和交互体验的静态网页项目。  
网站支持深色/浅色主题切换、自定义字体、实时运行时长统计，并包含完整的设置面板与更新日志。

<div>
  <a href="https://github.com/lxj13533251583/ldy/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-blue" alt="License">
  </a>
  <a href="https://lxj13533251583.github.io/ldy/">
    <img src="https://img.shields.io/badge/website-live-brightgreen" alt="Website">
  </a>
  <br>
  <a href="https://github.com/lxj13533251583/ldy/stargazers">
    <img src="https://img.shields.io/github/stars/lxj13533251583/ldy" alt="GitHub stars">
  </a>
  <a href="https://github.com/lxj13533251583/ldy/commits/main">
    <img src="https://img.shields.io/github/last-commit/lxj13533251583/ldy" alt="GitHub last commit">
  </a>
  <a href="https://github.com/lxj13533251583/ldy/releases">
    <img src="https://img.shields.io/github/v/release/lxj13533251583/ldy" alt="GitHub release">
  </a>
  <a href="https://github.com/lxj13533251583/ldy/releases">
    <img src="https://img.shields.io/github/release-date/lxj13533251583/ldy" alt="Release date">
  </a>
  <a href="https://github.com/lxj13533251583/ldy">
    <img src="https://img.shields.io/github/repo-size/lxj13533251583/ldy" alt="Repo size">
  </a>
  <a href="https://github.com/lxj13533251583/ldy/commits/main">
    <img src="https://img.shields.io/github/commit-activity/m/lxj13533251583/ldy" alt="Commit activity">
  </a>
  <a href="https://github.com/lxj13533251583/ldy">
    <img src="https://img.shields.io/badge/Maintenance-Active-brightgreen" alt="Maintenance">
  </a>
</div>

## 🌟 核心功能

### 主页
- **响应式设计**：适配各种设备
- **动态头像**：悬停时放大动画
- **个人信息展示**：姓名、个性签名、关于我、经历与技能
- **联系方式**：GitHub 仓库、个人网站链接、国家等
- **社交媒体链接**：GitHub、微信、QQ、Bilibili、抖音、快手

### 设置面板
- **外观模式**：自动（跟随系统）、浅色、深色，手动切换且不受系统深色模式覆盖
- **字体选择**：系统默认、MiSans、小米兰亭、HarmonyOS Sans、OPPO Sans、汉仪文黑、汉仪旗黑
- **状态信息**：
  - 当前时间
  - 最后更新时间
  - 网站运行时长
- **刷新页面**：一键强制刷新当前页面
- **更新日志**：跳转到独立的 `changelog.html` 页面

### 交互体验
- 所有按钮（社交媒体、设置按钮）均带有按压缩放反馈（`pressed` 效果）
- 设置面板弹出时背景模糊（`backdrop-filter`），同时锁定页面滚动，关闭后恢复
- 弹出/关闭动画使用缓动曲线，过渡自然流畅

## 🎨 设计特色

1. **视觉风格**
   - 圆角头像与卡片式布局
   - 主色调为深蓝（#00668B），深色模式下调整为天蓝（#76D1FF）
   - 平滑的悬停动画与按压反馈

2. **主题系统**
   - 完全由用户手动控制，不依赖浏览器默认深色模式
   - 切换后自动保存至 `localStorage`，下次访问自动恢复

3. **字体系统**
   - 支持多种字体
   - 字体切换实时生效

4. **响应式设计**
   - 移动端优先的媒体查询
   - 触摸友好的按钮尺寸与反馈

## 🛠 技术栈

- **HTML5**：语义化标签，无障碍支持
- **CSS3**：
  - Flexbox / Grid 布局
  - CSS 变量与主题切换
  - 过渡与关键帧动画
  - 自定义字体（`@font-face`）
  - 毛玻璃效果（`backdrop-filter`）
- **JavaScript（原生）**：
  - 动态主题切换与本地存储
  - 实时时间与运行时长计时器
  - 设置面板动画与滚动锁定
  - Fetch 获取文件 `Last-Modified` 头

## 📱 手机端支持

本网页支持打包为 **Android APK**，提供两种类型：

- **在线版 Online**：网页映射至软件，内容与网站同步更新（已弃用）
- **离线版 Offline**：打包网页源文件至软件，可离线查看，更新需重新下载
  👉 [前往下载](https://github.com/lxj13533251583/ldy/releases/)

## 📝 更新日志

查看完整版本记录与变更：
[ChangeLog](https://lxj13533251583.github.io/ldy/changelog.html)

## ⚠️ 声明

1. **项目性质**：本项目为个人技术练习与作品展示，非商业用途，不代表任何官方立场。
2. **版权与许可**：
   - **代码**：本项目代码采用 **[MIT License](https://opensource.org/licenses/MIT)** 开源。
   - **字体**：项目中引用的字体文件（MiSans、小米兰亭、HarmonyOS Sans、OPPO Sans、汉仪文黑、汉仪旗黑）均受版权保护，**不包含在 MIT 许可范围内**。
   - **头像**：头像为原创，未经允许禁止商用；如需个人使用请告知作者。
3. **责任限制**：作者不对因使用本项目代码或访问网站内容导致的任何损失承担责任。
4. **隐私说明**：本网站为纯静态页面，不收集任何用户隐私数据，所有设置仅保存在浏览器本地。

## 🙏 特别鸣谢

- [GitHub](https://github.com) 提供仓库与 Pages 托管服务
- https://qianwen.aliyun.com & https://chat.deepseek.com 提供技术建议与代码优化
- [Font Awesome](https://fontawesome.com) 提供高质量图标库

---

<div align="center">
  &copy; 2026 旅冬亦 版权所有
</div>