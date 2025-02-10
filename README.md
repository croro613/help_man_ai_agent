## 前提
- Google Places API (New) が有効になっていること
## 環境構築手順
1. このリポジトリをforkする
1. https://vertexaiconversation.cloud.google.com/
で新しいAI AGENTを作成する
2. SettingsからGit integrationを選び、forkしてきたリポジトリに紐付け、Restoreする
3. Toolsからplace-searchを選びAuthentication内のX-Goog-Api-KeyヘッダーのシークレットをGoogle Places API (New)のAPIキーに変更する

※APIキー変更後にGoogle Cloud側からpushしなおすと、リポジトリ内(tools/place-search/place-search.json)にAPIキーが入るため注意。(対処法が思いつかないので一旦このやり方)
