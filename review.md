# Bolt
## 修正内容

1. 「inner」の横幅を1100pxへ変更
  - innerクラスのwidthを960pxから1100pxに変更しました。

2. OUR SKILLSセクションの「javascript」の文字が消えている
  - 1個目のfigcaptionタグにクラス名を付けるのを忘れていた為、「skill-content__name」クラスを付与しました。

3. 「Bolt Theme」の見出しはh1タグ。それ以外の見出しはh2タグで統一。
  - 「OUR LATEST WORK」の見出しをh3タグからh2タグへ変更しました。

4. 見出しにはフォントを「Raleway」に。それ以外は「Lato」を指定する。
  - 全てのh1,h2タグに「title-font」クラスを付与し、title-fontクラスのfont-familyをRalewayへ変更しました。

5. 兄弟要素はmarginで余白をとり、marginで余白をとる場合は、上(margin-top)と左(margin-left)で余白をとる。
  - 「title-inner__theme」クラスの「margin-bottom:20px」を消し、兄弟要素の「title-inner__lead」クラスに「margin-top:20px」を付与しました。
  - 「service-title」クラスの「margin-bottom:35px」を消し、兄弟要素の「service-lead」に「margin-top:35px」を付与しました。
  - 「work-inner__title」クラスの「margin-bottom:40px」を消し、兄弟要素の「work-inner__wrap」に「margin-top:40px」を付与しました。
  - 「work-inner__text」クラスの「padding-top:90px」を「margin:90px auto 0 auto」へ変更しました。

6. 「title-inner」クラスのpadding-topが250pxではなく320pxのため、ヘッダー下にpaddingが隠れている。
  - 「title-inner」クラスの「padding: 320px 0 250px 0」を「padding: 250px 0」への変更と、「main-top」クラスに「margin-top:70px」を付与し
  「header」クラスに「top:0, left:0」を付与しヘッダー下にpaddingが隠れ無いようにしました。

7. 「OUR LATEST WORK」セクションの6枚の画像は、ul・liタグを使用して作成する。
  - 「work-inner__wrap」クラスのdivタグをulタグへ変更し、ulタグ直下のaタグをそれぞれ「work-img」クラスのliタグで囲いました。それに伴い下記の修正をしました。
  　・「work-link」クラスを「work-img__link」クラスに名前を変更。
  　・「work-img」クラスに「float: left」と「margin: 80px 0 0 100px」を付与。
  　・「work-img__link」クラスには「opacity: 0.7」と「transition: all 0.3s」のみ付与。
  　・「:nth-child(3n+1)」と「:nth-child(-n+3)」を付けていた「work-link」クラスを「work-img」クラスに変更。
