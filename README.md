# Country Image in COVID-19 Pandemic: A Case Study of China

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

## Citation

To be added.
