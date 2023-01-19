```mermaid
graph BT
  1("
    <b>Cages</b>

    👿
    Herald of Faith (1)
    Acolyte of Ash (2)
    ")
  2(Corridor)
  3(?)
  4(Maidens)
  5(Spike Pit)
  6(Carved Stones)
  7(Stairs)
  8(Tomb 2)
  9(Path)
  10(Tomb 3)
  11[/Boss 1\]

  subgraph "Monument of Ash"
    direction BT
    1 --- 2
    2 --- Locked --- 3
    2 --- 4
    4 --- 5
    5 --- 6
    6 --- 8
    6 --- 7
    6 --- 9
    9 --- 10
    9 --- 11
  end

```