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
| 1_Heterochromatin | Нет характерных меток | Ядерная ламина | <img src="https://github.com/KirillMatirko/hse_hw3_chromhmm/blob/main/pics/1.png" width="500" height="250"> |
| 2_Polycomb-repressed | H32K7me3 | Ядерная ламина | <img src="https://github.com/KirillMatirko/hse_hw3_chromhmm/blob/main/pics/2.png" width="500" height="250"> |
| 3_Inactive_Promoter | Сильнее всего выражен в H32K7me3, слабее в H2AZ,H3K34me3, H3K4me2, H3K36me3| Слабо проявляется в экзонах, CpG островках, TSS и TES| <img src="https://github.com/KirillMatirko/hse_hw3_chromhmm/blob/main/pics/3.png" width="500" height="250"> |
| 4_Weak_Promoter| H2AZ | CpG-островки, экзоны и TSS | <img src="https://github.com/KirillMatirko/hse_hw3_chromhmm/blob/main/pics/4.png" width="500" height="250"> |
| 5_Active_Promoter | H2AZ, H3K4me3, H3K9ac, H3K27ac, H3K4me1, H3K4me2, H3K79me2 | CpG-островки, экзоны, TSS, TES и TSSkb |<img src="https://github.com/KirillMatirko/hse_hw3_chromhmm/blob/main/pics/5.png" width="500" height="250"> |
| 6_Strong_Enhancer | H2AZ, H3K9ac, H3K27ac, H3K4me1, H3K4me2 | Ядерная ламина, TES |<img src="https://github.com/KirillMatirko/hse_hw3_chromhmm/blob/main/pics/6.png" width="500" height="250"> |
| 7_Weak_Enhancer | H3K4me1 | Ядерная ламина, TES | <img src="https://github.com/KirillMatirko/hse_hw3_chromhmm/blob/main/pics/7.png" width="500" height="250"> |
| 8_Weak_Enhancer | H3K4me1, HeK79me2 | Гены |<img src="https://github.com/KirillMatirko/hse_hw3_chromhmm/blob/main/pics/8.png" width="500" height="250"> |
| 9_Weak_Txn | HeK79me2 | Гены |<img src="https://github.com/KirillMatirko/hse_hw3_chromhmm/blob/main/pics/9.png" width="500" height="250"> |
| 10_Txn_elongation | Очень слабо выражен в H3K36me3 | Экзоны, гены, TES|<img src="https://github.com/KirillMatirko/hse_hw3_chromhmm/blob/main/pics/10.png" width="500" height="250"> |

### 5. Бонус

Присвоенные имена состояний указаны в таблице выше. Опирался на коллекцию типов в UCSC браузере для линии HUVEC.


Ссылка на отредактированный bed-файл: https://drive.google.com/drive/folders/1gAB0YeoWUMGtVO0kz9deA54vj-CK0KMb?usp=share_link

Ниже команды из бонусной части. Все другие команды из основной части так же есть в колабе.

```python
annotation = ['1_Heterochromatin',
          '2_Polycomb-repressed',
          '3_Inactive_Promoter',
          '4_Weak_Promoter',
          '5_Active_Promoter',
          '6_Strong_Enhancer',
          '7_Weak_Enhancer',
          '8_Weak_Enhancer',
          '9_Weak_Txn',
          '10_Txn_elongation']
```

```bash
!head HUVEC_10_dense.bed
```

```python
with open('HUVEC_10_dense.bed','r') as f:
  lines = f.readlines()
  with open('HUVEC_10_dense_edited.bed','w') as new_f:
    new_f.write(lines[0])
    for i in range(1,len(lines)):
      line = lines[i].split('\t')
      N = int(line[3]) - 1
      line[3] = annotation[N]
      new_f.write('\t'.join(line))
```

```bash
!head HUVEC_10_dense_edited.bed
```

<img src="https://github.com/KirillMatirko/hse_hw3_chromhmm/blob/main/pics/states_with_annotation.png" width="700" height="600">
