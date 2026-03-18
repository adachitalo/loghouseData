# TALO Log House — データ分析 & WEB戦略レポート

TALOログハウスのカタログ請求データ・顧客（契約者）データ・広告実績データを統合分析し、WEB広告・SEO・ターゲティング戦略の改善に活用するためのレポート群。

**Portal:** [https://adachitalo.github.io/loghouseData/](https://adachitalo.github.io/loghouseData/)

---

## WEB戦略レポート（2026年3月）

| File | Description |
|------|-------------|
| [talo-targeting-validation.html](./talo-targeting-validation.html) | **契約者ペルソナ分析レポート** ― 成約290件×カタログ請求14,643件の突合分析。年代・職業・総工費・居住地→建設地パターン・予算帯別発注率・情報源別発注率。第2部にターゲティング施策案（オプション）|
| [talo-ad-targeting-settings.html](./talo-ad-targeting-settings.html) | **広告ターゲティング設定ガイド** ― Google/Meta/Yahoo広告の具体的な管理画面設定値。エリア3分割・除外KW・年齢ターゲット・CV値重み付け・実行順序 |
| [talo-seo-audit-report.html](./talo-seo-audit-report.html) | **WEB広告 & SEO監査レポート** ― GTM 33タグ監査・GA4トラフィック分析・Ahrefs SEOデータ・Honka Japan比較・改善アクションプラン |
| [talo-web-mtg-agenda-20260318.html](./talo-web-mtg-agenda-20260318.html) | **WEB戦略MTGアジェンダ** ― 2026/3/18 イチプロとの打合せ用。KW戦略・広告最適化・GEO対策・LP制作優先度 |

## カタログ請求データ分析（全体レポート）

| File | Description |
|------|-------------|
| [catalog-analysis-report.html](./catalog-analysis-report.html) | 年度推移・地域分析・顧客属性の全体概況 |
| [hot-customer-analysis.html](./hot-customer-analysis.html) | ホット顧客数・発注率の代理店別・担当者別分析 |
| [prefecture-trends-analysis.html](./prefecture-trends-analysis.html) | 都道府県別の現住所 vs 建設予定地の推移分析 |
| [talo-hq-analysis.html](./talo-hq-analysis.html) | TALO本部（直接対応）のパフォーマンス分析 |
| [gap-analysis.html](./gap-analysis.html) | カタログ請求時予算 vs 実際の総工費の乖離分析 |
| [scoring-analysis.html](./scoring-analysis.html) | 6属性スコアリングモデル（A〜Dランク、最大25倍のリフト差） |
| [price-barrier-analysis.html](./price-barrier-analysis.html) | 価格障壁分析：坪単価64%上昇による購買層シフト |
| [web-analysis-dashboard.html](./web-analysis-dashboard.html) | WEB分析ダッシュボード |
| [ga4-gmail-report.html](./ga4-gmail-report.html) | GA4＋Gmailデータ統合レポート |

## 代理店別レポート

| File | Agency | Area | Order Rate |
|------|--------|------|------------|
| [act-agency-analysis.html](./act-agency-analysis.html) | ACT | 山梨・長野 | 4.14% |
| [cnd-agency-analysis.html](./cnd-agency-analysis.html) | CND | 鹿児島 | 2.38% |
| [hide-agency-analysis.html](./hide-agency-analysis.html) | HIDE | 静岡 | 1.86% |
| [fuji-agency-analysis.html](./fuji-agency-analysis.html) | FUJI | 長野 | 1.71% |
| [nh-agency-analysis.html](./nh-agency-analysis.html) | NH | 千葉 | 1.56% |
| [k10-agency-analysis.html](./k10-agency-analysis.html) | K10 | 近畿 | 1.02% |

## データソース

| Source | Records | Period | Description |
|--------|---------|--------|-------------|
| カタログ請求CSV | 14,643件 | 2021〜2025 | WEB経由のカタログ請求アンケート（予算・建設時期・情報源等） |
| 顧客データ（EUDS） | 9,593件 | 1993〜2025 | 契約者の詳細情報（年代・職業・総工費・建設地・用途・決定理由等） |
| 広告年間集計表 | 9年分 | 2017〜2025 | Google/Yahoo/Instagram広告のコスト・CV・CPA実績値 |
| GA4 | 28日分 | 2026/2〜3 | セッション・キーイベント・チャネル別CVR |
| Ahrefs | スナップショット | 2026/3 | DR・オーガニックKW・被リンク・競合比較 |

**Note:** 生データファイルはこのリポジトリには含まれていません。

## How to View

`.html` ファイルをブラウザで直接開くか、[index.html](./index.html) のポータルページからカード形式でナビゲーション。Chart.jsによるインタラクティブなグラフを含みます。

---
*Generated with Claude (Cowork)*
