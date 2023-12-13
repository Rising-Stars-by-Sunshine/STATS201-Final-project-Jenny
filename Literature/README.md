# Literature
**Title: Detecting Climate Change Deniers on Twitter Using a Deep Neural Network**

*1. Background/Motivation:*
This study addresses the challenge of automatically assessing attitudes towards climate change using social media content. As debates on climate change intensify, understanding public sentiments becomes imperative. Traditional survey methods possess limitations concerning time, expenses, and biases associated with participants. Utilizing social media enables real-time responses, bypassing predefined survey questions. However, interpreting and categorizing human expressions on these platforms remains arduous.

*2. Research Questions:*
1. How can a Deep Neural Network (DNN) be optimized to distinguish climate change deniers from believers based on their Twitter posts?
2. What are the temporal patterns in climate change discussions on Twitter during the year 2016?
3. How do extreme weather events and policy changes influence the volume and nature of climate change discussions on social media platforms?

*3. Application Scenarios:*
The study utilized a DNN classifier to discern 'denier' or 'non-denier' tweets, shedding light on public opinions about climate change. The findings demonstrated that the DNN model achieved an 88% overall accuracy in identifying climate change deniers based on tweet content. Additionally, it highlighted increased climate change discussions from September to December 2016, influenced by extreme weather events and environmental policy changes.

*4. Methodology:*
Twitter data, obtained from Internet Archive using climate change-related keywords, underwent translation, manual labeling, and the continuous bag-of-words (CBOW) model. The methodology involved converting tweets into vectors and training a DNN model to distinguish between climate change deniers and non-deniers.

<img width="439" alt="image" src="https://github.com/Rising-Stars-by-Sunshine/STATS201_JennyZheng/assets/125801773/fa5e87da-c39b-44e1-92a9-0e17d5da6519">
<img width="349" alt="image" src="https://github.com/Rising-Stars-by-Sunshine/STATS201_JennyZheng/assets/125801773/fdf3cbef-5d5f-446c-9227-cffde6e16810">

*5. Results:*
The developed DNN model effectively identified climate change deniers and revealed heightened discussions linked to environmental policy shifts and extreme weather events. These insights were derived from data collected, processed, and analyzed using translation, model-based analyses, and manual labeling.

<img width="361" alt="image" src="https://github.com/Rising-Stars-by-Sunshine/STATS201_JennyZheng/assets/125801773/0a8703ec-dd95-4b7f-b6e8-2858b8ac07bf">
<img width="392" alt="image" src="https://github.com/Rising-Stars-by-Sunshine/STATS201_JennyZheng/assets/125801773/84d10ec0-89af-4fed-b6e0-3a2c28d3cb13">

*6. Intellectual Merits/Practical Impacts:*
This approach not only showcased the efficiency of DNNs in classifying climate change attitudes but also emphasized the significance of social media in assessing public opinion. The study contributes to the application of deep learning algorithms in natural language processing, providing enhanced understanding of the factors influencing public attitudes towards climate change.

**Mindmap created by Whimscal**

<img width="708" alt="image" src="https://github.com/Rising-Stars-by-Sunshine/STATS201_JennyZheng/assets/125801773/1d008706-db45-4354-a10e-d7ac1df4061b">


**Title: Measuring climate change on Twitter using Google’s algorithm: perception and events**

*1. Background/Motivation:*
This paper addresses the imperative of gauging public awareness of climate change through Twitter, emphasizing the significance of hashtags as indicators. Focusing on the objectivity of computational approaches, the study aims to detect and rank emerging events related to climate change, mitigating subjectivity inherent in human interpretation.

*2. Research Questions:*
- *What role do intricate and emergent hashtags play in signaling climate change events on Twitter?*
- *How effective are computational approaches, such as Google's ranking algorithm and TFIDF, in detecting and ranking emerging climate change events expressed through hashtags?*

*3. Application Scenarios:*
The study applies computational methods, including Google's ranking algorithm and TFIDF, to discern and rank emerging climate change events on Twitter. Beyond climate change, the scenario envisions broader applications for objective computational approaches in event detection across diverse social media platforms.

*4. Methodology:*
The methodology utilizes objective computational approaches, such as Google's ranking algorithm and TFIDF, for detecting and ranking emerging climate change events. Web mining techniques and web design metrics contribute to uncovering prevalent themes and sentiments within the climate change discourse, eliminating subjectivity errors associated with human interpretation.

*5. Results:*
Findings reveal explicit evidence supporting the efficacy of emergent hashtags in signaling climate change events. The study successfully detects globally influential events, like Earth Day 2015, through hashtags like #EarthDay. The computational methods employed offer an objective and cost-effective solution, with potential applications extending beyond climate change events.

<img width="687" alt="image" src="https://github.com/Rising-Stars-by-Sunshine/STATS201-Final-project-Jenny/assets/125801773/b666b5ae-41e9-4342-a468-972e32d5cd97">
<img width="677" alt="image" src="https://github.com/Rising-Stars-by-Sunshine/STATS201-Final-project-Jenny/assets/125801773/50482a6c-549c-421b-8ac4-221b0d0686d4">

*6. Intellectual Merits/Practical Impacts:*
The intellectual merits lie in advancing the understanding of computational methods for climate change event detection on Twitter. The study contributes by eradicating subjectivity errors, providing a cost-effective solution, and offering insights into global awareness and influential events. Practical impacts extend to the applicability of the approach to other event detections and across various social media platforms.

