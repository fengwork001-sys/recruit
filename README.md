# 小风减脂｜销售合伙人招募网站

这是一个可以放上网的招募页，全部免费，以后自己就能更新，不需要用 AI。

## 文件夹里有什么

| 文件 | 用途 |
|---|---|
| `index.html` | 网站本身（排版、颜色、功能）。一般**不用改**。 |
| `content.js` | 网站的所有文字、佣金、条款、排行榜、图片路径。**以后改内容只改这个。** |
| `images/` | 网站用到的照片。 |
| `README.md` | 这份说明。 |

> 在电脑上双击 `index.html` 就能预览网站。

---

## 第一次：放上 GitHub 并开通网址（约 10 分钟）

### 1. 注册 GitHub
打开 <https://github.com> → **Sign up**，用邮箱注册并验证。
用户名会出现在网址里，例如用户名 `slimwithfeng`，网址就是 `https://slimwithfeng.github.io/...`。

### 2. 建立存放网站的仓库（repository）
1. 登录后点右上角 **＋** → **New repository**。
2. **Repository name** 填：`recruit`（只能用英文、数字、横线）。
3. 选 **Public**（免费版开通网址必须是 Public）。
4. 其他不用勾，点 **Create repository**。

### 3. 上传网站文件
1. 在新仓库页面点 **uploading an existing file**。
2. 先把电脑上这个文件夹**解压**，然后把里面的 `index.html`、`content.js`、`README.md` 和整个 `images` 文件夹，一起拖进网页框里。
   - 用 Chrome 或 Edge 可以直接拖整个 `images` 文件夹。
3. 等上传完，按最下面绿色的 **Commit changes**。

### 4. 开通网址（GitHub Pages）
1. 仓库上方点 **Settings** → 左边点 **Pages**。
2. **Source** 选 **Deploy from a branch**。
3. **Branch** 选 `main`，旁边选 `/ (root)`，按 **Save**。
4. 等 1–3 分钟，刷新这个页面，上方会出现网址：
   `https://你的用户名.github.io/recruit/`
5. 打开确认没问题，就可以把这个网址发到 IG、小红书、抖音、WhatsApp。

---

## 以后更新内容（不需要 AI）

### 方法 A：用网站自带的编辑模式（推荐）
1. 打开你的网址，在最后面加上 `#edit`，例如：
   `https://你的用户名.github.io/recruit/#edit`
2. 页面会进入编辑模式：
   - 点任何文字直接改。
   - 列表下面有「＋ 添加」，每一项右上角「×」删除（例如排行榜加人、改单数）。
3. 改完按底部 **下载 content.js**，电脑会下载一个新的 `content.js`。
4. 回到 GitHub 仓库首页 → **Add file** → **Upload files** → 把刚下载的 `content.js` 拖进去 → **Commit changes**。
   （会自动覆盖旧的同名文件。）
5. 等 1–3 分钟，打开网址刷新就看到新内容。

> 别人就算在网址后面加 `#edit` 也没关系：他们只能下载文件，没有你的 GitHub 账号，改不了你的网站。

### 方法 B：直接在 GitHub 改文字（适合改一两个字）
1. 仓库里点 `content.js` → 右上角铅笔图标 ✏️（Edit this file）。
2. 找到要改的文字，只改引号 `"…"` 里面的内容。
   - **不要删掉**引号 `"`、逗号 `,`、括号 `{ } [ ]`。
3. 按右上角 **Commit changes** → 再按一次 **Commit changes**。

### 换照片 / 加作品图片
1. 照片先改成英文文件名，例如 `post-ig-2.jpg`（不要用中文和空格）。
2. 仓库里点进 `images` 文件夹 → **Add file** → **Upload files** → 上传 → **Commit changes**。
3. 用 `#edit` 编辑模式，在图片下方的「图片：」那一栏填 `images/post-ig-2.jpg`，再按「下载 content.js」并上传（同上面方法 A 的第 3–4 步）。
4. 照片建议先压缩到 1 MB 以下，网站会开得更快。

### 更新排行榜
用 `#edit` 编辑模式 → 排行榜里改昵称和单数，或「＋ 添加一位 Sales Partner」→ 改「更新于」日期 → 下载 content.js → 上传。网站会自动按单数排名。

---

## 常见问题

**改了但网站没变？**
GitHub 需要 1–3 分钟更新。等一下，然后在手机上关掉网页重新打开，或在电脑按 `Ctrl + Shift + R`（Mac：`Cmd + Shift + R`）强制刷新。

**网站变成空白？**
通常是直接在 GitHub 改 `content.js` 时删掉了引号或逗号。在仓库点 `content.js` → **History**，找到上一个正常的版本恢复；或者重新上传之前下载的 `content.js`。

**想用自己的域名（例如 xiaofeng.com）？**
先在域名商（例如 Exabytes、Namecheap、GoDaddy）买域名，然后在 **Settings → Pages → Custom domain** 填入域名，再按 GitHub 显示的说明，在域名商那边设定 DNS。

**保留旧版本？**
GitHub 会自动保存每一次修改的历史，随时可以在 **History** 里查看或恢复。
