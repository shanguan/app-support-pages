# 通用支持与隐私页面

纯静态 HTML/CSS，无脚本、表单、数据库、外部字体或统计组件。公开页面不包含具体应用名称或运营主体名称。

## 文件

- `index.html`：技术支持、常见问题及公开反馈入口。
- `privacy.html`：适用于明确链接本页面之应用的正式隐私政策。
- `styles.css`：手机和桌面共用样式、键盘焦点和打印样式。

## 发布方式

在专用公开仓库根目录保存上述文件，将 Pages 的发布来源设为默认分支根目录。启用 HTTPS 后，以站点根地址访问支持页，以 `privacy.html` 访问隐私政策。不要把仓库代码浏览页或 Raw 文件地址当作网页地址。

公开反馈入口使用本仓库 Issues，需要 GitHub 账号。Issues 内容公开，不接收隐私申请或个人资料；隐私请求使用页面中列出的电子邮箱。

## 维护要求

- 新应用复用本页面前，核对运营主体、数据行为和第三方组件是否完全被当前政策覆盖。
- 根据实际代码和第三方组件说明，持续核对数据项、用途、接收方、保存期限和删除路径。
- 保持政策、应用内入口和商店隐私问卷与真实行为一致。
- 未来更新先核对线上现行版本及最小差异，不用旧文件覆盖新版本。保留版本记录，避免一个共用 URL 的变更意外影响其他应用。

## 核对依据

- [Apple 审核指南 1.5、5.1](https://developer.apple.com/app-store/review/guidelines/)
- [GitHub Pages 发布来源](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

本文档记录站点维护约定，不替代针对具体应用和适用法律的专业合规核对。
