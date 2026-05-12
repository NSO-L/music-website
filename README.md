# 🎵 宝贝 - 原创音乐作品

> 一个艺术感十足的交互式音乐播放器网页

## ✨ 特色功能

- 🎨 **渐变玻璃拟态设计** - 现代感十足的视觉效果
- ✨ **动态粒子背景** - 漂浮的光点营造梦幻氛围
- 🎵 **音频可视化** - 播放时显示跳动的频谱动画
- 🔊 **完整播放控制** - 播放/暂停/进度条/音量调节
- ⌨️ **键盘快捷键** - 空格键播放/暂停，左右箭头调整进度
- 📱 **响应式布局** - 完美适配桌面和移动设备
- 🎯 **流畅动画** - 入场动画和交互动效

## 🎮 使用方法

1. 直接在浏览器中打开 `index.html` 文件
2. 点击播放按钮或专辑封面开始播放
3. 使用进度条或键盘箭头键控制播放进度
4. 调节音量或点击图标静音

## 📁 项目结构

```
├── index.html      # 主页面（包含HTML/CSS/JS）
├── 宝贝.mp3         # 您的原创音乐文件
└── README.md       # 项目说明文档
```

## 🚀 部署到 GitHub Pages

### 方法一：手动部署（推荐新手）

1. **创建 GitHub 仓库**
   - 登录 [GitHub](https://github.com)
   - 点击右上角 `+` → `New repository`
   - Repository name 填写 `music-website`
   - 选择 `Public`
   - 点击 `Create repository`

2. **上传文件**
   - 在仓库页面点击 `uploading an existing file`
   - 将 `index.html`、`宝贝.mp3` 和 `README.md` 拖拽上传
   - 点击 `Commit changes`

3. **启用 GitHub Pages**
   - 进入仓库的 `Settings` 设置
   - 滚动到 `Pages` 板块
   - Source 选择 `Deploy from a branch`
   - Branch 选择 `main`，文件夹选择 `/ (root)`
   - 点击 `Save`
   - 等待1-2分钟，你的网站将上线！

4. **访问你的网站**
   - 网站地址：`https://你的用户名.github.io/music-website/`

### 方法二：使用 Git 命令行

```bash
# 1. 进入项目文件夹
cd path/to/your/music-website

# 2. 初始化 Git 仓库
git init

# 3. 添加所有文件
git add .

# 4. 提交
git commit -m "Initial commit"

# 5. 添加远程仓库（替换为你的仓库地址）
git remote add origin https://github.com/你的用户名/music-website.git

# 6. 推送到 GitHub
git push -u origin main
```

## 🎨 自定义修改

### 更换音乐文件
将你的音乐文件命名为 `宝贝.mp3` 替换现有文件，或修改 `index.html` 中的音频源路径：

```html
<audio id="audio" preload="auto">
    <source src="你的音乐文件名.mp3" type="audio/mpeg">
</audio>
```

### 修改文字内容
在 `index.html` 中搜索并修改以下内容：
- 歌曲标题：`<h2 class="track-title">宝贝</h2>`
- 艺术家：`<p class="track-artist">原创作品</p>`
- 关于描述：`.about-text` 段落内容

### 修改颜色主题
在 CSS 的 `:root` 或 `body` 样式中修改渐变背景：

```css
body {
    background: linear-gradient(135deg, #1a1a2e 0%, #16213e 50%, #0f3460 100%);
}
```

## 📋 技术栈

- HTML5 音频 API
- CSS3 动画与渐变
- 原生 JavaScript
- 无需任何外部依赖

## 💡 提示

- 确保音乐文件格式为 MP3（大多数浏览器支持）
- 音乐文件名建议使用英文或拼音，避免特殊字符
- GitHub Pages 支持免费托管静态网站

## 📜 许可证

MIT License - 欢迎自由使用和修改！

---

*用心聆听，每一首音乐都是宝贝 💝*
