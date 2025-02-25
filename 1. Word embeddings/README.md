# Word Embeddings

Word embeddings are an important part of Natural Language Processing. Having good dense representation of words really improves the performance on several tasks like Language modelling, machine translation etc. Also, the representations capture various similarity and differences between words which is very cool. I used this [Wikipedia page](https://en.wikipedia.org/wiki/French_Revolution) as my dataset.

**DISCLAIMER** : Only 'Word embeddings.ipynb' of the above 3 notebooks is complete and works. 

### Results and Plots

**Training loss v/s iterations (after gaussian smoothing)**

![loss](https://github.com/jayeshk7/Intro-to-NLP/blob/master/1.%20Word%20embeddings/images/loss.png)

**PCA plots over a few epochs**

I didn't check the quality of my word embeddings on any task. But I think the plots make a little sense because french govt and french revolution are more likely to occur in the dataset than french revolutionary.

![1](https://github.com/jayeshk7/Intro-to-NLP/blob/master/1.%20Word%20embeddings/images/1.png)
![2](https://github.com/jayeshk7/Intro-to-NLP/blob/master/1.%20Word%20embeddings/images/2.png)
![3](https://github.com/jayeshk7/Intro-to-NLP/blob/master/1.%20Word%20embeddings/images/3.png)
![4](https://github.com/jayeshk7/Intro-to-NLP/blob/master/1.%20Word%20embeddings/images/4.png)

### Resources
Lectures : Stanford CS224n [Lecture 1 and 2](https://www.youtube.com/playlist?list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z)

Some important papers include :
1. [Original Word2Vec paper](https://arxiv.org/pdf/1301.3781.pdf)
2. [Negative Sampling paper](http://papers.nips.cc/paper/5021-distributed-representations-of-words-and-phrases-and-their-compositionality.pdf)
3. [GloVe](https://nlp.stanford.edu/pubs/glove.pdf)

