```mermaid
flowchart TB
    0[Start Here]
    1[Docking Bay 2]
    2[Workspace]
    3[Quarters]
    4[Mess]
    5[Washrooms]
    6[Mine Entrance]
    7[Mine Tunnel]
    8[Mine Depths]
    9[Mine Antechamber]
    10[Docking Bay 1]

    0 --> 1
    
    10 ---|Airlock| 2
    1 ---|Airlock| 2

    2 --- 3
    2 ---|Mine Shaft| 6

    3 --- 4
    3 --- 5

    subgraph Mine
        6 ---|Airlock| 7

        7 --- 8
        7 --- 9
    end

    2 -.- 4 & 5
    4 -.- 5
```
```statblock
layout: Basic Pathfinder 2e Layout
name: Test
level: 20
alignment: Chaotic Evil
size: Medium
perception:
  - name: "Perception"
    desc: "Perception +40; __darkvision__"
languages: All
ac: 42
```
