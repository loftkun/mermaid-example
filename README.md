# mermaid-sample

## jiro flow

```mermaid
graph LR
    A{add garlic?}
    B[OK]
    C[protocol error <br>]
    D[as is]
    E[garlic]
    F[vegetable]
    G[oil]
    H[sauce]
    A -->|YES or No| C
    A --> D
    A --> E
    E --> F
    A --> F
    F --> G
    A --> G
    G --> H
    A --> H
    D --> B
    E --> B
    F --> B
    G --> B
    H --> B
```

## questionnaire of first move of shogi

```mermaid
pie title 好きな初手は？
    "７八銀" : 48
    "８六歩" : 32
    "１八香" : 16
    "その他" : 4
```

堂々の1位は７八銀となった。<br>
△３四歩に対して▲７六歩と突けなくなる最悪の初手である。<br>

そこで▲６六歩と指す手がある。これに対して、<br>
1) △同角には▲６八飛とパックマン戦法に切り替えていく
2) △８四歩には▲７六歩と突いて通常の将棋に戻すこともできる

といった指し方があり、最悪の初手と言われながらも意外と指せるかもしれない、味わい深い初手と言えよう。

2位の初手８六歩は後手が８筋を伸ばすと飛車先の歩を切られることを免れない最悪の初手である。<br>
しかしながら▲７八金と上がっておくことにより1歩損するわけでもないためすぐに悪くなることはないだろう。後手側からこの手を咎め文字数
