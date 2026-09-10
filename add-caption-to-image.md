# add-caption-to-image.md

add-caption-to-image.md

## 図や画像にキャプションを入れる

`図1　製品比較表`といったようなキャプションを入れたいことが多いが、HTMLとCSSでも簡単に実現できる。図を入れるための`figure`というHTML要素があり、また図に対して短い説明（キャプション）を入れるための`figcaption`という要素がある。divの配下に画像と文字を入れるのではなく、それ用に作られた構造であるため、文書構造も改善する。

例

```
<figure>
  <img src="example-image.jpg" alt="Just a sample image" />
  <figcaption>図1 Example caption for the sample image</figcaption>
</figure>
```

figcaptionの内容をJavaScriptから書き換えすることで図の番号を自動でカウントすることもできるだろう。

## 参考

https://developer.mozilla.org/ja/docs/Web/HTML/Reference/Elements/figure
https://developer.mozilla.org/ja/docs/Web/HTML/Reference/Elements/figcaption
