# himatsubushi
暇つぶしに遊んだやつをあげるところ.  
ANNだらけですがべつにすきなわけではないです.  
好きなようにやってるので読みづらかったりするかもしれませんが,もし使いたいのであれば好きなようにしてもらって構いません.  
下に書いてあるコードの概要は作ったものから順番になってます.
## add_DNN.ipynb  
足し算をしてくれるNN. DNNって名前についてるけど別にディープじゃない.  
## CNN_practice.ipynb  
CNNを実装する練習.   
## GAN.ipynb  
初めて論文だけを頼りにして実装したNN.  
## reshape_test.ipynb  
tensorflow.reshapeとndarray.reshapeの出力が一致するのかどうかを確かめたくて書いたコード.  
結果的にはたぶん同じっぽい？  
## four_arithmetic.ipynb  
前回足し算をする簡単なNNを作ったので,今回は四則演算すべてを一つのNNにまとめてみた.  
割り算以外はほぼほぼ良いが、割り算は他に比べて少し（+-1未満くらい）エラーが大きい.  
ちなみにどんな感じのモデルかというのがわかるように初めてイメージを載せている.  
ぶっちゃけわける意味ない気がするけど近々わける意味がありそうなモデルを作る予定なのでその練習と分けても精度が出るのかの検証を兼ねてる.  
~~暇になったら同エポックで分けてないNNを使って精度の差を検証してみたいけど多分しない.~~  
かなり雑だけど一応検証する対象となるNNは作りました.おそらく差はほとんどないとおもいます.適当です.
