# about_formulae_of_bessel_functions_in_Abramowitz_and_Stegun
about_formulae_of_bessel_functions_in_Abramowitz_and_Stegun

（以下敬称略）
Debyeの論文を探してたが、1909年のものは見つからなかった。代わりに1910年のはあった。1909年のは実数次数で次数を大きくしたときにハンケル関数がどう振る舞うかのもの。1910年のは次数が複素数の場合に拡張している。

ベッセルはハンケルの実部、ノイマンはハンケルの虚部の関係があります。（実変数の場合）

発端はAbramowitz and Stegunの以下の公式にあります

![1](https://github.com/chibaf/about_formulae_of_bessel_functions_in_Abramowitz_and_Stegun/assets/1296728/67dfb5d8-c767-4e93-ba8c-fa7f0e213a2a)

![1](https://github.com/chibaf/about_formulae_of_bessel_functions_in_Abramowitz_and_Stegun/assets/1296728/63976c92-1c0b-4e88-8c54-a2b2a48cadcc)

ここで$\sim$は私は"asymptotically equal"と読んでます
$\nu$を大きくしたときに比が１に近づくの意味です

Abramowitz and Stegunにはなぜか出典が書いてありません

偶然、岩波数学辞典第4版にDebyeが鞍部点法で計算したとの記述を見つけます

Debyeの計算はNaeherungsformen fuer Zylinderfunkutionen fuer grrosse werte des Arguments und mbeschraenkt veraederliche werte des Index, Math Ann 67, 535--558 (1909)で出版されています

ここでDebyeはDebye's contourという方法で計算している。（まだ勉強していない）出発はHankel関数の複素積分表示です。

数学辞典より 

![1](https://github.com/chibaf/about_formulae_of_bessel_functions_in_Abramowitz_and_Stegun/assets/1296728/2c315f8c-a249-487c-a4ff-e24661352130)

Debye's contourについてはWatsonのベッセル関数本のp237に説明があります（まだ読んでない）

論文は読めてないので、結果だけ引用します

（見つからなかったというのは手元に論文のコピーがなかったという意味です）

DebyeはHankelの次数に関する漸近級数を計算している。
例の公式はこれの一項目を簡略化すれば導ける。

漸近級数の定義については例えば教育出版の大久保先生の本を参照

![1](https://github.com/chibaf/about_formulae_of_bessel_functions_in_Abramowitz_and_Stegun/assets/1296728/bf60f0af-e583-42a1-a392-3712a61df28c)

Debyeの結論(3.13)は第2種のα次のハンケル関数です。

これの第１項をもう少し簡単な関数で近似する計算が下に続きます。αが大きくなるとノイマン関数がハンケル関数の主要な部分になります。ベッセル関数については第1種と2種を足せばノイマンは消えるので、これについて評価すれば良いです。

![In the same manner as this discussion, from the following Dedge's formula(9) we have the](https://github.com/chibaf/about_formulae_of_bessel_functions_in_Abramowitz_and_Stegun/assets/1296728/32671992-59f7-4a6c-bb97-21aa90d09fc3)

数式の記法は現代のやり方に合わせてます

これでAbramowitz and Stegunの式が導出できました。

フーリエ・ベッセル級数のような級数の収束を論じる際にオーダーによる漸近評価が必要になります。
