# COVID19-CountryImage

This repo opens the labeled dataset used in an upcoming paper in which the image of China during COVID-19 is analyzed by performing an aspect-based sentiment analysis (ABSA) on Twitter data.

## About the dataset

Each example in the dataset is made up of nine attributes:

- `status_id`: The ID of the tweet. (To comply with Twitter's Terms of Service, we are only releasing the `status_id`'s of the tweets. You can use [this program](https://github.com/DocNow/hydrator) to convert the `status_id`'s back into the tweets.)
- `politics`: The sentiment toward Chinese politics in the tweet.
- `economy`: The sentiment toward Chinese economy in the tweet.
- `foreign`: The sentiment toward China's foreign affairs in the tweet.
- `culture`: The sentiment toward Chinese culture in the tweet.
- `situation`: The sentiment toward the epidemic situation in China in the tweet.
- `measures`: The sentiment toward China's measures against the epidemic in the tweet.
- `racism`: The sentiment toward racism related to China in the tweet.
- `overall`: The overall sentiment toward China in the tweet.

For all the sentimental attributes, `0` stands for "not related", `1` for "negative", `2` for "neutral" and `3` for "positive."

## Data Collection

This dataset is built on another [dataset](https://github.com/echen102/COVID-19-TweetIDs) which includes COVID-19-related tweets. We filter a sample of that dataset with the following China-related keywords:

- china
- chinese
- cn virus
- prc
- wuhan
- hubei
- wu han
- hu bei
- ccp
- cpc
- communist
- communism
- socialism
- socialist
- beijing
- shanghai
- shenzhen
- tibet
- xinjiang
- uyghur
- eastturkistan
- east turkistan
- huawei
- xijinping
- liwenliang
- wuflu
- huoshenshan
- leishenshan
- findqiushi
- chenqiushi

## Citation

Please cite this [paper](https://ieeexplore.ieee.org/document/9195107) if you use this dataset:

H. Chen et al., "Country Image in COVID-19 Pandemic: A Case Study of China," in IEEE Transactions on Big Data, doi: 10.1109/TBDATA.2020.3023459.

*or in bibtex:*

@ARTICLE{9195107,  author={H. {Chen} and Z. {Zhu} and F. {Qi} and Y. {Ye} and Z. {Liu} and M. {Sun} and J. {Jin}},  journal={IEEE Transactions on Big Data},   title={Country Image in COVID-19 Pandemic: A Case Study of China},   year={2020},  volume={},  number={},  pages={1-1},}
