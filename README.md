# typing game 

![screen](https://github.com/user-attachments/assets/acd027a0-cfa4-49d8-a4c5-f9185012382c)

# Overview 
* ストーリー付きゾンビタイピングゲーム
* story1-3 -> game1 -> story4-7 -> game2 -> story8-9 -> game3 -> story10 という構成
* playerは最終的なスコアが高いことを目的とする

# Requirements
* windows11 Pro
* Unity 2022.3.46f1

# Usage
* 表示されたwordを60秒間でできるだけ多くタイピングする
* タイマーが360度回転するまでに入力が未完了 -> 10ダメージを受ける
* 初期HP(Hit Point)が100であり、これが0になるとGame Over
* タイプミスが多い場合はたとえクリアした場合でも、最終スコアが大幅に減少する
* 左下の設定ボタンから一時停止やボリュームチェンジが可能
* 難易度はgameが後半に進むにつれ、上昇する
* "chi"や"ti"などの複数入力に対応

# Discription

<img width="812" alt="game-screen" src="https://github.com/user-attachments/assets/9072305d-8751-4c02-b2a4-a65402557e66" />

* HP(左上) : 60以上で緑, 30-50で黄色, 20以下で赤
* タイマー(右上 左側) : 60秒からカウントダウン 0になるとゲームが終了
* 時計(右上 右側) : 1問あたりのカウントダウン　gameごとに条件が厳しく設定されている
* スコア (中央右側) : タイピングによって獲得したスコアの表示　(タイピングミスは除く)
* 問題 / スペル / 入力画面 (下中央) : 誤っている単語は赤く表示される
* 一時停止 (左下) : 一時停止や音量調整が可能

