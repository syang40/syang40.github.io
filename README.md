# 杨帅个人主页（Academic CV 风格）

这是参考 HugoBlox Academic CV 视觉风格独立制作的静态 HTML/CSS 网页，不是原版 Hugo 工程，无需构建工具。信息来自 2026-11-24 提供的 github_ys.zip；13 篇论文均为 Selected Publications，保留顺序、作者、期刊、优秀论文和通讯作者标记。修正 Xiamen Univeristy 为 Xiamen University，其余论文信息不作外部核验。

## 发布到 GitHub Pages
1. 新建公开仓库 `你的用户名.github.io`，或使用现有主页仓库（先备份）。
2. 将本压缩包解压后，上传根目录的 `index.html`、`assets/`、`.nojekyll`、`README.md`。不要上传外层目录。若替换旧 Jekyll 主页，删除旧 `index.md`、`_config.yml` 和不再使用的主题文件（先备份）。
3. Settings → Pages → Deploy from a branch → main → /(root) → Save。
4. 构建成功后查看 Settings → Pages 中实际地址。

## 维护
- `index.html`：使用 GitHub 网页的铅笔图标编辑。PROFILE 区域修改职称、单位、邮箱（同时修改 mailto）；ABOUT 区域修改简介、研究方向；PUBLICATIONS 区域复制完整的 `<li class="pub">...</li>` 论文条目，修改标题、作者、期刊、链接；SERVICE 区域修改审稿列表。
- `assets/style.css`：布局和颜色。
- `assets/avatar.jpg`：个人照片；保持相同文件名即可。
- `.nojekyll`：让 GitHub Pages 直接托管静态文件。
- 修改后 Commit changes，GitHub Pages 自动重新发布。无需安装 Hugo 或 Jekyll。

Scholar 链接为标题搜索，不是论文 PDF。原始压缩包未提供 Google Scholar 个人 ID 或新单位邮箱，未虚构补全。
