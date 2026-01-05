# 02_sitemap.md

## サイト構造設計書

本プロジェクトは、ユーザーの意識変容を促すストーリーテリング型の構成を採用する。SPA（Single Page Application）的な遷移を想定し、シームレスなUXを提供する。

### ディレクトリマップ

```text
root/
├── index (Entry Point / Splash)
├── top (Ethos Home / Dashboard)
├── philosophy (Our Philosophy)
├── wisdom (AI Wisdom / Technology)
├── future (Future Vision / Roadmap)
└── connect (Contact & Community)
```

### ページ詳細定義

#### 1. ホーム (index)
*   **役割:** ブランドの世界観への没入（Immersion）。
*   **概要:** 抽象的なデータビジュアライゼーションを用いたイントロダクション。ユーザーに「問い」を投げかけ、クリックすることで`top`へ遷移するゲートウェイ。

#### 2. Ethos Home (top)
*   **役割:** 情報のハブ、メインダッシュボード。
*   **概要:** ユーザーの関心に基づき、Philosophy、Wisdom、Futureへの導線を動的に配置するハブページ。最新の知見やニュースフィードもここに集約される。

#### 3. Our Philosophy (philosophy)
*   **役割:** 思想への共感（Empathy）。
*   **概要:** 「なぜ今、人間の尊厳か？」を問うマニフェスト。ミッションステートメントの詳細解説と、創設者のメッセージ、倫理規定（Code of Ethics）を掲載。

#### 4. AI Wisdom (wisdom)
*   **役割:** 技術への信頼（Trust）。
*   **概要:** 具体的なエンジニアリングアプローチの紹介。感情解析AIのデモ、ケーススタディ、倫理的AIの実装ガイドラインなど、専門的知見を提供するナレッジベース。

#### 5. Future Vision (future)
*   **役割:** 未来への期待（Expectation）。
*   **概要:** Ethos Intelligenceが描く2030年、2050年のロードマップ。「労働からの解放」「自律的幸福」が実現した社会のスペックをSFプロトタイピングの手法で提示する。

#### 6. Contact & Community (connect)
*   **役割:** 共創と参画（Engagement）。
*   **概要:** 問い合わせフォームに加え、エンジニア、哲学者、市民が参加するコミュニティへの招待口。ニュースレター登録やイベント情報も含む。