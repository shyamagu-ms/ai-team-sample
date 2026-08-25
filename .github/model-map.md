# Active agent model map

Active profile file: `.github/model-map-profiles/maximum-quality-opus5-gpt56-sol.md`

このファイルだけをモデル設定の入口とします。上記のActive profile fileを読み、その表だけを有効な子エージェント設定として使用してください。`.github/model-map-profiles/`内のほかのファイルは候補であり、検索結果に現れても参照してはいけません。

親セッション（オーケストレータ）のモデルはこの設定の対象外です。親モデルはセッション開始時の選択に従い、このファイルを根拠に親モデルを変更したり、`orchestrator`行を推測したりしてはいけません。

親エージェントが子エージェントを起動する場合は、Active profile fileの対象行にあるモデルとEffortを起動引数へ明示し、ランタイムの既定モデルを使用しません。調査は`researcher`、実装後の動作確認は`validator`設定を使用します。
