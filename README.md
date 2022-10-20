# On Regret-optimal Cooperative Nonstochastic Multi-armed Bandits

The code to produce all the numerical results in Section 5 in the paper: [On Regret-optimal Cooperative Nonstochastic Multi-armed Bandits](https://openreview.net/pdf?id=UAtoVT1FTmi).

## Dependences

```
numpy 1.20.3
scipy 1.7.1
matplotlib 3.4.3
networkx 2.6.3
```


## Download experiment data

The [data](https://drive.google.com/drive/folders/1qrvurRBXFYdt3wmvnfp2w_pNSb6_JokE?usp=sharing) generated by the experiments is stored in 
- coin_flip_erods_renyi_graph
- coin_flip_path_graph
- coin_flip_regular_graph
- coin_flip_star_graph

Move the four folders into the `experiments/` folder.

## Produce figures in the paper

Run `figures.ipynb` in the `figures` folder which also contains the PNG files of the figures in the paper.

## Run new experiments.

Run `experiments/run.py`
