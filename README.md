# Jully 导航中心（优化版）

这是一个无需后台即可部署的纯静态导航网站。优化版不依赖原项目缺失的图片目录，下载后可以直接预览。

## 页面

- `index.html`：首页与栏目总览
- `platform.html`：体育平台线路及推广披露
- `demo.html`：第三方试玩入口
- `wallet.html`：交易平台、第三方钱包与资金安全提示
- `research.html`：年龄限制内容（默认禁止搜索引擎收录）
- `service.html`：客服渠道与防诈骗提示
- `404.html`：错误页面

## 本地预览

不要直接双击文件测试全部功能，建议在本目录启动任意静态文件服务器后访问 `index.html`。复制到剪贴板等功能通常需要 HTTPS 或本地主机环境。

## 部署

将本目录完整上传至 GitHub Pages、Cloudflare Pages、Netlify、Vercel 或普通静态服务器。`CNAME` 已配置为 `jully.pw`，部署前请确认 DNS 所有权和平台设置。

## 上线前必须确认

1. 逐一核验所有第三方地址及最终跳转域名。
2. 确认博彩、成人内容和金融推广符合目标地区法律及年龄要求。
3. 明确披露平台链接中的代理或佣金关系。
4. 确认 Telegram、QQ、SAFEX 和邮箱仍属于官方。
5. 为服务器配置 CSP、HSTS、Referrer-Policy、X-Content-Type-Options 和 Permissions-Policy。
6. 如需恢复钱能、234、808、988 等入口，必须先取得可信的官方 HTTPS 地址。

## 维护位置

- 公共视觉：`assets/css/site.css`
- 公共菜单和页尾：`assets/js/components.js`
- 菜单、复制和外链交互：`assets/js/site.js`
- 页面条目和外链：对应 HTML 文件

## 设计说明

保留原有黑金风格，但移除了虚假的实时延迟、无法验证的安全承诺、无功能占位链接和对缺失图片的依赖。外部链接会显示跳转标识并使用安全的窗口隔离属性。
