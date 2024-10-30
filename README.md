# Hotel Search Engine
Welcome! This repository outlines details of the my NLP based project - Hotel Search Engine.

## Project Summary
This project aims to develope an advanced hotel search engine that leverages user preferences to suggest hotels instead of traditionally searching for hotel names and locations. As a result, the search outcomes align closely with users' tastes and amenities requirements and make it easy to make informed decisions. Overall, the user experience is enchanced.

## Dataset
The dataset used in taken from ![Kaggle](https://www.kaggle.com/datasets/jiashenliu/515k-hotel-reviews-data-in-europe). Here is summary of the dataset.
| |
|-----------|
| ![image](https://github.com/user-attachments/assets/23f5e03a-aef6-4229-ac2c-6f6f55ede032) |

## Approach
In this project four different versions of word2vec model is developed and experimented.
- Model1: Custom Word2Vec to combine words with similar meanings + BM-25 with doc length normalization
- Model2: Custom Word2Vec + Word2Vec log-likelihood (one vector per word)
- Model3: Pre-trained Word2Vec + Word2Vec log-likelihood (one vector per word)
- Model4: Pre-trained Word2Vec + Word2Vec log-likelihood (one representative vector per doc/review)

| |
|-----------|
| ![image](https://github.com/user-attachments/assets/efedd305-ad6e-45b2-ae34-da3f912d250c) |



## Result
The result achieved has similar performance as the pre-trained model.
| | |
|-----------|----------|
| ![image](https://github.com/user-attachments/assets/346ad81e-a65d-416b-abda-7810b557249e) | ![image](https://github.com/user-attachments/assets/af44fd12-23f0-4cff-ad28-e96b1998348b) |
| ![image](https://github.com/user-attachments/assets/000e4d57-f17d-49e6-8851-d6ceb16cf17b) | ![image](https://github.com/user-attachments/assets/38b9f781-6856-4948-b693-3053691a5286) |


## Tools & Technologies
- **Programming**: Python
- **Frameworks/Libraries**: PyTorch
- **Deep Learning Models**: word2vec
- **Data Sets**: ![515K Hotel Reviews Data in Europe](https://www.kaggle.com/datasets/jiashenliu/515k-hotel-reviews-data-in-europe)

Please hit the like button! :)

