```mermaid
flowchart LR
    subgraph 1
    id1["ひとりで効率良く袋入りインスタントラーメンを作って食べる"]
    end
    subgraph 2
    id2["具材を購入する"]
    id3["調理する"]
    id4["食べる準備をする"]
    end
    subgraph 3
    id5["インスタントラーメンを買う"]
    id6["トッピングを買う"]
    id7["調味料を買う"]

    id8["お湯を沸かす"]
    id9["調理道具を準備する"]
    id10["麺を茹でる"]
    id11["トッピングを調理する"]

    id12["どんぶりを準備する"]
    id13["箸を準備する"]

    id1 --> id2
    id1 --> id3 
    id1 --> id4

    id2--> id5
    id2 --> id6
    id2 --> id7

    id3 --> id8
    id3 --> id9
    id3 --> id10
    id3 --> id11

    id4 --> id12
    id4 --> id13
    end