GitHub Pages 发布说明

这个文件夹已经整理成 GitHub Pages 可用结构：
- index.html 必须放在仓库根目录
- audio/ 文件夹必须和 index.html 放在同一层
- .nojekyll 用来避免 GitHub Pages 按 Jekyll 处理静态文件

最简单发布步骤：
1. 在 GitHub 新建 Public 仓库，例如 zero-english-life
2. 进入仓库，点击 Add file -> Upload files
3. 把本文件夹里面的所有内容上传到仓库根目录：index.html、audio 文件夹、.nojekyll、validation.json
4. 点击 Commit changes
5. 进入 Settings -> Pages
6. Source 选择 Deploy from a branch
7. Branch 选择 main，文件夹选择 /root
8. 保存后等待几分钟
9. 网站地址一般是：https://你的GitHub用户名.github.io/zero-english-life/

注意：不要只上传 ZIP 文件。必须解压后上传 index.html 和 audio 文件夹。
