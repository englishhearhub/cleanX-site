# Privacy Policy / 隐私政策

**CleanX** — Last updated / 更新日期：2026-10-28

## English

### Summary
CleanX does not collect, transmit, sell, or store any user data. Everything runs locally in your browser.

### What the extension does
- Runs a content script on x.com / twitter.com that applies visual adjustments locally in your browser: decluttering the timeline and navigation, hiding view and engagement counts, and providing a focused Zen writing mode. All changes are CSS/DOM adjustments made on your device — nothing is sent anywhere.
- Stores your preferences (feature toggles, selected version, UI theme, custom CSS) locally in your browser (`chrome.storage.local`). This data never leaves your device.
- When you open the extension popup or the About page in the settings, the extension fetches a small read-only product list (`products.json`) from GitHub (raw.githubusercontent.com) to show our other extensions and to resolve the "rate us" link. This request is a plain, anonymous download of a public file and contains no user data. The list is cached locally for 24 hours; if the request fails, a built-in offline list and a built-in fallback link are used. Product icons are bundled inside the extension and are never downloaded remotely.

### What the extension does NOT do
- No data collection, no analytics, no tracking, no advertising, no telemetry servers.
- No external servers of ours exist. The extension's only network access besides normal browsing on x.com is the read-only public GitHub file mentioned above.
- No passwords, credentials, cookies, browsing history, or personal content are requested, accessed, transmitted, sold, or stored by the developer.
- No remote code is executed: the optional product list is pure data (JSON), rendered as plain text. No remote JavaScript, HTML, CSS, or images are loaded.

### Note on Custom CSS
The Advanced settings include an optional Custom CSS field. If you choose to write external URLs (e.g., a font URL) into your own CSS, those requests are made by your configuration at your discretion — the extension itself loads no remote resources.

### Changes
Any changes to this policy will be published at this URL.

### Contact
Via the GitHub repository [issues page](https://github.com/englishhearhub/cleanX-site/issues).

---

## 中文

### 概述
CleanX 不收集、不传输、不出售、不存储任何用户数据。所有功能均在你的浏览器本地运行。

### 扩展会做什么
- 在 x.com / twitter.com 页面上运行内容脚本，在你的浏览器本地应用视觉调整：净化时间线与导航、隐藏浏览量与互动数字、提供 Zen 专注写作模式。所有改动都是在你设备上完成的 CSS/DOM 调整，不会发送任何内容。
- 将你的设置（功能开关、所选版本、界面外观、自定义 CSS）保存在浏览器本地（`chrome.storage.local`），数据不会离开你的设备。
- 当你打开扩展弹窗或设置中的「关于」页时，扩展会从 GitHub（raw.githubusercontent.com）拉取一份只读的产品列表（`products.json`，一个很小的公开文件），用于展示我们的其他扩展和解析「给个好评」链接。该请求是匿名的公开文件下载，不包含任何用户数据；列表在本地缓存 24 小时，请求失败时使用内置离线列表和内置兜底链接。产品图标随扩展本地打包，不会远程下载。

### 扩展不会做什么
- 不收集数据、不做分析、不做追踪、不放广告、没有任何遥测上报。
- 我们没有任何外部服务器。除正常的 x.com 浏览外，扩展唯一的网络访问就是上述公开 GitHub 只读文件。
- 开发者不要求、不访问、不传输、不出售、不存储你的密码、凭据、Cookie、浏览历史或任何个人内容。
- 不执行远程代码：可选产品列表是纯数据（JSON），以纯文本方式渲染；不加载任何远程 JavaScript、HTML、CSS 或图片。

### 关于自定义 CSS
「高级」设置中提供可选的自定义 CSS。如果你主动在自己的 CSS 中写入外部 URL（例如字体地址），相关请求由你的配置决定——扩展自身不会加载任何远程资源。

### 变更
本政策如有变更，将在此页面公布。

### 联系方式
通过 GitHub 仓库 [Issues 页面](https://github.com/englishhearhub/cleanX-site/issues)联系。
