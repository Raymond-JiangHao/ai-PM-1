# 仟维动力智能科技有限公司官网

一个现代美观的公司主页，采用深蓝/黑银未来感设计风格，展示可穿戴外骨骼技术公司的核心业务和产品。

## 项目特色

- 🎨 **现代设计** - 参考Hypershell官网风格，采用深蓝/黑银配色方案
- 📱 **响应式布局** - 完美适配桌面端、平板和手机
- ⚡ **流畅动画** - 包含滚动动画、悬停效果和渐变过渡
- 🔧 **易于定制** - 清晰的代码结构，方便修改和扩展

## 页面结构

1. **导航栏** - 固定顶部导航，包含平滑滚动锚点
2. **Hero区域** - 全屏标题区域，含动态背景和行动按钮
3. **公司简介** - 介绍公司核心业务和技术优势
4. **产品展示** - 两款核心产品的详细介绍
5. **技术亮点** - 四个主要技术优势展示
6. **合作伙伴** - 投资机构和合作伙伴logo展示
7. **联系方式** - 详细联系信息和社交媒体链接

## 技术栈

- **HTML5** - 语义化标记
- **CSS3** - 现代CSS特性，包含Grid、Flexbox、动画
- **JavaScript** - 交互功能和滚动效果
- **Google Fonts** - Inter字体家族

## 文件说明

```
├── index.html      # 主页面HTML结构
├── styles.css      # 完整样式表
├── script.js       # 交互功能脚本
└── README.md       # 项目说明文档
```

## 使用方法

1. 直接在浏览器中打开 `index.html` 文件
2. 或者使用本地服务器运行项目：
   ```bash
   # 使用Python简单服务器
   python -m http.server 8000
   
   # 或使用Node.js serve工具
   npx serve .
   ```

## 自定义指南

### 替换图片
将 `image-placeholder` 和 `qr-placeholder` 类的占位符替换为实际图片：

```html
<!-- 替换前 -->
<div class="image-placeholder">
    <span>产品图片 1</span>
</div>

<!-- 替换后 -->
<img src="path/to/your/image.jpg" alt="产品图片" class="product-image">
```

### 修改公司信息
在 `index.html` 中搜索并替换以下内容：
- 公司名称
- 联系方式
- 产品信息
- 技术特色

### 调整颜色主题
在 `styles.css` 中修改CSS变量：
```css
:root {
    --primary-color: #64b5f6;
    --secondary-color: #42a5f5;
    --background-dark: #0a0a0a;
    --background-light: #121212;
}
```

## 浏览器兼容性

- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+

## 许可证

本项目仅供学习和参考使用。

## 技术支持

如需定制或技术支持，请联系开发团队。
