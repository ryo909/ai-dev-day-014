# Day014 Story — Onboarding Checklist Smith

## Why
毎日使う小さな課題を、1ページで即解決できる形にしたかったため。

## Requirements
- Webブラウザだけで完結すること
- 1画面で主要操作が終わること
- GitHub Pagesで公開できること

## Design highlights
- Day014専用にテーマをseed固定して再生成時の見た目を安定化
- planning用途に寄せた単機能UIで迷いを減らす
- 出力をそのまま再利用できるテキスト構造
- Family: onboarding_flow
- Mechanic: milestone_chunking
- Input/Output: role_and_tasks -> onboarding_plan
- Audience Promise: faster_team_rampup
- Publish Hook: 初週で迷わない受け入れ手順を即生成
- Complexity Tier: large
- Selected components: none
- Complexity hint: Create a showpiece version by adding around 3 safe enhancement components from selected_components, but avoid risky architecture changes.

## Trade-offs / Known issues
- ローカル保存機能は未実装
- 複雑な入力バリデーションは最小限

## Next ideas
- 履歴保存
- プリセット追加
- エクスポート形式拡張

## Social copy
Day014｜Onboarding Checklist Smith
新メンバーの初週導線を迷わず回すためのオンボーディング設計ツール。（話題:HN Frontpage）
