# 特定の文言のXPATH 指定
* 特定のラベルがあるところの同レベルの階層にある別のdivタグを指定

`{0}` の部分をパラメータにする。

```
/html/body/div[2]/div/div[2]/div[2]/div[2]/div/div/div[1]/a[text()="{0}"]/../../div[2]/div/a[text()="クリックしたいラベル"]
```
* 部分一致でラベルをクリック

```
/html/body/div[2]/div/div[2]/div[2]/div[2]/div/div/div[1]/a[starts-with(text(),"{0}")]
```
