## 前提

- Google Places API (New) が有効になっていること

## 環境構築手順

1. このリポジトリを fork する
2. https://vertexaiconversation.cloud.google.com/
   で新しい AI AGENT を作成する
3. Settings から Git integration を選び、fork してきたリポジトリに紐付け、Restore する
4. Tools から place-search を選び Authentication 内の X-Goog-Api-Key ヘッダーのシークレットを Google Places API (New)の API キーに変更する

※API キー変更後に Google Cloud 側から push しなおすと、リポジトリ内(tools/place-search/place-search.json)に API キーが入るため注意。(対処法が思いつかないので一旦このやり方)
