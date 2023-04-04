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

<img src="https://github.com/KirillMatirko/hse_hw3_chromhmm/blob/main/pics/chromhmm_emission.png" width="350" height="400"> <img src="https://github.com/KirillMatirko/hse_hw3_chromhmm/blob/main/pics/chromhmm_transition.png" width="350" height="400"> <img src="https://github.com/KirillMatirko/hse_hw3_chromhmm/blob/main/pics/chromhmm_state.png" width="350" height="400"> 

<img src="https://github.com/KirillMatirko/hse_hw3_chromhmm/blob/main/pics/chromhmm_tss.png" width="500" height="350"> <img src="https://github.com/KirillMatirko/hse_hw3_chromhmm/blob/main/pics/chromhmm_tes.png" width="500" height="350"> 
