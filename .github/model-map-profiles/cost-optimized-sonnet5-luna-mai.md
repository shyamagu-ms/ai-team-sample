# Cost-optimized profile: Sonnet 5, GPT-5.6 Luna, MAI-Code-1.1-Flash

このファイルは`.github/model-map.md`のActive profile fileに指定された場合だけ有効です。

| Agent | Model | Effort |
|---|---|---|
| planner | Claude Sonnet 5 (`claude-sonnet-5`) | medium |
| designer | Claude Sonnet 5 (`claude-sonnet-5`) | medium |
| programmer | MAI-Code-1.1-Flash (`mai-code-1.1-flash`) | medium |
| researcher | GPT-5.6 Luna (`gpt-5.6-luna`) | low |
| validator | MAI-Code-1.1-Flash (`mai-code-1.1-flash`) | low |
| reviewee | GPT-5.6 Luna (`gpt-5.6-luna`) | low |

Sonnet 5は企画・設計の判断に限定し、作業量の多い実装・調査・検証・デモはLunaまたはMAI-Code-1.1-Flashへ割り当てます。
