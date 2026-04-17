# 品質証明書 — おばんざい郁 -aya-

**発行日**: 2026-04-17
**判定**: APPROVED（合格）
**総合スコア**: 88 / 100点
**制作システム**: AI Web制作カンパニー v2.0
**審査機関**: Quality Assurance Agent + Strategic Evaluator Agent

---

## スコア内訳

| 審査カテゴリ | 満点 | 取得点 | 評価コメント |
|---|---|---|---|
| SEO基盤 | 10 | 8 | title・meta・OGP（og:image含む）・schema.org完備。openingHours等は確定情報待ち(-2) |
| ブランド世界観 | 20 | 18 | loader「郁」・clip-pathリビール・stagger・cursorが「じわっとした灯り感」で一貫 |
| 来店転換率 | 25 | 22 | 電話tel:リンク・マップ・スティッキーフッター3カラム・Instagram導線完備(-3は地図embed安定性) |
| 禁止事項遵守 | 20 | 19 | unknown_info 8項目完全排除・営業時間/定休日の柔軟表記・現金のみ案内完備 |
| モバイルUX | 15 | 13 | 100svh・safe-area・3カラムフッター対応。will-change最適化余地あり(-2) |
| コード品質 | 10 | 8 | aria-label全セクション・alt店舗固有・CSS変数完備(-2は文字化け軽微残存) |
| **合計** | **100** | **88** | |

---

## QA審査結果

| 審査項目 | 結果 |
|---|---|
| HIGH（ブロッカー）発見件数 | **0件** |
| MID（修正推奨）発見件数 | 2件 → **Loop 1で対応済み** |
| LOW（軽微）発見件数 | 3件 → 公開後継続改善対象 |
| unknown_info 8項目 完全排除 | **PASS** |
| 営業時間・定休日の柔軟表記 | **PASS** |
| 現金のみ案内 | **PASS** |
| Instagram URL（@mamakitchen0109） | **PASS** |
| シネマティック6技法実装 | **PASS（loader/cursor/clip-path/stagger/warp/h-track）** |
| schema.org JSON-LD | **PASS（Restaurant + LocalBusiness）** |
| モバイルスティッキーフッター3カラム | **PASS（電話・Instagram・地図）** |
| safe-area-inset-bottom | **PASS** |
| 全画像alt（店舗固有） | **PASS** |
| 全section aria-label | **PASS（9セクション）** |
| og:image | **PASS** |
| copyright 2026 | **PASS** |

---

## 閾値判定

- 停止条件: スコア ≥ 88点 かつ 全カテゴリ70%以上
- 取得スコア: **88点**
- 全カテゴリ70%以上: **PASS**（最低 SEO/コード品質 80%）
- 判定: **APPROVED（2ループ目で停止条件充足）**

---

*Quality Assurance Agent + Strategic Evaluator Agent / AI Web制作カンパニー v2.0 / 2026-04-17*
