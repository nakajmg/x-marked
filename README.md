# x-marked

x-marked is Web Components module. render markdown to HTML.

---

[demo](http://nakajmg.github.io/x-marked/)

マークダウンで書かれたテキストをHTMLに変換するウェッブコンポーネンツッ

* リストだって
* このとおり

`x-marked`タグを指定すれば使える超簡単！

|テーブル|見出し|
|:-------|:-------:|
|テーブル|だよ|


## 使い方
```
<x-marked>#markdownテキストをいれるとレンダリングされるよ</x-marked>
```

タグに`data-apply-style="true"`をつけるとGitHub風なレンダリングになるよ。

## 使ったもの

* [marked.js](https://github.com/chjj/marked)
* [github-markdown-css](https://github.com/sindresorhus/github-markdown-css)
