## hse_hw3_chromhmm

Была выбрана линия HUVEC, потому что HUES64 в таблице не было.

Ссылка на Colab: https://colab.research.google.com/drive/1lgIn_Z1Kb2qGEQlbFAQgYFiIq64Avqbh?usp=sharing

### 1. Гистоновые метки
| Гистоновая метка | Файл |
|:-------:|:----------------:|
| H2az | wgEncodeBroadHistoneHuvecH2azAlnRep1.bam |
| H3k27ac | wgEncodeBroadHistoneHuvecH3k27acStdAlnRep1.bam |
| H3k27me3 | wgEncodeBroadHistoneHuvecH3k27me3StdAlnRep1.bam |
| H3k36me3 | wgEncodeBroadHistoneHuvecH3k36me3StdAlnRep1.bam |
| H3k4me1 | wgEncodeBroadHistoneHuvecH3k4me1StdAlnRep1.bam |
| H3k4me2 | wgEncodeBroadHistoneHuvecH3k4me2StdAlnRep1.bam |
| H3k4me3 | wgEncodeBroadHistoneHuvecH3k4me3StdAlnRep1.bam |
| H3k79me2 | wgEncodeBroadHistoneHuvecH3k79me2AlnRep1 |
| H3k9ac | wgEncodeBroadHistoneHuvecH3k9acStdAlnRep1 |
| H3k9me1 | wgEncodeBroadHistoneHuvecH3k9me1StdAlnRep1.bam |

### 2. Таблица cellmarkfiletable (папка data)
| Клеточная линия | Гистоновая метка | Файл | Контрольный файл |
|:----------:|:-------:|:----------------:|:----------------:|
| HUVEC | H3k9ac | H3k9ac.bam | Control.bam |
| HUVEC | H3k34me3 | H3k34me3.bam | Control.bam |
| HUVEC | H3k4me1 | H3k4me1.bam | Control.bam |
| HUVEC | H3k4me2 | H3k4me2.bam | Control.bam |
| HUVEC | H2az | H2az.bam | Control.bam |
| HUVEC | H3k27ac | H3k27ac.bam | Control.bam |
| HUVEC | H3k79me2 | H3k79me2.bam | Control.bam |
| HUVEC | H3k27me3 | H3k27me3.bam | Control.bam |
| HUVEC | H3k9me1 | H3k9me1.bam | Control.bam |
| HUVEC | H3k36me3 | H3k36me3.bam | Control.bam |

### 3. Картинки из отчёта ChromHMM

<img src="https://github.com/KirillMatirko/hse_hw3_chromhmm/blob/main/pics/chromhmm_emission.png" width="300" height="350"> <img src="https://github.com/KirillMatirko/hse_hw3_chromhmm/blob/main/pics/chromhmm_transition.png" width="300" height="350"> <img src="https://github.com/KirillMatirko/hse_hw3_chromhmm/blob/main/pics/chromhmm_state.png" width="300" height="350"> 

<img src="https://github.com/KirillMatirko/hse_hw3_chromhmm/blob/main/pics/chromhmm_tss.png" width="500" height="350"> <img src="https://github.com/KirillMatirko/hse_hw3_chromhmm/blob/main/pics/chromhmm_tes.png" width="500" height="350">



### 4. Таблица с эпигенетическими типами

| Номер | Характерные метки | Где проявляется | UCSC browser |
|:---:|:------------:|:---------:|:--------------------------------------------------------:|
| 1 | Нет характерных меток | Ядерная ламина | <img src="https://github.com/KirillMatirko/hse_hw3_chromhmm/blob/main/pics/1.png" width="200" height="150"> |
| 2 | H32K7me3 | Ядерная ламина | <img src="https://github.com/KirillMatirko/hse_hw3_chromhmm/blob/main/pics/2.png" width="200" height="150"> |
| 3 | Сильнее всего выражен в H32K7me3, слабее в H2AZ,
H3K34me3, H3K4me2, H3K36me3| Слабо проявляется в экзонах, CpG островках, TSS и TES| <img src="https://github.com/KirillMatirko/hse_hw3_chromhmm/blob/main/pics/3.png" width="200" height="150"> |
| 4 |  || <img src="https://github.com/KirillMatirko/hse_hw3_chromhmm/blob/main/pics/4.png" width="200" height="150"> |
| 5 | | |<img src="https://github.com/KirillMatirko/hse_hw3_chromhmm/blob/main/pics/5.png" width="200" height="150"> |
| 6 | | |<img src="https://github.com/KirillMatirko/hse_hw3_chromhmm/blob/main/pics/6.png" width="200" height="150"> |
| 7 | || <img src="https://github.com/KirillMatirko/hse_hw3_chromhmm/blob/main/pics/7.png" width="200" height="150"> |
| 8 | | |<img src="https://github.com/KirillMatirko/hse_hw3_chromhmm/blob/main/pics/8.png" width="200" height="150"> |
| 9 | | |<img src="https://github.com/KirillMatirko/hse_hw3_chromhmm/blob/main/pics/9.png" width="200" height="150"> |
| 10 | | |<img src="https://github.com/KirillMatirko/hse_hw3_chromhmm/blob/main/pics/10.png" width="200" height="150"> |
