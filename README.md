# Master's thesis Peter Kolbeinsen Klingenberg

Title: Using content- and behavioural data for recommendations in the Norwegian news market

University: University of Bergen (UiB), Department of Information Science and Media Studies

Collaborators: MediaFutures and Bergens Tidende/Schibsted

Supervisors: Assoc. Prof. Df. Mehdi Elahi (UiB/MediaFutures) and Thomas Husken (BT)


## Abstact
In the news domain, the technological development has contributed to always accessible 
platforms with frequent publishment of articles. This contributes to a vast amount of 
articles, leading to a multitude of choices. Interactions executed by users (clicks, views or ratings) 
and content of articles (text, section, etc.) on such platforms can be utilized to create personalised 
recommendations. However, there can arise a situation where there is a lack of data, i.e., 
when a new article is published or there is a new user, known as the Cold Start Problem. In addition, 
personalised recommendations in the news industry, where user behaviour are the basis of recommendations, are more
complex in comparison with, for example, the movie domain due to the timeliness with
short duration and relevance of articles. Recommendations provided by content data
may mitigate this issue.

This thesis investigates the viability of using both content- and user-behavioural data
to generate recommendations in the Norwegian media market in collaboration with
one of Norway’s largest newspapers, i.e., Bergens Tidende (BT). The first technique
investigated is collaborative-based filtering, built on the recommender models Alternating Least Squares, 
Bayesian Personalized Ranking and Logistic Matrix Factorization, which is specially tailored to use 
user behavioural data as input. The second technique investigated is content-based filtering, 
built on a state-of-the-art architecture named BERT, specially trained to draw the semantic content of sentences 
in the Norwegian language. A comprehensive offline evaluation of both techniques is executed using a diverse 
selection of accuracy metrics. In addition, an online evaluation of a large-scale A/B test of the content-based filtering 
technique against a former recommendation technique in BT. The evaluation methods used in the online experiment are
descriptive data- and Bayesian analysis.

The results of the collaborative-based filtering technique have shown increased performance in different stages of filtering, 
in addition to the importance of hyperparameter optimization. Based on the content-based filtering technique, 
the results have shown promising performance, indicating that this attracts users’ interest at a greater scale, 
even the groups that usually show less amount of interaction.


## Thesis code
The folders ExperimentA, ExperimentB and ExperimentC contains the code used in this thesis, with datasets and some 
concepts of Bergens Tidende missing.

