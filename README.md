# primelang

- ソースコードには一つの自然数のみが記述できる。
- 上記自然数を素因数分解し、昇順にソートする。
  - 現行の仕様ではここで2を除く(2何か面白いことできないかな)
- 上記の素因数について順に、16で割った余りが1,3,5,7,9,11,13,15の場合それぞれBrainfuckの><+-,.[]に相当する処理を行う。
