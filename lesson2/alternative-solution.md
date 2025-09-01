# 画像表示の代替ソリューション

## オプション1: GitHub Pagesを使用
1. lesson2の画像をGitHubリポジトリにコミット
2. GitHub Pagesを有効化
3. 画像URLを以下の形式に：
   ```
   https://[username].github.io/hackathon/lesson2/[画像ファイル名]
   ```

## オプション2: Google Sitesに直接アップロード
1. Google Sitesの編集画面で「挿入」→「画像」
2. 「アップロード」タブから画像を直接アップロード
3. HTMLコードは不要（Google Sitesが自動処理）

## オプション3: Imgur等の画像ホスティングサービス
1. [Imgur](https://imgur.com/)に画像をアップロード
2. 直接リンクを取得
3. HTMLに埋め込み

## オプション4: Base64エンコード（最終手段）
画像をBase64に変換してHTMLに直接埋め込む
- メリット：外部依存なし
- デメリット：HTMLファイルサイズが大きくなる

## 推奨順位
1. **Google Sitesに直接アップロード**（最も簡単で確実）
2. GitHub Pages（バージョン管理も可能）
3. Google Drive（共有設定を正しく設定すれば動作）
4. Base64（ファイルサイズに注意）