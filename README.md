# DiDの近年の展開と実証への応用

## JSIE関東支部チュートリアルセッション


現時点での計画は以下の通りです。

日時：11月16日（土）

- 午後2時00分から午後3時15分：解説
- 午後3時15分〜午後3時30分：休憩
- 午後3時30分から午後4時45分：コード紹介と質疑応答

- 会場：日本大学経済学部（水道橋）ハイブリッド方式で開催
- 言語：日本語

  
## 講義概要

<!--

応用の分野では、計量理論的な根拠なく、DiD（difference-in-differences）の様々な技法が用いられてきた。
近年、TWFEモデル（two-way fixed effects model）をはじめとするDiDの慣例的な使用に対する批判と新しい手法の開発が急速に進んでいる。
その際たるものが、TWFEモデル（two-way fixed effects model）である。
ここ5年ほどの間に、TWFEモデルをはじめとするDiDの慣例的な使用に対する批判と新しいDiD推定法の開発が急速に進んでいる。
現在では、処置時期に不均一性がある場合、TWFEモデルによる推定値が信頼できないことに幅広い合意が得られている。
処置時期の不均一性に対処するために、多くの新しい有望なDiD（difference-in-differences）推定量が開発されている。
-->


近年、DiD（difference-in-differences）の研究が様々な側面で急速に進んでいる。
特に、処置時期の不均一性に対処するために、異質性に頑健なDiD推定量（heterogeneity-robust difference-in-differences estimators）が開発された。
本講義では、こうしたDiDの近年の展開を展望し、実証への応用のあり方について議論するよう試みる。
時間の制約があるため、膨大な研究のごくわずかにしか、またごく表層的にしか触れることはできない。
大学院レベルの因果推論の知識とRプログラミングの技能を前提とする。コード紹介では、Rを主として用いる。時間があれば、Stataも扱う。




## 資料（適宜更新）

### スライド（75分）

- [DiDの展開](https://rpubs.com/ayumuR/Roth2023survey_short)

### R資料（75分）

- [重力方程式を用いた2元固定効果差の差推定](https://rpubs.com/ayumuR/gravity_fixest_twfe)

- [重力方程式を用いた多期間差の差推定](https://rpubs.com/ayumuR/gravity_fixest_es)

<!--  重力方程式を用いた時差あり差の差推定 -->

### 関連資料

- 田中 鮎夢（2016）「[重力方程式の基本](https://researchmap.jp/ayumu-tanaka/misc/14570985)」『世界経済評論』
- 田中 鮎夢（2023）「【コメント】国際貿易分野におけるDID分析や重力方程式の現状と今後について」大塚啓二郎・黒崎卓・澤田康幸・園部哲史編著『[次世代の実証経済学](https://www.nippyo.co.jp/shop/book/9082.html)』
- Silva, J. S., & Tenreyro, S. (2006) "log of gravity" [田中講義スライド](https://researchmap.jp/multidatabases/multidatabase_contents/detail/251549/a24e2bd8834e0d58884b12e2633de530?frame_id=502471)

