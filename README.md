[![MIT License](http://img.shields.io/badge/license-MIT-blue.svg?style=flat)](LICENSE)

# subject_eval
## 概要
音声の主観評価実験XABテストを実施できるデスクトップアプリです.以下のような機能があります.
* 初回聴取時の音声強制再生
* 音声の任意再生(リピート再生)
* AorB選択時に, 正解と回答を記録に残す機能(ログ機能)
* テスト試行ごとに, 提示する音声がランダムで変わる機能(ランダム試行機能)

ランダム試行機能についてはpythonで実装しています.

## 動作環境
node v8.4.0
electron v1.6.11
python3 3.6

## 動作確認
1. Install `Node.js` and `electron` yourself.
1. `git cloe https://github.com/Akio-m/subject_eval.git`
1. `electron .`

