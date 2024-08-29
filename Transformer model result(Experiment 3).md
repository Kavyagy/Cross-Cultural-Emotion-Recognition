# Transformer model result(Experiment 3)

###### Transformer

###### lr:0.0001

###### epoch:100

TRAIN on C1,C2,C4,C5, TEST C4 + C6

### Arousal:

###### Audio single model/image single model/early fusion model

| Modality | CATS-Transformer | -Channel Attention |
| -------- | ---------------- | ------------------ |
| audio    | 0.1889 / 0.0008  | 0.2466 /  0.0008   |
| image    | 0.1578 /  0.0000 | 0.1708 / 0.0000    |
| au-vi    | 0.1548 / 0.0000  | 0.1681/ 0.0000     |

### Valence:

###### Valence single model/image single model/early fusion model

| Modality | CATS-Transformer | -Channel Attention |
| -------- | ---------------- | ------------------ |
| audio    | 0.1161 / 0.0015  | 0.1161 /  0.0019   |
| image    | 0.1341 /  0.0000 | 0.1578  / 0.0000   |
| au-vi    | 0.1202 / 0.0000  | 0.1388/ 0.0000     |