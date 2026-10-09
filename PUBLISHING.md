# 发布说明

建议仓库名：S3IC-Lab/ai-learning-materials。

materials/ 完整收录 10 份 PDF；README.md 为 GitHub 阅读入口；docs/ 为独立静态导航页。网页中的 PDF 链接指向仓库 main 分支，不会将 PDF 复制到网站发布目录。

仓库包含尚未核实再分发授权的教材，建议先设为私有。GitHub Free 组织的 Pages 支持公开仓库；私有组织仓库的 Pages 需要 GitHub Team 或 Enterprise 等支持方案。普通 Pages 网站公开可访问。

创建仓库并上传全部内容到 main 后，在 Settings → Pages 选择 Deploy from a branch，分支 main，目录 /docs。预期地址为 https://s3ic-lab.github.io/ai-learning-materials/ 。该地址在实际发布前不可视为可用网站。

若组织方案不支持私有仓库 Pages，可将 docs 的网页单独放入公开站点仓库，完整 PDF 继续保存在私有资料仓库。

官方说明：https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
