# LOL (League of Legends)

**LOL (5v5)** contains 623,263 matches, with 145 heroes involved. Unfortunately, no unique participantId is given for every player across all the matches.
Full data link: [Google Cloud](https://drive.google.com/file/d/1Ff7czpeDpX-sIgIiWNpRgpNYlelo7SQu/view?usp=sharing) or [Baidu Cloud](https://pan.baidu.com/s/1f0svnsbbzRhyA3iJhyYk0A) (code: m5h3)

[<< View the data analysis of all the datasets](../)

# Analysis Method

## 1. Synergy Analysis
Some heroes have beneficial multiplay when teamed up, while some have disadvantageous multiplay.

### 1.1 Analysis of 2-hero combination

| Combinations of heroes        | Win rate         | Co-occurrence count (win) |Co-occurrence count (total) |
|:-------------:|------------------:|------:|------:|
| (48, 72) | 0.765 | 13  | 17|
| (57, 83) | 0.712   | 37  | 52|
| (127, 421) | 0.683      | 41   | 19 |
| (72, 104) | 0.682 | 15  | 7|
| (62, 77)  | 0.675 | 108 | 160|
| ...     |...     |...     |...     |
| (80, 99)  | 0.466 | 12,979 | 27,863|
|(80, 157)|0.452 | 11,014 | 24,355|
|(80, 222)| 0.489 | 10,690 | 21,848|
|(80, 555)| 0.469 | 9,937 | 21,180 |
|(80, 202)| 0.475  | 10,005 |21,051 |
| ...     |...     |...     |...     |

### 1.2 Analysis of 3-hero combination

| Combinations of heroes        | Win rate         | Co-occurrence count (win) |Co-occurrence count (total) |
|:-------------:|------------------:|------:|------:|
| (106, 157, 497) | 0.716 | 73  | 102 |
| (22, 143, 238) | 0.709   | 73  | 103 |
| (11, 18, 36) | 0.701      | 75   | 107
| (131, 222, 238) | 0.699 | 79  | 113 |
| (19, 55, 75)  |  0.697  | 83  | 119 |
| ...     |...     |...     |...     |
| (80, 99, 222) | 0.502  | 1333 | 2653 |
| (80, 497, 498) | 0.485 | 1254 | 2583 |
| (80, 99, 202) | 0.483 | 1233 | 2553 |
| (51, 80, 99)  | 0.490 | 1194 | 2439 |
| (80, 99, 157) | 0.466 | 1097 | 2356 |
| ...     |...     |...     |...     |

### 1.3 Visualization of Synergy relationship

## 2. Suppression Analysis

### 2.1 Analysis of 2-hero combination

| Combinations of heroes        | Win rate         | Win count | Match count |
|:-------------:|------------------:|------:|------:|
| (80, 99)->(157, 555) | 0.415 | 164  | 395 |
| (80, 99)->(497, 498) | 0.464 | 170  | 366 |
| (80, 99)->(157, 222) | 0.431 | 157  | 364 |
| (80, 99)->(157, 412) | 0.511 | 185  | 362 |
| (80, 157)->(86, 99)  | 0.417 | 146  | 350 |
| ...     |...     |...     |...     |
| (103, 222)->(80, 157) | 0.744 | 87 | 117 |
| (24, 67)->(80, 81) | 0.738 | 76 | 103 |
| (497, 498)->(80, 107) | 0.725 | 87 | 120 |
| (11, 45)->(80, 157) | 0.724 |76 | 105|
| (45, 555)->(80, 99) | 0.722 | 96 | 133 |
| ...     |...     |...     |...     |


### 2.2 Analysis of 3-hero combination

| Combinations of heroes        | Win rate         | Win count | Match count |
|:-------------:|------------------:|------:|------:|
| (59, 86, 99)->(80, 238, 412)| 0.8 | 8  | 10 |
| (59, 86, 99)->(80, 497, 498) | 0.4   | 4  | 10 |
| (59, 86, 99)->(80, 145, 555) | 0.667      | 6   | 9 |
| (80, 84, 412)->(86, 99, 517) | 0.444 | 4  | 9 |
|(25, 157, 222)->(64, 84, 99)| 0.555 | 5 | 9|
| ...     |...     |...     |...     |
|(19, 55, 497)->(59, 238, 266)|  1 | 1 | 1 |
| ...     |...     |...     |...     |


### 2.3 Visualization of Suppression relationship
