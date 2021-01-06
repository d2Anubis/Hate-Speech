# HATE SPEECH ON BILLBOARD HOT 100 SONGS

It has been scientifically proven that music has very powerful on brain. Over the years the music industry has gone through a massive change in it’s lyrics writing. According to an article on medium by performing sentiment analysis on Billboard Hot 100 songs it was found on average music lyrics gets 1.3% negative every year. Also we find many toxic songs makes it upto the most streaming songs. In this project, we try to see the trends of hate speech over the years using the BERT model. The OLID dataset is used to fine-tune the model and then transfer learning has been performed by testing it on songs. Since the testing dataset contains songs in different languages, zero-shot learning has been experimented. 


After training the song on OLID dataset the model performs well on the validation dataset by resulting in an accuracy score of 0.76. However the zero-shot learning does not go well after testing it on the ToLD-Br dataset for portuguese. The model shows a macro avg f1-score of 0.59. However for the similar datasets according to paper on toxic language detection the model gives a macro avg f1-score of 0.56 which is quite comparable results from ours. 


On analyzing the trends of hate speech on hit songs it has been found that over the years there has been a massive increase in use of hate speech in songs. On looking at the most frequently occurring words we can easily conclude that the model was able to identify the songs with bad lyrics.

