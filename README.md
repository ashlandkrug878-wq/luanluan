# 简历网站 GitHub Pages 部署包

本包为完整静态网站，包含最终 index.html 和全部图片，无需安装依赖或运行构建。

## 上传到现有仓库

1. 将 ZIP 解压到一个文件夹。
2. 打开 https://github.com/ashlandkrug878-wq/luanluan 。
3. 上传解压后的文件和图片子文件夹到仓库根目录，更新同名文件。
   根目录必须能直接看到 index.html，不能额外套一层文件夹。
   不要把 ZIP 压缩文件本身作为网页上传。
   文件较多时可分批上传，并保留图片子文件夹的原有路径。
4. 同时上传 .nojekyll 空文件。Mac Finder 可按 Command + Shift + . 显示它。
5. Settings → Pages → Build and deployment：
   Source 选择 Deploy from a branch；Branch 选择 main；目录选择 /(root)，然后 Save。
6. 在 Actions 中查看部署是否成功。
7. 部署成功后访问 https://ashlandkrug878-wq.github.io/luanluan/ 。

不需要绑定自定义域名。本包不包含 CNAME。

## 本地查看

保留所有图片文件和子文件夹，直接用浏览器打开 index.html。
手机布局、六项能力切换、角色介绍、产品与空间图集均保留。

## 最后调整

顶部个人信息：1991年 / 中国传媒大学 / 18257142336。
电话与其他个人信息采用相同字号和颜色，点击可拨号。

GitHub 官方设置说明：
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
