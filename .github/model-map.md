# Agent model map

| Agent | Model | Effort |
|---|---|---|
| planner | Grok 4.6 (`grok-4.6`) | medium |
| designer | Claude Opus 5 (`claude-opus-5`) | medium |
| programmer | GPT-5.6 Sol (`gpt-5.6-sol`) | medium |
| researcher | GPT-5.6 Luna (`gpt-5.6-luna`) | medium |
| reviewee | GPT-5.6 Terra (`gpt-5.6-terra`) | medium |

各スキルはこの表をモデル設定の正とします。親エージェントが子エージェントを起動する場合も、対象行のモデルとEffortを起動引数に明示し、ランタイムの既定モデルを使用しません。調査を別エージェントへ委任する場合は`researcher`設定を使用します。
