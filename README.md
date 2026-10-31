# 有春 Uchun・公開網頁（同意頁與隱私政策）

這個資料夾是要發布到 GitHub Pages 的靜態頁，網址規劃為 `https://coulson-kt.github.io/uchun-auth/`（公開 repo `coulson-KT/uchun-auth`，只放這兩頁；2026-10-31 由 CC 準備，repo 待 Coulson 同意後建立）。

- `oauth/consent/index.html`：Supabase OAuth Server 的授權同意頁（`auth.oauth_server.authorization_url_path = /oauth/consent/`）。AI 工具（ChatGPT 等）要連有春 MCP 時，會被導到這頁登入並按「允許」。
- `privacy/index.html`：隱私政策。App 設定頁「隱私政策」按鈕、App Store Connect 的隱私政策網址、同意頁的連結都指到這裡。

發布方式：把這個資料夾的內容推到 `uchun-auth` repo 的 `main`，GitHub Pages 設成從 `main` 根目錄發布。改內容只改這裡再推，不在 GitHub 網頁上直接改。
