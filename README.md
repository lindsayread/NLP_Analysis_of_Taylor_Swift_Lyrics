# **Metis Project 4: NLP Analysis of Taylor Swift Lyrics - Summer 2020**

## About:

I have always found it interesting how Taylor Swift started her career as a seemingly innocent, reserved country singer and has evolved to a very confident, empowered, and somewhat sassy pop star. In this project, I wanted to investigate the main topics that Taylor Swift sings about, how the topics have changed over time, and if these topics have an effect on Album Sales.

After applying some NLP techniques to the lyrics, my NMF model with TF-IDF vectorizer identified 9 topics that Taylor Swift songs fall under:

0. Permanency & Belonging
1. Positivity through the bad
2. Bright and Happy
3. Moving on from the past, thinking about the future
4. Don't want to move on, don't want the time to pass
5. Looking back (sad)
6. Looking back (pondering, with somewhat regret)
7. New Relationship
8. Reflection of the Past

I then used K-Means clustering to fit these topics into 5 clusters, which were then visualized with TSNE (2 components):

0. Mostly topic 3 (Moving on from the past, thinking about the future)
1. Mostly topic 5 (looking back, sad)
2. Mixture of topics 2 and 4 (bright and happy; don't want to move on, don't want time to pass)
3. Mixture of topics 6, 7, 8, and 0 (looking back, pondering, some regret; reflection of the past; new relationship; permanency and belonging)
4. Mostly topic 1 (positivity through the bad)

I found that Cluster 3 has been a steady theme throughout Taylor Swift's career, while clusters 0 and 1 have fluctuated; clusters 2 and 4 have stayed relatively the same.

My analysis also found that cluster 1 (looking back on the past, sad) was by far the most successful (in terms of Album Sales) while cluster 0 (moving on from the past, thinking about the future) was the least successful, which I found kind of sad and ironic.

In this project, you will find a PDF of my presentation, a code file for my EDA and modeling, my data source, other sources used, and the skills/analysis acquired.

## Files:
### Slideshow PDF:
- [TaylorSwift.pdf](https://github.com/lindsayread/NLP_Analysis_of_Taylor_Swift_Lyrics/blob/master/TaylorSwift.pdf)

### Code File:

[TSwiftLyricsJN.ipynb](https://github.com/lindsayread/NLP_Analysis_of_Taylor_Swift_Lyrics/blob/master/TSwiftLyricsJN.ipynb)

### Tableau Visualization Files:

[Project4TableauPresentation.twbx](https://github.com/lindsayread/NLP_Analysis_of_Taylor_Swift_Lyrics/blob/master/Project4TableauPresentation.twbx)

## Data:

[Kaggle: Taylor Swift Lyrics](https://www.kaggle.com/ishaanaditya/taylorswiftlyricsfeatures?select=LyricsFeaturesGenre.csv)

## Other Sources:

[Taylor Swift Wikipedia](https://en.wikipedia.org/wiki/Taylor_Swift)

## Skills & Analysis:

- Natural Language Processing (NLP) techniques
- Unsupervised Learning Techniques
- Tokenization
- LSA
- NMF
- TF-IDF
- CountVectorizer
- K-Means Clustering
- DBSCAN
- PCA
- TSNE
- Cosine Similarity
- Tableau
