# Bolt (レスポンシブ版)
## 修正内容

1. 「contact-inner」クラスが「padding: 50px 15px 200px 15px」になっていた為、snsアイコンセクションの見た目が、見本より下の余白が大きくなっていた。
  - 「contact-inner」クラスの「padding: 50px 15px」を指定し見た目通りに変更しました。

2. ハンバーガーメニューで擬似要素(::before, ::after)を使用する際、spanタグを３本線の内、中心の線に指定していなかった。
  - 「btn-line」クラスを中心の線に指定し、その位置を基準に上に「::before」、下に「::after」でtopの位置を修正しました。