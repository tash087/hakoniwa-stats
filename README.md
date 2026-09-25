# hakoniwa-stats

箱庭クラフトの公開統計を`stats.json`として配信するだけの軽量リポジトリです。

- 更新元: `hakoniwa-core`プラグイン(本番`life`鯖)が、新規プレイヤーの初参加を検知するたびに
  GitHub Contents APIで`stats.json`を直接更新します(gitクライアント・SSH鍵は不要)。
- 参照元: 静的サイト(hakoniwacraft-site)から
  `https://raw.githubusercontent.com/tash087/hakoniwa-stats/main/stats.json`を`fetch`して表示します。
- Cloudflare Pagesとは連携していません。このリポジトリへのpushでサイトのビルドが走ることはありません。

## stats.jsonの形式

```json
{
  "totalParticipants": 0,
  "updatedAt": "2026-09-25T12:34:56Z"
}
```
