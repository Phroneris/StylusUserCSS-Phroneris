## 概要
Chrome/Firefox/Opera拡張機能「[Stylus](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne)」で自分が使っているカスタムCSS。  
よろしければご自由にお使いください。

## 利用方法

### 全ファイル共通
+ 以下のいずれかの方法でStylusに追加可能。
  + ファイルをローカルに保存して、Stylusの管理ページで「スタイルをインポート」。  
  + コードをGitHub上でコピーし、Stylusの管理ページで「新スタイルを作成」し、ペーストして適当な名前をつけて「保存」。
  + ファイルがUserCSSの場合は更に簡単な追加が可能（後述）。
+ 追加後は、必要に応じて手動で対象サイトを指定すべし（特にMastodon用CSSの場合）。

### ただのCSSファイル
コード冒頭に`==UserStyle==`を含まず、ファイル名が`*(".user"以外).css`のもの。
+ コピペで追加する場合は、「Mozilla形式のコードを貼り付ける」というダイアログが出たら「スタイルを上書き」を選ぶ。

### UserCSSファイル
コード冒頭に`==UserStyle==`を含み、ファイル名が`*.user.css`のもの。  
Stylus内のスタイル名横の歯車マークから、柔軟なオプションを指定できる。ただのCSSと違ってこれが便利。  
仕様等の[詳細はこちら](https://github.com/openstyles/stylus/wiki/UserCSS)。
+ **UserCSS限定のお手軽な追加方法**（推奨）：  
  Stylus導入済みの環境でGitHubの「Raw」などからファイルを直接開くと、自動的にStylusへの追加画面が開く。  
  その画面の「インストール」ボタンを押せばただちに追加が完了する。
  + 以下の各リンクから直接どうぞ。
    + [Mastodonカラム内ユーザーTOPを圧縮.user.css](https://github.com/Phroneris/Stylus/raw/master/Mastodonカラム内ユーザーTOPを圧縮.user.css)
    + [Mastodon未収載アイコン変更.user.css](https://github.com/Phroneris/Stylus/raw/master/Mastodon未収載アイコン変更.user.css)
    + [TogetterコメNG（アイコン、名前、IDを黒塗り）.user.css](https://github.com/Phroneris/Stylus/raw/master/TogetterコメNG（アイコン、名前、IDを黒塗り）.user.css)
+ コピペで追加する場合は、新規作成前に「UserCSSとして」にチェックを入れておく必要がある。  
  そうすると作成時にテンプレートが現れるので、その中身を全て消して貼り付ける。  
  + 初回はめちゃめちゃエラーが出るが、「保存」すると全ておさまる。

## ライセンス
個別に断りがない限り、[CC0-1.0](http://creativecommons.org/publicdomain/zero/1.0/deed.ja)。

## 作者環境（READMEの内容もこれに準ずる）
+ Windows 7 64bit
+ Google Chrome
+ 日本語

## 作者
森の子リスのミーコの大冒険（Phroneris）
