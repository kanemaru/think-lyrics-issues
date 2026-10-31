# Think Songs Issues

[Think Songs(シンクソング)](https://think-songs.com/) の不具合と課題を、公開で記録・共有するためのリポジトリです。

Think Songs は、音楽に合わせて歌詞がぴったり同期して流れるサービスです。iPhone・Android・Mac・Windows のアプリと、ブラウザで使える Web 版があります。

## このリポジトリの目的

- いま分かっている不具合と、対応を予定している課題を確認できるようにする
- 修正済みの不具合も記録として残し、いつ直ったかを追えるようにする
- 利用者のみなさんからの不具合報告や要望を受け付ける

ここには Issue の管理だけを置いており、アプリやサーバーのソースコードは含まれていません。

## Issue の見方

| 状態 | 意味 |
| --- | --- |
| Open | 未解決、または対応を検討しているもの |
| Closed | 修正済み、または対応を終えたもの |

修正済みの不具合は [Closed の一覧](https://github.com/kanemaru/think-lyrics-issues/issues?q=is%3Aissue%20is%3Aclosed) から確認できます。

## ラベル

| ラベル | 対象 |
| --- | --- |
| `iOS` | iPhone・iPad 版 |
| `MacOS` | Mac 版 |
| `Android` | Android 版 |
| `Windows` | Windows 版 |
| `HelperApp` | [同期ヘルパー](https://think-songs.com/sync-helper)(Web 版と手元の音楽アプリを一緒に動かすデスクトップアプリ) |
| `bug` | 不具合 |
| `enhancement` | 要望・改善 |

同じ問題が複数の環境で起きているものには、ラベルを併記しています。Web 版やサーバーに関するものには、OS のラベルを付けていません。

## 不具合を報告するには

1. 同じ内容の Issue がないか、Closed も含めて検索してください。
2. 新しい Issue を作り、次の内容を書いてください。
   - 使っているアプリと版(例: iOS 版 1.1.5)、OS の版、機種
   - 音の出力先(内蔵スピーカー、Bluetooth、車載など。音ズレの場合)
   - 操作の手順
   - 期待した動きと、実際の動き

GitHub のアカウントがない方は、[お問い合わせ](https://think-songs.com/contact) からも報告できます。

## Issue に書かないでください

Issue は誰でも読めます。次の内容は書かないでください。

- メールアドレスなどの個人情報、アカウントやログインの情報、購入の情報
- 歌詞の本文(著作権のため)

**セキュリティ上の問題**は公開の Issue に書かず、[お問い合わせ](https://think-songs.com/contact) からご連絡ください。アカウントや購入についての個別のご相談も、お問い合わせで受け付けています。

## リンク

- [Think Songs](https://think-songs.com/)
- [アプリの入手](https://think-songs.com/app)
- [更新履歴](https://think-songs.com/changelog)
- [お問い合わせ](https://think-songs.com/contact)

## English

This is the public issue tracker for [Think Songs](https://think-songs.com/), a service that plays perfectly synced lyrics along with your music on iPhone, Android, Mac, Windows and the web. It holds known bugs and planned work, along with a record of fixed bugs. The source code is not included here.

Please search existing issues, including closed ones, before opening a new one. Do not post personal data, lyrics text, or security problems here. Report security problems through the [contact form](https://think-songs.com/contact) instead.
