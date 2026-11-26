# LORE

はじめまして。LOREと名乗って、XとThreadsでAIの話を書いている者です。本業はITのプロジェクトマネージャーで、子育てをしながら、仕事と家庭の合間に発信を続けています。

好きなのは、フロンティアAIとローカルLLMの両方です。新しいモデルやツールが出ると、発表資料を読むだけで終わりにせず、まず自分で動かして確かめたくなります。公式のベンチマーク数字をそのまま紹介するより、自分の環境で測った速度や精度を出す方が性に合っていて、検証の場は Google Colab（A100 / L4）と、自宅の RX 9070 XT + ROCm の2つを行き来しています。最近は、Inkling 2 Mini のような実験的なモデルを題材に、ループ回数や文脈長で挙動がどう変わるかを測るような検証が中心です。

作業はいつもAIエージェントと一緒で、Muse、Codex、Gemini・Antigravity、Grok Build を日常的に使っています。このページは、その活動の置き場として作りました。実測の記録は主にXに投稿していて、GitHubには公開できる成果物を少しずつ置いていきます。

- X: [@LOREbeginning](https://x.com/LOREbeginning)
- Threads: [@lorebeginning](https://www.threads.net/@lorebeginning)

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

## これから

実測シリーズも公開プロジェクトも、まだ始めたばかりです。これからどんどん増やしていきます。

## 公開プロジェクト

- [GProTray](https://github.com/LORE-AILabs/GProTray) — Windows 11向けの超軽量・Rust製タスクトレイ設定ツール。Logicool G HUB を常駐させずに、G PRO Wireless の DPI やポーリングレートをタスクトレイから管理できます（アイドル時 Working Set 約 9 MB）。

## 環境

- ローカル: RX 9070 XT + ROCm / Windows
- クラウド: Google Colab（A100 / L4）
- エージェント: Muse / Codex / Gemini・Antigravity / Grok Build
- 本業: IT-PM
