# LinkChecker Privacy Policy

Last updated: 2026-10-16

LinkChecker is a browser extension that shows the real destination domain of a link before it opens. This policy explains what data the extension handles.

## Data the developer collects

None. LinkChecker has no server of its own, contains no analytics or tracking, and does not sell or share any data.

## Data processed on your device

- **Links you click**: When you click a link, the extension reads the link's URL and text on your device to show the confirmation dialog. This information is not sent anywhere.
- **Settings and trusted domains**: Your settings and the list of domains you trust are stored with `chrome.storage.sync`. If Chrome sync is turned on, Google syncs them between your browsers signed in to the same Google account.
- **Lookup cache**: Domain registration results are cached in the browser for up to one day, and the list of registry servers for up to seven days.

## Data sent to third parties

- **Domain registration lookup** (can be turned off in settings): To show the registration date and other details, the extension sends **only the domain name** of the link destination (for example, `example.com`, never the full URL) to the registry that manages that domain:
  - RDAP servers of each top-level domain registry, as listed by IANA (`https://data.iana.org/rdap/dns.json`)
  - JPRS WHOIS (`https://whois.jprs.jp/`) for `.jp` domains

  These requests are sent without cookies. The registries' own privacy policies apply to them.
- **Links to external checkers**: The dialog shows links to VirusTotal and Google Safe Browsing. The domain name is sent to those services only if you click those links.

## Contact

If you have questions about this policy, contact: tksg.wtr@gmail.com

---

# LinkChecker プライバシーポリシー

最終更新日: 2026年10月16日

LinkChecker は、リンクを開く前に本当のリンク先ドメインを表示するブラウザ拡張機能です。このポリシーでは、拡張機能が扱うデータについて説明します。

## 開発者が収集するデータ

ありません。LinkChecker は独自のサーバーを持たず、アクセス解析やトラッキングも含まず、データの販売・共有もしません。

## お使いの端末内で処理するデータ

- **クリックしたリンク**: 確認ダイアログを表示するために、クリックしたリンクの URL と表示テキストを端末内で読み取ります。外部には送りません。
- **設定と信頼済みドメイン**: 設定と信頼済みドメインの一覧は `chrome.storage.sync` に保存されます。Chrome の同期がオンの場合、同じ Google アカウントでログインしているブラウザ間で Google によって同期されます。
- **問い合わせ結果のキャッシュ**: ドメインの登録情報は最大 1 日、登録管理団体のサーバー一覧は最大 7 日間ブラウザ内にキャッシュします。

## 第三者に送信するデータ

- **ドメイン登録情報の問い合わせ**（設定でオフにできます）: 登録日などを表示するために、リンク先の**ドメイン名だけ**（例: `example.com`。URL 全体は送りません）を、そのドメインを管理する登録管理団体に送ります。
  - IANA の一覧（`https://data.iana.org/rdap/dns.json`）に載っている、各トップレベルドメインの RDAP サーバー
  - `.jp` ドメインの場合は JPRS WHOIS（`https://whois.jprs.jp/`）

  これらの問い合わせに Cookie は付けません。問い合わせ先のプライバシーポリシーが適用されます。
- **外部サービスへのリンク**: ダイアログに VirusTotal と Google セーフブラウジングへのリンクを表示します。ドメイン名がこれらのサービスに送られるのは、リンクをクリックしたときだけです。

## お問い合わせ

このポリシーについてのお問い合わせ先: tksg.wtr@gmail.com
