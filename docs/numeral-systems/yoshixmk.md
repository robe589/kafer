# yoshixmk

## Repository

<https://github.com/yoshixmk/griglia/tree/main/problems/numeral-systems>

## 初めの方針
- 方式は、数値から文字列の、組み立て方法だけを書く。
- 方式はbaseクラス作る（方式base）。数値を持たせる
- 区切りのロジックは外だし。方式baseに持たせる。
- 方式は、ファクトリークラスを経由して作られる

## よかったところ
- 最初の設計方針を踏み外さないまま、勧められた
- テストファーストで進められた

## 心残り
- 「インド方式」は2つのコンマと3つのコンマで分けて考える必要があり、regexpの難易度がさらに上がるため、ロジックをかけなかった
- 最後にFactoryを作っていたのだが、作りきれていない。
