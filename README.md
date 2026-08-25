# AI Team Sample

AIエージェントを企画・設計・実装・検証・レビューの役割に分け、Web UI PoCを作成するためのサンプルです。

![AI PoCチーム](ai-team-poster-jp-20260825-145621.png)

## 構成

- `.github/agents/`: エージェント定義
- `.github/skills/`: 各工程のスキル
- `.github/model-map-profiles/`: モデル設定例
- `.vscode/mcp.json`: Microsoft LearnとWorkIQのMCP設定

## 注意

WorkIQはMicrosoft 365のメール、会議、ファイルなどにアクセスできるMCPです。使用しない場合は、`.vscode/mcp.json`の`workiq`設定を削除または無効化してください。使用する場合は、組織のポリシーとアクセス許可を確認してください。

## ライセンス

Apache License 2.0です。`.github/skills/playwright-cli/`には、[Microsoft Playwright](https://github.com/microsoft/playwright)から変更したドキュメントが含まれます。詳細は[NOTICE](NOTICE)を参照してください。
