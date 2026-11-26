# LORE

フロンティアAIと地元LLM（ローカルLLM）の二刀流で、検証と実測を発信しています。

- X: [@LOREbeginning](https://x.com/LOREbeginning)
- Threads: [@lorebeginning](https://www.threads.net/@lorebeginning)

## やっていること

- 新しいモデルやツールを、実際に動かして測る（生成速度・精度・VRAM・文脈長）
- 公式ドキュメントや発表数字と、実測の突き合わせ
- ローカル環境（RX 9070 XT + ROCm）と Google Colab（A100 / L4）の両方で検証

## 実測シリーズ（Xポストへのリンク）

**Inkling 2 Mini（Thinking Machines Lab）ループ構造の検証**
- [GGUFごとの速度と精度（初回）](https://x.com/LOREbeginning/status/2124086650640957610)
- [ループ回数を変えると速度と精度はどう変わるか](https://x.com/LOREbeginning/status/2124269125933334935)
- [難問で差が出た（第4弾）](https://x.com/LOREbeginning/status/2124480113349939487)

**Strata 実行エンジンの実測**
- [生成速度320 tok/s、llama.cpp比 約8.7倍（A100）](https://x.com/LOREbeginning/status/2124643968906637747)
- [文脈を伸ばすと生成速度はどこまで落ちるか、13点で実測](https://x.com/LOREbeginning/status/2124786280013942857)

**MemT-1.0**
- [記憶の中身を分解した：混ざる原因は「同じ形の文」という共通成分だった](https://x.com/LOREbeginning/status/2125514844245778482)

## 解説ポスト

- [【T3 Code】今話題のT3 Code徹底解説](https://x.com/LOREbeginning/status/2123742828195193238)
- [【Qwen3.8 FN】59通りの試行から爆誕（rS氏の無検閲モデル作り直し版）](https://x.com/LOREbeginning/status/2124371188466295093)

## 公開プロジェクト

- [GProTray](https://github.com/LORE-AILabs/GProTray) — Windows 11向けの超軽量・Rust製タスクトレイ設定ツール。Logicool G HUB を常駐させずに、G PRO Wireless の DPI やポーリングレートをタスクトレイから管理できます（アイドル時 Working Set 約 9 MB）。

## 環境

- ローカル: RX 9070 XT + ROCm / Windows
- クラウド: Google Colab（A100 / L4）
- エージェント: Muse / Codex / Gemini・Antigravity / Grok Build
- 本業: IT-PM
