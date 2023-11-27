# Style-Transfer
## This Repo Exists as a proof of assignment solution for Dashtoon by Rahul Sawant.

### I have proposed two solutions:
### 1. Self Supervised: Neural Artistic Transfer ([Research Paper](https://arxiv.org/abs/1705.04058#:~:text=The%20seminal%20work%20of%20Gatys%20et%20al.%20demonstrated,is%20referred%20to%20as%20Neural%20Style%20Transfer%20%28NST%29.))
### 2. CycleGAN based Model ([Research paper](https://ietresearch.onlinelibrary.wiley.com/doi/10.1049/ipr2.12342))
#### Even with the help of GPU, it (cycleGAN) is taking around an hour for a single epoch, hence final results cannot be presented as cycleGAN requires huge amount of epochs.

### Note : Due to ongoing placement tests which consume most of our time, it was very difficult to give time to the assignment. So this is my best effort keeping time limitations in mind.

## Results:
![Mona Lisa with Just Content and Style Loss](https://github.com/rahul0906/Style-Transfer/blob/main/mona_lisa_content_and_style_loss.png)
![Mona Lisa with additional variational loss](https://github.com/rahul0906/Style-Transfer/blob/main/mona_lisa_variational_loss.png)
![Canyon Portrait](https://github.com/rahul0906/Style-Transfer/blob/main/__results___24_0.png)

### Cycle GAN Training
In the following screenshot you can see that, it has been more than 15,000 seconds i.e. **more than 4 hours** and merely **3 epochs** have been trained. Which shows the training complexity.


![Screenshot of Ongoing Training](https://github.com/rahul0906/Style-Transfer-Dashtoon-Task/blob/main/Screenshot%20(497).png)

### Another similar project, implemented originally by me (U-NET Architecture): [Image to Sketch Image Translation by UNET Architecture](https://www.kaggle.com/code/squarehare/u-net-image-translation-image2sketch)


## Few Achievements (Also mentioned in Resume):
**Rank 24 | AISGSLA Visual Localisation Challenge | Jul' 2023** \
• 24th Worldwide Rank in the International Competition held by AI Singapore and DrivenData for the prediction of camera pose data from 2D Images \
• Preprocessed more than 12,000 high quality images and used pretrained models like Res-NET and Image-NET to extract features from these images \
• Used Deep Learning Architecture to process and trainthese extracted features and predict all the camera pose data features using Multi-Regression \
• Surpassed various benchmark models like Pretrained Droid Slam with my trained FCNN Deep Learning Model and attained a minimal error of 0.2028


**Rank 49 | NFT Price Prediction Challenge | Feb' 2023** \
• Secured 49th Worldwide Rank in the International Competition held by BitGrit Platform i.e. NFT Price Prediction Challenge to forecast NFT prices \
• Preprocessed a huge tabular dataset with around 40 total number of features and trained and ensembled several Machine Learning models \
• Trained and ensembled models like XG-Boost, LGBM Regressor, FCNN Deep Learning Architecture and Random Forest Regressor, etc \
• Attained an excellent accuracy of 91.18% on the unseen data using the Hybrid Model created with ensembled ML Models and Clustering Models
