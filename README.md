## Dataset

- https://www.kaggle.com/datasets/adityajn105/flickr8k

- Dataset is also available in the /Images folder

## Install libraries
```bash
pip install pyspark
pip install findspark
pip install tensorflow
```

## Start pyspark
```bash
pyspark
```
## Results
```txt
1 epoch
BLEU-1: 0.476257
BLEU-2: 0.294542
start a dog dog end
start a young girl in a and in a end
start a man in a snow end
```

```txt
5 epochs
BLEU-1: 0.631810
BLEU-2: 0.444975
start two dogs are playing with a ball end
start a girl in a yellow dress is playing in the grass end
start a skier in a red jacket is skiing in the snow end
```

```txt
20 epochs
BLEU-1: 0.535163
BLEU-2: 0.303571
start two dogs play with on the sidewalk each other end
start two children are sitting in the below the rainbow end
start four people standing on snow in costumes end
```

```txt
100 epochs
BLEU-1: 0.934329
BLEU-2: 0.917832
black dog and white dog with brown spots are staring at each other in the street
little girl is sitting in front of large painted rainbow
skier looks at framed pictures in the snow next to trees
```
