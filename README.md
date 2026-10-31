# 落下 単語 タイピング ゲーム

英単語が Canvas 上部から落下してくる前に正確にタイピングして消すゲーム。速度段階・スコア記録付き。

## 機能
- Canvas 上で英単語が落下。入力欄にタイプするとマッチした単語が消える
- 単語が底に達するとライフ -1（ライフ 3 個）
- 英単語リスト（100 語・easy/medium/hard 難易度別）内蔵
- レベルアップで落下速度が上昇
- ゲームオーバー画面とリスタート機能
- ハイスコアを LocalStorage で保存

## 技術
- Vanilla JS + Tailwind CSS CDN
- Canvas 2D API
- localStorage
