# 毕业纪念册

���个在线绘画和图片编辑工具，用于创建和分享毕业纪念。

## ✨ 功能特性

- 📸 **上传图片** - 支持本地上传毕业照或任何图片
- 🎨 **自由绘画** - 使用画笔工具在图片上自由绘画
- 🧹 **橡皮擦** - 轻松擦除绘画内容
- 🎯 **颜色选择** - 自定义画笔颜色
- 📏 **笔刷大小** - 调整笔刷粗细（1-40像素）
- ↩️ **撤销功能** - 撤销上一步操作
- 🔄 **重置功能** - 恢复到原始图片
- 🗑️ **清空绘画** - 删除所有绘画保留原图
- 🔍 **缩放功能** - 鼠标滚轮缩放，中键拖动平移
- 💾 **下载保存** - 将编辑后的图片下载为 PNG 格式

## 🌐 在线访问

该项目已部署到 GitHub Pages，可以直接访问：

👉 **[https://cony-m.github.io/w-s-s-s-sa/](https://cony-m.github.io/w-s-s-s-sa/)**

## 🚀 快速开始

### 本地运行

1. 克隆仓库：
```bash
git clone https://github.com/Cony-M/w-s-s-s-sa.git
cd w-s-s-s-sa
```

2. 使用本地服务器运行（因为需要跨域加载图片）：

**Python 3:**
```bash
python -m http.server 8000
```

**Python 2:**
```bash
python -m SimpleHTTPServer 8000
```

**Node.js (http-server):**
```bash
npx http-server
```

3. 在浏览器中打开 `http://localhost:8000`

## 📚 使用说明

1. **加载图片**
   - 页面会自动加载一张示例图片
   - 点击"上传毕业照"按钮上传本地图片

2. **编辑图片**
   - 点击"画笔"按钮开始绘画
   - 选择喜欢的颜色和笔刷大小
   - 在图片上绘画即可

3. **调整视图**
   - 滚动鼠标滚轮缩放图片
   - 按住鼠标中键拖动平移

4. **保存结果**
   - 点击"下载"按钮保存编辑后的图片

## 🛠️ 技术栈

- **HTML5 Canvas** - 画布绘制
- **Fabric.js** - Canvas 库
- **Lucide Icons** - 图标库
- **CSS3** - 样式和动画
- **JavaScript** - 交互逻辑

## 📦 依赖

- [Fabric.js](https://fabricjs.com/) - Canvas 绘图库
- [Lucide](https://lucide.dev/) - 开源图标库

## 🔧 部署

本项目已配置 GitHub Pages 自动部署：

1. 确保仓库设置中启用了 GitHub Pages
2. 选择部署分支为 `main`
3. 更改会自动部署到 `gh-pages` 分支

## 📱 浏览器兼容性

- Chrome/Edge - ✅ 完全支持
- Firefox - ✅ 完全支持
- Safari - ✅ 完全支持
- IE - ❌ 不支持

## 📄 许可证

MIT License

## 👨‍💻 贡献

欢迎提交 Issue 和 Pull Request！

## 📮 联系方式

如有问题或建议，请在 GitHub 上提交 Issue。
