This study's initial dataset was obtained from Google Research. This dataset can be retrieved by running:
```
wget -P data/full_dataset/ https://storage.googleapis.com/gresearch/goemotions/data/full_dataset/goemotions_1.csv
wget -P data/full_dataset/ https://storage.googleapis.com/gresearch/goemotions/data/full_dataset/goemotions_2.csv
wget -P data/full_dataset/ https://storage.googleapis.com/gresearch/goemotions/data/full_dataset/goemotions_3.csv
```

Alternatively, you can also download the csv files in this folder, or you can use the following command to copy the entire directory:
```
gsutil cp -r gs://gresearch/goemotions/data/full_dataset/ .
```
