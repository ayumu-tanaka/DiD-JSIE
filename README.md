# DiDの近年の展開と実証への応用

## 日本国際経済学会関東支部チュートリアルセッション


現時点での計画は以下の通りです。

日時：11月16日（土）

- 午後2時00分から午後3時15分：解説
- 午後3時15分〜午後3時30分：休憩
- 午後3時30分から午後4時45分：コード紹介と質疑応答

- 会場：日本大学経済学部（水道橋）ハイブリッド方式で開催
- 言語：日本語
- 詳細：[関東支部HP](https://www.jsie.jp/kanto/news/915/)

   
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
特に、処置時期の不均一性に対処するために、異質性に頑健なDiD推定量（heterogeneity-robust DiD estimators）が開発された。
本講義では、こうしたDiDの近年の展開を展望し、計量経済学やRプログラミングの基本的な知識は前提として、初学者向けにDiDの実践的な内容に絞ってお話しする。
国際経済学のトピック（例：重力方程式）にも触れる。
時間の制約があるため、膨大な研究のごくわずかにしか、またごく表層的にしか触れることはできない。
コード紹介では、Rを主として用いる。Posit Cloud / RStudio を推奨。
資料・詳細はGitHub（[https://github.com/ayumu-tanaka/DiD-JSIE](https://github.com/ayumu-tanaka/DiD-JSIE)）に掲載。


## 資料

### スライド（75分）

- [DiDの展開](https://rpubs.com/ayumuR/Roth2023survey_short): [HTML](https://ayumu-tanaka.github.io/DiD-JSIE/DiD_notes02_Roth2023survey_short.html) / [PDF](DiD_notes02_Roth2023survey_short.pdf)

<!--
  - [Pedro Sant'Anna氏による解説動画](https://youtu.be/Jyat3OZLyRc?si=RXkz6Ma0POrOeu6w)
-->

### Rコード（75分）


- [重力方程式を用いた2元固定効果差の差推定](https://rpubs.com/ayumuR/gravity_fixest_twfe): [HTML](https://ayumu-tanaka.github.io/DiD-JSIE/gravity_fixest_twfe.html)

- [重力方程式を用いた多期間差の差推定](https://rpubs.com/ayumuR/gravity_fixest_es): [HTML](https://ayumu-tanaka.github.io/DiD-JSIE/gravity_fixest_es.html)

<!--  重力方程式を用いた時差あり差の差推定 -->

- 最低賃金の若年雇用への影響: [R版](https://rpubs.com/ayumuR/DiD-Wage) / [Stata版](https://rpubs.com/ayumuR/DiD-Stata-Wage)

