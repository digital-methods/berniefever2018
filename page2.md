# Analysis 

### Figure 1: Epoch Bump Graph of Post Topics

![figure_1](https://user-images.githubusercontent.com/38719684/39634923-53e9bf08-4fbc-11e8-9c9a-70de436e7414.png)

This shows a temporal evolution of the topics of Bernie’s posts. We can see that socio economic justice, corporate welfare, trump administration, and healthcare were the dominant ones with some movement in terms of ranking among the top ones, but no drastic ones overall

### Figure 2: Network Modeling with aggregated sentiment score as tags

![figure_2](https://user-images.githubusercontent.com/38719684/39635063-b13a8fc0-4fbc-11e8-9b52-a234b72dee98.png)

The above figure provides us with a visualization of the connection between different topics in Bernie’s posts in clusters complimented by the average aggregated score of the sentiment analysis on the comments of the cluster. This network map (Figure 2) shows three main clusters of topics, meaning that one post could contain multiple topics that are within the same cluster or that share a node. For example some posts that are about minimum wage also mention socioeconomic justice or health care. The Yellow and blue clusters are connected whereas the green cluster is isolated. 

The results demonstrate that posts about topics in the blue cluster (immigration, events, and healthcare) and the green cluster (education, gun control,..etc) have an aggregated highly positive score of 8 to 10. This means that these posts generally generate comments with a positive sentiment such as agreement and praise. While topics in the yellow cluster such as the trump administration, socioeconomic justice, and the supreme court have comments with a highly negative sentiment score (-10 to -5). We believe that some negative comments are not necessarily about the topic itself or a criticism of the post’s content, but negative statements about Bernie himself such as “ Berinie where is your humanity? You are cruel.”

### Figure 3: Heat Map with sentiment score as third variable

![figure_3](https://user-images.githubusercontent.com/38719684/39635272-4ee339fc-4fbd-11e8-8a2d-74447d3e1ed3.png)

Figure 3 is a heat map showing the network mapping of the various topics contained in the posts, correlated by the average sentiment score that are conveyed in the comments.  Red is a more positive sentiment score with bright red being a score of 10. Blue is negative sentiment score, the darker it is the more negative the score is. White is a neutral sentiment score. Posts about immigration appear to elicit very positive comments. A closer look at the data, however, shows that immigration posts were very close in time suggesting that it was about a specific event which might explain why it has received a very positive score (Figure 4):

### Figure 4: Field Evolution of Immigration

![figure_4](https://user-images.githubusercontent.com/38719684/39635367-9722d8d0-4fbd-11e8-80fc-5fccc41d0b4c.png)

The corpus explorer on a subquery of all ‘immigration’ posts revealed that all those comments belonged in fact to three posts only. Nothing can thus be said about a sentiment trend on immigration posts:

![figure_4_2](https://user-images.githubusercontent.com/38719684/39635615-4a41743a-4fbe-11e8-8af0-c9b1d0f383fe.png)

![figure_4_3](https://user-images.githubusercontent.com/38719684/39635616-4a82095a-4fbe-11e8-9810-35ecf0dd88b6.png)

![figure_4_4](https://user-images.githubusercontent.com/38719684/39635617-4acbbe6a-4fbe-11e8-8465-98d224b12680.png)

### Figure 5: Network Maps

![figure_5](https://user-images.githubusercontent.com/38719684/39635837-e3d76492-4fbe-11e8-89e8-58754acd85f7.png)

### Figure 6: Contingency Matrix: Post Topics and Comment Sentiment Scores

![figure_6_1](https://user-images.githubusercontent.com/38719684/39636043-5c087816-4fbf-11e8-85b0-6e35c4808a8f.png)

The contingency matrix above (figure 1) visualizes a joint distribution of our two variables: the topics addressed in Bernie’s posts on the X-axis and the sentiment score of the comments on the Y-axis. The colors demonstrate the degree of correlation between the two variables with red being the most correlated, blue anti-correlated, and white do not feature any correlation. 

Finally, the size of the cells both horizontally and vertically represent the portion of that category in the overall sample size. For the Y-axis, which contains the sentiment score, the length of the cell is proportional to the number of comments that belong to each category. In this case -1 to 1 is longest because a large part of the comments (for all of the posts) have that score (~ 50%)

![figure_6_2](https://user-images.githubusercontent.com/38719684/39636044-5c3cbdba-4fbf-11e8-9260-3424b9e31554.png)

The results of the contingency matrix demonstrate that there is a high correlation between the posts about the Trump administration and comments with a highly negative score (-10 to -5). There is also a strong correlation between posts on minimum wage and comments with a decent positive score (2 to 4) and immigration (and events) and comments with a highly positive sentiment score (8 to 10).

To have a closer look at the strong correlation results between ‘trump administration’ and the very negative sentiment range -10_-5 and ‘minimum wage’ and the positive sentiment range of 2_4, we created field evolution graphs isolating the ‘opinionated’ comments:

### Figure 7: Field Evolution of Opinionated Comments - Subcorpus ‘Trump Administration’

![figure_7](https://user-images.githubusercontent.com/38719684/39636237-ee4b202a-4fbf-11e8-9984-47836b776746.png)

Though we can indeed see that negative comments mostly dominated throughout, we again see that there are event specific bumps that heavily influence the results. Without those, comments are not really as negative as the contingency matrix may suggest. The same holds true for the topic minimum wage:

### Figure 8: Field Evolution of Opinionated Comments - Subcorpus ‘Minimum Wage’

![picture_8](https://user-images.githubusercontent.com/38719684/39636239-eebe5464-4fbf-11e8-8bab-9bbb8c31e34a.png)
