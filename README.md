## 概要
Chrome/Firefox/Opera拡張機能「[Stylus](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne)」で自分が使っているカスタムCSS。

## 利用方法

### 全ファイル共通
+ 必要に応じて手動で対象サイトの追加が必要（特にMastodon用のもの）。
+ ファイルをローカルに保存して、Stylus管理ページで「スタイルをインポート」すると追加可能。  
  このとき表示拡張子は「すべてのファイル」とするのが良い（デフォルトでは`*.json`しか表示されない）。

### ただのCSSファイル
※ コード冒頭に`==UserStyle==`を含まないもの。拡張子はたぶん`*.css`。
+ 上記方法以外に、コードをGitHub上でコピー→Stylus管理ページで「新スタイルを作成」→ペースト→適当な名前をつけて「保存」でも追加可能。  
  
### Usercssファイル
※ コード冒頭に`==UserStyle==`を含むもの。拡張子はたぶん`*.styl`とか。
+ 上記方法以外に、コードをGitHub上でコピー→Stylus管理ページで「Usercssとして」にチェックを入れて「新スタイルを作成」→出てきたテンプレートを全て消してペースト→「保存」でも追加可能。  
  初回はめちゃめちゃエラーが出るが、「保存」すると全ておさまる。
+ Usercssは、管理ページ等においてスタイル名の横の歯車マークからオプションを指定可能。

## ライセンス
個別に断りがない限り、[CC0-1.0](http://creativecommons.org/publicdomain/zero/1.0/deed.ja)。

## 作者環境（READMEの内容もこれに準ずる）
+ Windows 7 64bit
+ Google Chrome
+ 日本語

## 作者
森の子リスのミーコの大冒険（Phroneris）
