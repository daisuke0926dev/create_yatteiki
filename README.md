# 概要
ペパボエンジニアが入社時に記述する"yatteiki.md"を作成するrakeです。

# 使い方
1. rakeコマンドを実行 `rake create_template`  
  社員番号と氏名(ローマ字)の入力を求められるので、入力します。  
    <img width="299" alt="スクリーンショット 2023-10-10 16 19 50" src="https://github.com/daisuke0926dev/create_yatteiki/assets/90462400/c1898580-ac1f-4570-a09f-4492e34ee041">


3. 以下内容が記述された`./#{実行時の年}/#{社員番号}_#{氏名}/yatteiki.md`が作成されます。

```:md
# ペパボで私がやっていきたいこと

## 1ヶ月後の目標

## 2ヶ月後の目標

## 3ヶ月後の目標

# 振り返り

## Month 1

TBE

## Month 2

TBE

## Month 3

TBE

# ペパボテックカンパニービジョンの感想

xxxx は yyyy なので zzzz と思った。

```

## 特記
必要なディレクトリが存在しない場合のみ、ディレクトリを作成します。
