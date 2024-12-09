# typst-hane
A typst package for drawing go/baduk/weiqi diagrams

<table>
  <tr>
    <td>
      <pre>#figure(
  board("
    . . . .
    . 1 . .
    . O X .
    . . . .
  "),
  caption: [A _hane_.]
)</pre>
    </td>
    <td align=center>
      <img height="150" alt="Typst output showing a go board diagram" src="https://github.com/user-attachments/assets/a05b791b-0d86-4f29-a31d-f185e9103339">
    </td>
  </tr>
  <tr>
    <td><pre>#board("
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
  <img height="220" alt="Typst output showing a go board diagram" src="https://github.com/user-attachments/assets/44cd016f-cc8d-428c-8e62-7c59f3efa83a">

</td>
  </tr>
</table>
