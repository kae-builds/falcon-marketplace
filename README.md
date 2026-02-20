# falcon-plugins

Claude Code プラグインのマーケットプレイス。

## プラグイン一覧

| Plugin | Description |
|--------|-------------|
| [best-practices](https://github.com/kae-builds/best-practices) | ソフトウェア開発ライフサイクル全体をカバーするベストプラクティス |
| [notion-tools](https://github.com/kae-builds/notion-tools) | Notion API直接連携 - ページ取得・検索・コメント・プロパティ操作 |
| [tmux-ai-manager](https://github.com/kae-builds/tmux-ai-manager) | tmuxで動作するAIエージェントの管理・オーケストレーション - タスクキュー・Claude判断型ディスパッチ・完了監視 |

## インストール

```bash
# マーケットプレイス追加
/plugin marketplace add kae-builds/falcon-marketplace

# プラグインインストール
/plugin install best-practices@falcon-plugins
/plugin install notion-tools@falcon-plugins
/plugin install tmux-ai-manager@falcon-plugins
```
