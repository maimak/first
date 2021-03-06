# first
Git Hubの確認用です。以下はMarkdownの記法です。

# H1の見出しです。
###### \#の数でレベルを変えます。(これはH6です)

# 改行
文章の末尾に半角スペースを2つ入れると  
改行します。 1つだとしません。

# 引用
> \>を文頭につけると引用になります。
>> 入れ子にできます。

# リスト
* \*、+、-のいずれかを文頭につけるとリストになります。
  * タブ(として扱うスペースの入力)で階層が変わります。
    * 3段目
    - 行頭文字は混在していても同じ階層です。

# リスト(数字)
1. "1."のように数字+ピリオドで数字のリストになります。
1. 同じ数字を指定しても連番になります。
    1. 階層を変えるのは普通のリストと同じ(はず)です。(スペース2つだと連番になった。。)
9. 数字を変えても連番は続きます。

# チェックボックス
- [ ] リスト文字のあとに[ ]でチェックボックスが表示されます。
1. [x] チェックを入れるには[x]とします。数字リストの文字でも表示は変わりません。

# 水平線
3つ以上の-、*、_を並べると
***
水平線が引かれます。

# リンク
## 自動リンク
\<URL>で自動的にリンクになります。  
<https://www.google.com>
## 文字列にリンクを設定
\[文字列](URL "Alt文字列(オプション)")で文字列にリンクを設定できます。  
文中でも[Google](https://www.google.com/, "ぐーぐる")大丈夫です。

# 強調
\*、-1つで囲むと*斜体*  
2つで囲むと**太字**  
3つで囲むと ___斜体太字___ →前後にスペースを入れないとならない？  
になります。

# 画像
\![文字]\(URL)で画像を表示します。

# 取り消し線
\~2つで囲むことで ~~取り消し線~~ が表示されます。

# コード表記
\`で囲むことでコードの一部を表現できます。  
コマンドは `npm install --save` です。  

複数行に渡るコードを書きたい場合は\`や~3つで開始行～終了行を囲みます。
```
<div id="contents">
  <span id="button">更新</span>
</div>
```
\```のあとに言語名を付けることでシンタックスハイライトが適用されます。(下は```html)
```html
<div id="contents">
  <span id="button">更新</span>
</div>
```

# 表
\|項目名1|項目名2|項目名3|  
\|---|:---:|---:| (ヘッダとボディの区切り。:を付けた位置で横位置を揃えます)  
\|値1|値2|値3|  
と記述することで表を表示できます。  

|項目名1|項目名2|項目名3|
|---|:---:|---:|
|値1|値2|値3|

# ページ内リンク
\[テキスト](#見出しの文字列)で、#を使用した見出しの箇所へのリンクを設定可能です。  
[戻る](#リスト)
