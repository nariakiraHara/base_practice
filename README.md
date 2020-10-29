# base_practice
基礎プログラム練習用リポジトリ

## 手順
下記コマンドを実行
```
cd ~/
mkdir -p workspaces/ruby_workspace && cd workspaces/ruby_workspace
git clone https://github.com/nariakiraHara/base_practice.git
cd base_practice
code .
```

## 問題１
引数：commandをとり「4より大きければ"勝ち"、4以下であれば”負け”」と出力するような、関数（メソッド）fightを完成させてください。
また、fightメソッドはtimesを使用し10回呼び出すようにし、fightに渡す引数は"0~9"のランダムな数字生成するものとします。

乱数についてはこちらを参照
> https://techacademy.jp/magazine/21527

想定される出力結果
---
![スクリーンショット 2020-10-29 23 37 51](https://user-images.githubusercontent.com/35086740/97588372-c4167500-1a3f-11eb-99fd-be4e72210adf.png)

## 問題2
問題１の答えに少し手を加えましょう。
fightメソッドで判定する条件を
「６より大きければ"勝ち"、３以下であれば”負け”、4以上6以下の場合には"引き分け"」とするよう修正してください。
また問題１同様にtimesを使用し10回呼び出すようにし、fightに渡す引数は"0~9"のランダムな数字生成するものとします。
さらに、引き分けの回数を最後に出力してください。

想定される結果
---
![スクリーンショット 2020-10-29 23 59 35](https://user-images.githubusercontent.com/35086740/97591292-cfb76b00-1a42-11eb-9dce-3b39976caf43.png)
