# mml-repl-like

# DEMO
https://cat2151.github.io/mml-repl-like/

# twitter
https://twitter.com/cat2151/status/1394331295572922373

# 仕様
- MMLを1文字入力するごとに音が鳴る
  - 入力した音だけ鳴る
  - （chordAreaの場合は、現在行が鳴る）
- カーソル移動で音が鳴る
  - 今カーソルのある場所の音だけ鳴る
  - （chordAreaで上下移動した場合は、現在行が鳴る）
- SHIFT + ENTER または CTRL + S で音が鳴る
  - 現在行が鳴る
  - 範囲選択していた場合は、その範囲の音だけ鳴る
- 演奏中のMMLを表示する

# こんなとき便利
- MMLを書くとき、すぐ音を鳴らしたい
  - キーボードをタイプして0.2秒以内にその音を鳴らしたい
  - SHIFT + ENTER 連打で和音を連打で鳴らしたい
- フレーズをMMLで書くとき、
  - 「鳴らして、変更して」のサイクルを速く回したい
- コード進行をMMLで書くとき、
  - 「鳴らして、変更して」のサイクルを速く回したい
  - カーソル上下でコード進行を素早く鳴らしたい
- ktコマンドでtransposeしながら書きたい
  - 和音でもtransposeしたい
- 生成したMMLを [mml-template-generator](https://cat2151.github.io/mml-template-generator/) で、ほかのMMLに簡易変換したい

# 注意
開発中のため、[Sionic.js Fork版](https://github.com/cat2151/sionicjs/) のほうを使っています。

---
Powered by [SiON](https://github.com/keim/SiON)
and [Sionic.js](https://github.com/minipop/sionicjs/)
and [pico.js](https://github.com/mohayonao/pico.js/)
