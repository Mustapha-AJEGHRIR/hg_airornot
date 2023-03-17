# hg_airornot
See the hugging face competition here https://huggingface.co/spaces/competitions/aiornot

# Data
At the moment of creating this repository, it is impossible to use `load_dataset` to load the data. However, it is possible to downlaod the hugging face dataset and load it manually as a git repo with the following command in the root of this repo :

```bash
$ git submodule init
$ git submodule update
```

These commands will create a folder `data` in the root directory, then run the following command to exctract the data : 

**Note** : the commands above might need your hugging face credentials, the data is in the hugging face web site.


```bash
$ unzip data/train.zip -d data              # Train data
$ unzip data/test.zip -d data               # Test data
```

