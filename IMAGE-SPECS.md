# Jully 图片尺寸规范

为了避免人物、文字和 Logo 被裁切，请按下列画布制作图片，并把重要内容放在安全区域内。

| 使用位置 | 推荐尺寸 | 比例 | 格式 | 安全区域 |
|---|---:|---:|---|---|
| 电脑端页面主视觉 | 1920 × 680 | 2.82:1 | WebP | 四周各留 6%，人物和文字不要贴边 |
| 手机端页面主视觉 | 900 × 1200 | 3:4 | WebP | 左右各留 10%，上下各留 8% |
| 首页功能导航 | 1200 × 750 | 16:10 | WebP | 四周各留 5% |
| 平台线路卡片 | 1200 × 600 | 2:1 | WebP | 四周各留 5% |
| 模拟试玩封面 | 1200 × 900 | 4:3 | WebP | 四周各留 5% |
| 钱包卡片背景 | 1200 × 675 | 16:9 | WebP | 主要文字放在左上或中部，底部留出标签区 |
| 深夜推荐图标 | 400 × 400 | 1:1 | PNG/WebP | 透明背景，图标占画布约 80% |
| 品牌 Logo | 600 × 400 | 3:2 | PNG/WebP | 透明背景 |

## 文件替换位置

- 电脑主视觉：`assets/images/hero/index.webp`、`platform.webp`、`demo.webp`、`wallet.webp`、`research.webp`、`service.webp`
- 手机主视觉：同目录下带 `-mobile.webp` 的文件
- 首页卡片：`assets/images/home/`
- 平台线路：`assets/images/platform/`
- 试玩封面：`assets/images/demo/`
- 钱包图片：`assets/images/wallet/`
- 深夜推荐图标：`assets/images/research/`

替换时保持文件名不变即可，无需修改 HTML。建议 WebP 品质设置在 82–88，单张桌面主视觉控制在 350 KB 以内，手机主视觉控制在 220 KB 以内。
