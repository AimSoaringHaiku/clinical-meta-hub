# clinical-meta-hub

薬局・臨床現場向けの**ナレッジ集（リンク集・臨床判断メモ）**と、公開中の業務支援ツールをまとめた総合案内ページです。

- 🌐 公開ページ：<https://aimsoaringhaiku.github.io/clinical-meta-hub/>
- 🗺️ 開発ロードマップ：<https://aimsoaringhaiku.github.io/clinical-meta-hub/roadmap.html>

## 公開中の業務支援ツール
| ツール | URL |
| :--- | :--- |
| 指定乱用防止医薬品 該当有無の判定早見表（PDF） | <https://aimsoaringhaiku.github.io/pharma-gatekeeper/downloads.html> |
| 同（Web閲覧用） | <https://aimsoaringhaiku.github.io/pharma-gatekeeper/> |
| 薬局掲示物のコンプライアンス・チェックリスト | <https://aimsoaringhaiku.github.io/Pharmacy-Compliance-Signage-Checklist/> |
| エンレスト：対象患者層の分析・服薬指導文言集（試作） | <https://aimsoaringhaiku.github.io/integrated-master-hub/docs/apps/Entresto.html> |

## このリポジトリの構成
| ファイル | 内容 |
| :--- | :--- |
| `index.html` | ナレッジ一覧（タブ切替・検索）。単一ファイルの静的HTML |
| `sitemap.html` | サイトマップ（公開サイトのページ一覧と、重なり・関連）。トップのヘッダーからも開ける |
| `roadmap.html` | 開発ロードマップ（優先課題・TODO・作業の候補） |
| `print_links.html` / `print_notes.html` / `print.html` | A4印刷用の画面（リンク集だけ／解説・事例だけ／全部）。トップの「印刷」メニューからも開ける |
| `detail_iron_tea.html` / `detail_inhaler.html` / `detail_kidney_dose.html` | 詳細ページ（鉄剤とお茶／吸入ステロイドの用量／腎臓：薬の注意レベル案）。トップの「詳細ページ」メニューからも開ける |
| `proposals/` | 検討資料（たたき台）のページとPDF。共有ログ（`proposals/share_log.html`）もここにある |
| `exabase_knowledge_pack.md` | 全ナレッジを1ファイルに結合したもの（生成AI・RAGに投入する用。URLは1行の完全な形） |
| `project_manifest.json` | 各リポジトリの概要・進捗・公開URLの軽量一覧（AI・人間共通の入口） |

## 🔒 セキュリティ宣言
- 公開ページは**静的HTML/CSSとバニラJavaScriptのみ**です。サーバー側プログラム、データベース、ログイン、入力フォームは使用していません。
- ページは外部への通信を行いません（CSPで外部読み込み・外部送信を禁止）。外部CDN・解析タグ・広告も使っていません。
- 個人情報の入力・収集は行いません。ロードマップのチェック状態は閲覧者のブラウザ内（localStorage）にのみ保存され、送信されません。
- 通信はGitHub PagesのHTTPSで保護されます。

## ⚠️ 免責
掲載内容は現場の参考情報・出典への案内であり、診療・調剤の最終判断を代替しません。用量・換算値・禁忌などは必ず1次資料（添付文書・インタビューフォーム・ガイドライン等）で確認してください。各リンク先の権利は各提供元に帰属します。

## 更新について
このリポジトリのファイルは非公開の作業リポジトリから自動生成したものです。**直接編集せず**、内容の修正依頼は Issue でお願いします。
