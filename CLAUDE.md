# ios-app-prototype — セッションルール

## このディレクトリのマスターセッション

**このディレクトリ (`ios-app-prototype`) は専用セッションが管理するマスターです。**

ホームディレクトリ (`/Users/mhigashino`) など、別の作業ディレクトリから起動したセッションは、以下のファイルを直接編集してはいけません：

- `index.html`
- `02.html`（参照スナップショット）
- その他 `.html` ファイル

## セクション別オーナーシップ

| セクション | オーナー | 備考 |
|---|---|---|
| `#screen-search` | ios-app-prototype session | 検索画面。ここで一元管理 |
| `#screen-home` | ios-app-prototype session | |
| `#screen-auction` | ios-app-prototype session | |
| `#screen-list` | ios-app-prototype session | |
| `#screen-wallet` | ios-app-prototype session | |
| CSS / JS | ios-app-prototype session | |

## セッション別の編集対象

| セッション | 編集可能ファイル |
|---|---|
| ios-app-prototype 専用セッション | `index.html`、全ファイル |
| ホームDir セッション（セッション 23fda683） | `04.html` **のみ** |

## 他セッションへの指示

別ディレクトリ起動のセッション（例: ホームDir セッション）がここで作業する場合：

1. `index.html` を **直接編集しない**
2. `04.html` **のみ**を編集対象とすること
3. `index.html` に変更が必要な場合は、ios-app-prototype 専用セッションで行うこと

## コミット・プッシュ

- すべての変更後に commit & push すること（このセッションの確立済みワークフロー）
