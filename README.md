## 『線形代数の半歩先 データサイエンス・機械学習に挑む前の30話』 サポートページ

### 書籍情報
大久保 潤 著,『線形代数の半歩先 データサイエンス・機械学習に挑む前の30話』 講談社 (2025）のサポートページです。

出版社のページ: https://www.kspub.co.jp/book/detail/5386477.html

<div align="center">
<img src="https://github.com/junohkubo/linear_algebra_half_book/blob/main/figs/jacket_rgb.jpg" width="200px">
</div>


（更新: 2024.4.4 誤植情報掲載）

***

### 第1版・第2版の誤植
（ミスがあり、大変申し訳ありません）

- (2025.4.4) 第17話の、特異値分解を利用した主成分分析の箇所において、図を作成するためのコードが間違っていました。特徴量ごとに（つまり「列」ごとに）「中心化」すると説明しているにもかかわらず、コードではデータごとに（つまり「行」ごとに）「中心化」をする形になってしまっていました。  
（このミスは、以下のURLでご指摘いただきました。どうもありがとうございます）  
https://x.com/arthappymuseum/status/1907720554976784574?s=53  
説明の本質に修正はありませんが、これにともない、以下の変更が必要です。
   - p.148: 図17.3を以下に差し替え。
   <div align="center">
   <img src="https://github.com/junohkubo/linear_algebra_half_book/blob/main/figs/fig_17_3_svd_result_modified.png" width="500px">
   </div>
  
   - p.149: 式(17.5)の2行下の「三つの特異値だけ残りました」を削除（再計算した結果、ゼロとなる特異値がなく、すべて（四つ）残りました）。
 
- (2025.4.4) p.244: 1行目「データの数をNをしたとき」&rarr;「データの数をNとしたとき」 

