# AngryMan 官方网站

## 网站结构

```
website/
├── index.html          # 主页
├── privacy.html        # 隐私政策
├── terms.html          # 用户协议
├── styles.css          # 样式文件
├── script.js           # JavaScript功能
├── assets/
│   └── icon/
│       └── app_icon.png # 应用图标
└── README.md           # 说明文档
```

## 产品定位

AngryMan 是面向独居女性的安全防护 APP：
- 通过 AI 变声生成多种强力男性角色声音
- 一键模拟来电通知与通话场景
- 支持多参数设置，适配不同风险环境
- 纯端侧运行，不涉及云端隐私，不收集用户数据

## 页面内容

- `index.html`：产品介绍、功能说明、下载入口
- `privacy.html`：隐私政策（纯端侧、零采集）
- `terms.html`：服务条款与使用边界

## 技术特点

- **响应式设计**: 适配各种屏幕尺寸
- **现代CSS**: 使用Flexbox和Grid布局
- **平滑动画**: CSS过渡和JavaScript交互
- **SEO优化**: 语义化HTML和meta标签
- **性能优化**: 压缩图片和优化代码

## 部署说明（GitHub Pages）

1. 推送到 `main` 分支后会自动触发 `.github/workflows/deploy.yml`
2. 在仓库 Settings -> Pages 中选择 `GitHub Actions` 作为 Source
3. 部署成功后访问：`https://wangying245028-maker.github.io/AngryMan/`

## 本地预览

1. 进入网站目录
2. 使用本地服务器运行（如 `python -m http.server 8000`）
3. 打开 `http://localhost:8000`

## 浏览器支持

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 版权

本网站内容受版权保护，归 AngryMan 所有。
