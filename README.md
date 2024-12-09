# typst-hane
A typst package for drawing go/baduk/weiqi diagrams

<table>
  <tr>
    <td>
      <pre>#import "@preview/hane:0.1.0": board, stone
#figure(
  board("
    . . . .
    . 1 . .
    . O X .
    . . . .
  "),
  caption: [Black's #stone(black, n: 1) is a _hane_.]
)</pre>
    </td>
    <td align=center>
      <img width="303" height="150" alt="Typst output showing a go board diagram" src="https://github.com/user-attachments/assets/89d454e0-9ed5-41e9-8437-a71a9dfe885f">
    </td>
  </tr>
  <tr>
    <td><pre>#import "@preview/hane:0.1.0": board
#board("
  $$Bc Support for Sensei's Library syntax.
  $$ | . .
  $$ | . X
  $$ | .
  $$ | . X X ,
  $$ | . O X X X
  $$ | . . O O X . X
  $$ | . O . B
  $$ --------
", board-color: rgb("eb9"))
</pre></td><td align=center>
  <img width="444" height="238" alt="Typst output showing a go board diagram" src="https://github.com/user-attachments/assets/44cd016f-cc8d-428c-8e62-7c59f3efa83a">

</td>
  </tr>
</table>
