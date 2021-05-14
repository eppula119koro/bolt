# Bolt
## 修正内容

1. 兄弟要素はmarginで余白をとり、marginで余白をとる場合は、上(margin-top)と左(margin-left)で余白をとる。
  - 「service-inner__text-block」クラスの「padding-top: 20px」を「margin-top: 20px」に変更しました。

2. ブロック要素のwidth:100%は外す。
  - 「title」、「service」、「work」、「skill」、「contact」、「footer」クラスの「width: 100%」を削除しました。

3. 「text-align: center」を中央に寄せたいinline要素の親要素に指定する
  - 「.skill-inner__img-wrap li figure img」の「width: 100%」とfigcaptionタグの「text-align: center」を消し、「skill-inner__img-wrap」クラスに「text-align: center」を付与しました。