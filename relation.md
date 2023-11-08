```mermaid
    flowchart LR
    subgraph me
    id1["銀行でお金をおろす
    作業時間10分"]
    id2["スーパーで卵を買う
    作業時間10分"]
    id3["卵を洗う
    作業時間10分"]
    end
    subgraph you
    id4["お湯を沸かす
    作業時間20分"]
    id5["卵をゆでる
    作業時間10分"]
    id6["殻を割る
    作業時間10分"]
    id7["塩を振る
    作業時間10分"]
    end
    subgraph p
    id8["腹筋して腹を減らす
    作業時間30分"]
    end

    id1 --> id2
    id2 --> id3
    id3 --> id5

    id4 --> id5
    id5 --> id6
    id6 --> id7
