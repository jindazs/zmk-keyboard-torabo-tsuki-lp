
[torabo-tsuki LP](https://github.com/sekigon-gonnoc/torabo-tsuki-lp)用のZMKファームウェア

* _centralがついているuf2をトラックボールがついている方に、_peripheralを反対側に書き込んでください
* キーマップはkeymap-editorおよびzmk-studioで編集できます

## キーマップ (Keyball39 互換 / S サイズ)

Keyball39 のキーマップを移植し、Mac 用と Windows 用のレイヤーを排他的に切り替えて使う構成です。

| # | レイヤー | 呼び出し |
|---|---|---|
| 0-4 | Mac: Base / Nav / Sym / Num / Fn | 起動時は Mac |
| 5-9 | Windows: Base / Nav / Sym / Num / Fn | |
| 10 | Scroll (押している間トラックボールがスクロール) | Mac: 右下 / Windows: 右下の左隣 |

* 切り替え: Space 長押し + 左内側キーで Mac、右内側キーで Windows (再起動・スリープ復帰後は Mac に戻る)
* Bluetooth: Space 長押し + 右下段の 3 キーで接続先 0/1/2、右下で現在の接続先をクリア
* Windows 側の違い: Ctrl と Win の位置を入れ替え、Cmd 系ショートカットは Ctrl、英数/かなは 無変換/変換、右下は F13
