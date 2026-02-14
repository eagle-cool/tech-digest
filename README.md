# Tech Digest

每日精選科技新聞摘要 — AI、前端、系統工程與資安趨勢。

## 網站

**[https://eagle-cool.github.io/tech-digest/](https://eagle-cool.github.io/tech-digest/)**

## 本地開發

需要 Ruby 3.3+：

```bash
# macOS (Homebrew)
brew install ruby@3.3
export PATH="/opt/homebrew/opt/ruby@3.3/bin:/opt/homebrew/lib/ruby/gems/3.3.0/bin:$PATH"

# 安裝依賴
bundle install

# 本地預覽
bundle exec jekyll serve
```

瀏覽器開啟 `http://localhost:4000/tech-digest/`

## 部署

Push 到 `main` 分支會自動觸發 GitHub Actions 建置和部署。

> 首次設定需到 repo **Settings → Pages** 將 Source 改為 **GitHub Actions**。

## 技術棧

- [Jekyll](https://jekyllrb.com/) 靜態網站產生器
- [Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy) 主題（v7.4）
- [Noto Sans TC](https://fonts.google.com/noto/specimen/Noto+Sans+TC) 中文字體
- GitHub Pages 託管

## 授權

內容版權所有，程式碼部分依循 [MIT License](https://opensource.org/licenses/MIT)。
