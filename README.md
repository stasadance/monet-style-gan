# monet-style-gan

In this notebook, we are delving into the world of Generative Adversarial Networks (GANs), specifically focusing on generating images that resemble the distinctive style of the renowned impressionist painter Claude Monet. The task is to create a model capable of translating common photos into images mirroring Monet's unique artistic essence, using a dataset provided on Kaggle which includes a collection of Monet’s paintings and a diverse set of photos.

The dataset is divided into two main categories:
1. Monet Paintings – present in both JPEG and TFRecord formats.
2. Photos – available in JPEG and TFRecord formats as well.

Our objective is to eventually build a GAN model that can generate thousands of Monet style images.

First we will perform an initial Exploratory Data Analysis (EDA) to understand the characteristics, patterns, and distributions present in the datasets before moving on to the modeling phase. We will try build a strong GAN model architecture and do analysis on its performance and try to submit the best possible score for the competition.
