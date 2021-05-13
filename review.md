# Bolt
## 修正内容

1. 「main-top」クラスは「margin-top」ではなく、「padding-top」で余白をとる
  - 「main-top」クラスの「margin-top:70px」を「padding-top:70px」へ変更しました。

2. 「OUR SKILLS」セクションの４つの画像はul,liタグを使用する。
  - 「skill-inner__img-wrap」クラスのdivタグをulタグへ変更し、ulタグ直下のfigureタグをそれぞれliタグで囲いました。

3. 兄弟要素はmarginで余白をとり、marginで余白をとる場合は、上(margin-top)と左(margin-left)で余白をとる。
  - 「work-text」クラスの「margin-right:90px」を消し、兄弟要素の「work-email」クラスに「margin-left:90px」を付与しました。
  - 「skill-inner__title」クラスの「margin-bottom:60px」を消し、兄弟要素の「skill-inner__img-wrap」クラスに「margin-top:60px」を付与しました。
  - 「skill-inner__img-wrap li figure img」の「margin-bottom:15px」を消し、兄弟要素のfigcaptionタグに「margin-top:15px」を付与しました。