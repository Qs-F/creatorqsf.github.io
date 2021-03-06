---
layout: default
title: なぜPythonが人工知能の開発に適しているのか
---

今宵の月はどうでしょう。こんばんは、[@CreatorQsF](http://f.9en.co/?move=mainSns)です。  
最近では人工知能の人気が凄いですね。この波がまたいつ終わってしまうのかと思うと少々怖いですが、できればこのまま続行していただきたいものですね。

さて、今日はそんな中でもなぜPythonがAIの研究では多く用いられているのか、についてのお話です。もちろんRなどが悪いと言って否定しているわけではありません。というよりここで話す内容はむしろRの方に軍配があがるとも言えます。しかし、Rでは現在汎用性が皆無です。統計学ように作られた言語であるために、初心者などの参入がとてもしにくい現状があります。  
そこで、ここではPythonに区切ってお話します。多分Rと置き換えても通じるところはたくさんあるでしょう。

***

## インタプリタ型言語とコンパイラ型言語

そもそもこの違いはみなさんお分かりでしょう。ちなみにスクリプト言語とインタプリタ型言語は違いという違いはなく、そもそもの意としてスクリプトはコードが書かれたファイルのこと、インタプリタはコンパイラー的な意味合いでありましたが近年はほぼ同義で使われているような気もします。間違っていたらすみません。

ちなみにPythonはインタプリタ型言語です。なので型がないと言ってもいいです。もちろんあるにはあるのですが、動的型付け言語のためにあまり意識する必要はないです。それでいて速いので、とても重宝されています。  
しかし、Cなどの静的型言語の方が実行速度などは速いのは当たり前です。大量のデータを扱うAIの研究はどうしてわざわざ遅いPythonを好むのでしょうか。

それは、その大量のデータを処理することこそにヒントがあります。

そもそも機械学習とは統計学などの様々な分野の寄せ集めであります。そのため本当に色々な数式と多種多様なデータを双方向的に扱うことになります。ここにいちいち型を持ち込んでいるとすごく厄介なのです。

プログラミングとは**非常に高い水準の効率性**を求められます。つまりそれの意味するところとは、実行の早さと仮説検証までの早さの比べっこです。いくら実行が早くてもそのデータ入力やコーディング事態に時間がかかっていると本末転倒です。しかし、実行速度は犠牲にされるわけにもいかない。そのうまいところを突いているのがPython、というわけです。

***

わかってしまえば簡単なはなしなのですが、面白いと思うので、私の考えるPythonがなぜ好まれるかをこの分野を見ながら書いてみました。実を言いますとRにはまだ正面からはきちんと触れたことがありません。私のこういう系の学習もtensor flowを試してみたところまでで中断されています。忙しくて…(言い訳)

是非とも、いろんな人がこの分野に関わると、これからもっともっと楽しくなるのになぁ、そう感じてやまないです。

おわり