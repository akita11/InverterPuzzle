# InverterPuzzle

<img src="https://github.com/akita11/InverterPuzzle/blob/main/InvPuz.jpg" width="480px">

CMOSプロセスで設計したインバータ（NOTゲート）のレイアウトと3次元構造を模したアクリルパズルの加工データです。

<img src="https://github.com/akita11/InverterPuzzle/blob/main/side.jpg" width="480px">

コンタクト・Viaを黒アクリルで加工すると、横からみたときに縦方向の接続がわかりやすいです。（特に拡散とゲートが同じCnt穴でもエッチングが止まるところ＝Cntが埋まるところが違うのが見どころ）

※[Boothで販売中です](https://akita111.booth.pm/items/5187072)

## 組み立て方
以下のレイヤと色の対応をみながら、インバターのレイアウトをつくります。
- 薄ピンク: Psub
- 薄緑: Nwell
- ピンク: P+
- 緑: N+
- 透明: 酸化膜
- 赤: PolySi
- 水色: Metal1
- 黒: CNT（コンタクトホール）

各層は、こちらの写真のようになります。途中の赤線のところに、ゲート酸化膜の薄膜（トレーシングペーパー等）がはさまります。また一番上層には1mm透明カバーが載ります。これらを重ね、四隅をねじで固定します。

<img src="https://github.com/akita11/InverterPuzzle/blob/main/config.jpg" width="480px">

## 作り方

### 用意するもの
- 3mmアクリル板（透明）
- 3mmアクリル板（黒）
- 薄い透明シート（OHPシート、トレーシングペーパー等）
- M3x30ねじ＋ナット(4組）

### 作り方

- 3mmアクリル板を、inv_cut.pdf（一番下の横長長方形以外は透明板。右下の5mm角正方形部品は黒色板）でレーザーカッター等でカットします。（5mm角の正方形の部品（コンタクトホール）がなくなりやすいので注意）
- 薄い透明シートを、inv_cut.pdfの一番下の横長長方形の形状にカット（ゲート酸化膜）
- UVプリンタで、inv_UV_print.pdfのデータを、カットした部品を並べて印刷。このときinv_UV_base.pdfをアクリル板等でカットしておくと位置合わせがやりやすい。

## Author

Junichi Akita (akita@ifdl.jp / @akita11)