**Mindmap created by Whimscal**

<img width="678" alt="image" src="https://github.com/Rising-Stars-by-Sunshine/STATS201-Final-project-Jenny/assets/125801773/1dd021f5-c76f-40f3-9a60-d03348ce1fd0">


# How my research connects and advances existing studies

My research builds upon existing literature by integrating advanced machine learning techniques, refining temporal analyses, incorporating stance classification and sentiment analysis, eliminating subjectivity errors, and introducing a robust model evaluation process. These advancements contribute to a more nuanced and comprehensive understanding of climate change discussions on Twitter, offering valuable insights for both researchers and policymakers.

Here's how my research connects to and enhances previous works:

**1. Integration of machine learning algorithms:**
   - **Connection:** Existing research, such as Chen, Zou, and Zhao (2019), has explored the use of Deep Neural Networks (DNN) to detect climate change deniers on Twitter.
   - **Advancement:** My research extends this by not only utilizing machine learning, specifically OpenAI's GPT-3.5 for sentiment analysis and BERTopic for topic modeling, but also incorporating linear regression analysis to investigate correlations between sentiments, environmental policies, and public perceptions. This multi-faceted approach provides a more comprehensive understanding of the dynamics within climate change discussions.

**2. Temporal analysis and specific time frame:**
   - **Connection:** The study on measuring climate change on Twitter using Google’s algorithm (Hamed et al., 2015) addressed the importance of temporal patterns in climate change discussions.
   - **Advancement:** My research further refines the temporal analysis by focusing on a specific time frame, the first half of 2022, marked by notable climate events. This temporal specificity enhances the precision of My analysis, capturing the immediate impact of incidents on public discourse.

**3. Incorporation of stance classification and sentiment analysis:**
   - **Connection:** Kirilenko et al. (2015) studied the linkage of local temperature effects on Twitter's awareness, recognizing complex terms in climate discussions.
   - **Advancement:** My research surpasses this by incorporating stance classification (believers, neutrals, deniers) and sentiment analysis using GPT-3.5. This not only refines the classification process but also provides nuanced insights into emotional inclinations and attitudes expressed in tweets.

**4. Thematic clusters and elimination of subjectivity errors:**
   - **Connection:** The study using Google’s algorithm (Hamed et al., 2015) focused on objective computational approaches for climate change event detection.
   - **Advancement:** My research employs BERTopic to identify thematic clusters, offering a more sophisticated understanding of prevalent topics. This goes beyond mere event detection, eliminating subjectivity errors and providing a nuanced exploration of the evolving themes within climate change discourse.

**5. Model evaluation and comparison with representative accounts:**
   - **Connection:** Chen, Zou, and Zhao (2019) utilized a DNN classifier for discerning 'denier' or 'non-denier' tweets.
   - **Advancement:** My research introduces an extensive model evaluation process, including precision, recall, F1 score, and a comparison with tweets from representative accounts embodying different stances. This enhances the reliability of My model's outputs by validating them against real-world perspectives.
   
<img width="865" alt="image" src="https://github.com/Rising-Stars-by-Sunshine/STATS201-Final-project-Jenny/assets/125801773/bf4bd755-4f16-4b1f-a946-52e1357dbe9a">


# References:
Chen, Xingyu, Lei Zou, and Bo Zhao. 2019. “Detecting Climate Change Deniers on Twitter Using a Deep Neural Network.” Proceedings of the 2019 11th International Conference on Machine Learning and Computing - ICMLC ’19. https://doi.org/10.1145/3318299.3318382.
‌
‌Hamed, Ahmed Abdeen, Alexa A. Ayer, Eric M. Clark, Erin A. Irons, Grant T. Taylor, and Asim Zia. 2015. “Measuring Climate Change on Twitter Using Google’s Algorithm: Perception and Events.” International Journal of Web Information Systems 11 (4): 527–44. https://doi.org/10.1108/ijwis-08-2015-0025.

Kryvasheyeu, Yury, Haohui Chen, Nick Obradovich, Esteban Moro, Pascal Van Hentenryck, James Fowler, and Manuel Cebrian. 2016. “Rapid Assessment of Disaster Damage Using Social Media Activity.” Science Advances 2 (3): e1500779. https://doi.org/10.1126/sciadv.1500779.

Kirilenko, Andrei P., and Svetlana O. Stepchenkova. 2014. “Public Microblogging on Climate Change: One Year of Twitter Worldwide.” Global Environmental Change 26 (May): 171–82. https://doi.org/10.1016/j.gloenvcha.2014.02.008.

Kirilenko, Andrei P., Tatiana Molodtsova, and Svetlana O. Stepchenkova. 2015. “People as Sensors: Mass Media and Local Temperature Influence Climate Change Discussion on Twitter.” Global Environmental Change 30 (January): 92–100. https://doi.org/10.1016/j.gloenvcha.2014.11.003.

Veltri, Giuseppe A., and Dimitrinka Atanasova. 2015. “Climate Change on Twitter: Content, Media Ecology and Information Sharing Behaviour.” Public Understanding of Science 26 (6): 721–37. https://doi.org/10.1177/0963662515613702.
