# Research Objective 
To conduct a comprehensive analysis encompassing sentiment analysis, social network analysis, and web analytics on 812 tweets related to Ubisoft, focusing on key web metrics comparison, sentiment categorization, and social network visualization. Additionally, to evaluate the effectiveness of Ubisoft's SEO strategies, interactivity features, and mobile optimization compared to a competitor, aiming to provide insights into user engagement and perceptions across different online platforms. 

# Research Question 
How do sentiment analysis, social network analysis, and web analytics metrics contribute to understanding the online presence and engagement of Ubisoft on Twitter, and what insights can be derived from the analysis of 812 tweets related to Ubisoft?


## Diagram 1: Comparison of Sentiment Analysis Results Between Azure and Textblob 

<img width="452" alt="image" src="https://github.com/user-attachments/assets/3fe75976-f21c-4350-b9c6-b7fec4f139c6">

In terms of positive sentiment, Azure classifies a substantial 81.48% of the tweets as positive, in contrast to Textblob's 62.00%. This suggests that Azure might tend to overestimate positive sentiment or interpret a broader range of tweets as positive compared to Textblob. To determine which method is more accurate for sentiment analysis, we must consider the context and the coverage of the lexicons used by both methods. The accuracy of these models was initially calculated based on the presence of words in the respective lexicons. Textblob's higher identification of neutral tweets suggests better handling of ambiguous or less emotionally charged content, potentially offering a more balanced sentiment analysis. Conversely, Azure's higher positive sentiment classification might indicate an overestimation of positive content or a different interpretation framework.

For negative sentiment, Azure classifies 7.41% of the tweets as negative, while Textblob identifies a slightly higher proportion at 9.66%. This minor discrepancy suggests that Textblob is slightly more sensitive in detecting negative sentiments. The most notable difference between the two methods is in the classification of neutral sentiments. Azure identifies 11.11% of the tweets as neutral, whereas Textblob classifies a significantly higher percentage at 28.34%. This considerable disparity indicates that Textblob has a more nuanced approach to identifying tweets that do not express strong positive or negative sentiments, potentially providing a more balanced sentiment analysis.

## Diagram 2: Word Cloud of Vader for Ubisoft Company Tweets

<img width="452" alt="image" src="https://github.com/user-attachments/assets/d462fcd8-4aa0-469c-9344-02f9881fbd6b">

The word cloud generated from the Vader of Ubisoft-related tweets highlights key terms such as "game," "play," "new," "free," "available," and "Ubisoft," indicating a strong focus on gaming activities. Words like "coming," "watch," "team," "join," "live," and "update" suggest high engagement and anticipation for upcoming releases and events. Terms like "closed beta," "preorder," "discover," and "experience" emphasize interest in exclusive content and new adventures. Titles such as "Assassin's Creed," "Mirage," "Avatar," and "Frontiers" generate significant buzz, reflecting an excited gaming community eagerly discussing new games and updates.

## Diagram 3: Network Overview

<img width="290" alt="image" src="https://github.com/user-attachments/assets/1985a90f-4b32-458e-83d4-32ad7566a453">

The network reveals a directed graph comprising 692 vertices and 812 edges, with 668 unique edges and 144 duplicated edges, indicating repeated interactions between certain nodes. Notably, there are no self-loops, suggesting that nodes do not interact with themselves. The network is characterized by two connected components, with the largest component encompassing 487 vertices and 486 edges. The network’s maximum geodesic distance, or diameter, is 4, while the average geodesic distance is 2.217, indicating the nodes are relatively close to each other on average.

## Diagram 4: Top 5 Vertex for Out-Degree

<img width="452" alt="image" src="https://github.com/user-attachments/assets/6f7f9864-dcb1-417c-a85f-11b576150d9d">

The top 5 vertices with the highest out-degree. @Ubisoft has the highest out-degree in the network at 486, indicating it interacts with 486 nodes. It also has the highest betweenness centrality at 235,710, playing a crucial role as a connector. @Ubisoft's closeness centrality is 0.002, suggesting it is relatively close to other nodes. With a high PageRank score of 223.838, @Ubisoft is highly influential, though its neighbors are not necessarily influential. The absence of clustering coefficient and reciprocated vertex pair ratio values (both 0) indicates @Ubisoft does not engage in mutual interactions with other nodes.

# Conclusion 

In conclusion, as the video game market continues to experience steady growth, it's imperative for Ubisoft to adapt and evolve its digital advertising strategy to capitalize on emerging opportunities. The comprehensive analysis of Ubisoft's online presence and engagement on Twitter through sentiment analysis, social network analysis, and web analytics metrics provides valuable insights into the dynamics of user interactions and perceptions surrounding the brand. The sentiment analysis reveals overwhelmingly positive feedback, indicating high levels of customer satisfaction and loyalty, with minimal negative sentiments. This positivity is reinforced by the social network analysis, which highlights Ubisoft's central role within the network and its influence in disseminating information. The identification of key influencers and communities further underscores the brand's strong online presence and engagement strategies. By leveraging these insights, Ubisoft can continue to enhance its online reputation, address areas of neutrality, and foster deeper connections with its audience, ultimately strengthening its position as a leading game developer and publisher in the gaming industry.


