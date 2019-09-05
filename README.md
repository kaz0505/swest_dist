
# SWESTワークショップ用ファイル

- [Windows用IDE](https://github.com/kaz0505/swest_dist/blob/master/mrubyc_ide1.0_win%EF%BC%88%E9%85%8D%E5%B8%83%E7%94%A8%EF%BC%89.zip)
- [mac用IDE](https://github.com/kaz0505/swest_dist/blob/master/mrubyc_ide1.0_mac%EF%BC%88%E9%85%8D%E5%B8%83%E7%94%A8%EF%BC%89.zip)

# RBoardの組込み関数

（ハンズオンで使用する関数のみ示しています）

- `leds_write <value>`<br/>
ボード上の4つのLEDを制御する。`<value>` に 0x01, 0x02, 0x04, 0x08 の論理和を指定する。

- `SW()`<br/>
ボード上のボタンの状態を返す。ボタンが押されていれば 1 、押されていなければ 0 。

- `sleep_ms <value>`<br/>
`value`で指定する時間（ミリ秒）だけスリープする。

- `puts <value>`<br/>
USBシリアルへ `<value>` を出力する。

