# Public Perception on Climate Change — Analyzing Twitter Discourse on Climate Change in the Epoch of Extreme Weather
## Project information
- **Author**: Ni Zheng, Computation and Design/Social Policy, Class of 2026, Duke Kunshan University
- **Instructor**: Prof. Luyao Zhang, Duke Kunshan University
- **Disclaimer**: Submissions to the Final Project for [STATS201 Introduction to Machine Learning for Social Science, 2023 Autumn Term (Seven Week - Second)](https://ms.pubpub.org/) instructed by Prof. Luyao Zhang at Duke Kunshan University.
- **Acknowledgments**: Thanks Prof.Luyao for her guidance and enriching instruction in STATS201. Thanks my peers for creating a collaborative environment that enhanced my learning experience.
- **Project Summary**:
  - **Summarize the Background/Motivation**

    In recent years, climate change has been a focal point of intense debate, sparking widespread discussions on various platforms, particularly on the internet. This heightened discourse is mirrored by the escalating pace of climate change and the frequent occurrences of natural disasters. As society grapples with the increasing impact of climate-related incidents, public perceptions and discussions on climate change have undergone notable shifts (“Natural Disaster Data Book 2022 (an Analytical Overview) - World | ReliefWeb” 2023). This research aims to navigate this evolving landscape by closely examining Twitter discussions during a crucial period in 2022. The focus is on capturing the changing dynamics and correlations between public sentiments and climatic events, contributing to a deeper understanding of the ongoing discourse surrounding climate change.
  - **Research Questions**
  
    1. **What are the most prevalent topics in climate change discussions on Twitter, and how do the dynamic shifts over time reflect  public perception towards climate change during the first half of 2022?**
    2. **What is the correlation between the frequency of tweets and the occurrence of natural disasters during the first half of 2022?**
    3. **How do different user stances contribute to climate change discussions on Twitter?**

  - **Application Scenario (Data Source)**
  
    The research relies on a [Kaggle-sourced dataset](https://www.kaggle.com/datasets/die9origephit/climate-change-tweets), covering daily Twitter discussions on 'Climate Change' from January 1, 2022, to July 19, 2022. This dataset, chosen during a year marked by unprecedented global extreme weather events, offers a unique insight into public sentiment during impactful climatic occurrences. Leveraging machine learning, specifically OpenAI's GPT-3.5 for sentiment analysis and BERTopic for topic modeling, the study aims to explore the correlation between climate discourse, extreme weather events, and environmental policy releases. The extensive timeframe allows for iterative exploration, providing refined insights into the evolving dynamics of public perception concerning climate change on Twitter amid the climate crisis.
  
  - **Methodology**

    The methodology is designed to address three research questions, focusing on prevalent topics, the correlation between tweet frequency and natural disasters, and the impact of different user stances on climate change discussions on Twitter. The significance lies in providing insights for policymakers, researchers, and the public regarding the intricate relationship between real-world events, environmental policies, and social media discourse (Hamed et al., 2015).

    Operational measures include defining variables (dependent: tweet frequency, independent: extreme weather events, environmental policy), with time-series data collected from top daily tweets with the 'Climate Change' hashtag in the first half of 2022. The hypothesis anticipates a positive correlation based on recent findings. Machine learning involves GPT-3.5 for sentiment analysis, BERTopic for topic modeling, and linear regression for analyzing relationships.

    The workflow includes dataset collection, tweet classification, topic modeling, sentiment analysis, and linear regression. Results presentation involves cross-validation, data visualization of clusters and trends, comparative analysis with representative accounts, and model evaluation using precision and F1 score. Iterative improvement strategies include feedback and bias mitigation for GPT-3.5 and cross-validation for BERTopic. This concise methodology aims to comprehensively explore climate change discussions on Twitter.

  - **Results**
    
    - **Most Prevalent topics in climate change discussions on Twitter**
    
      The analysis of Twitter data revealed the most prevalent topics in climate change discussions during the first half of 2022. Notable themes included discussions about climate-related issues within the political landscape of Australia, the intersection of climate change and agriculture, and general discourse about climate change. Topics also delved into the automotive industry's role in climate change mitigation, emissions in the context of government actions, and discussions extending beyond climate change to include political processes. The temporal evolution of these topics demonstrated a nuanced reflection of public sentiment, adapting to real-world events and developments.
  
    - **Correlation between tweet frequency and natural disasters**
      
      Examining the correlation between tweet frequency and natural disasters, the analysis focused on the dominance of Australia-related discussions on Twitter from March to June 2022 (CDP 2022). With a significant portion of tweets mentioning Australia and a notable presence from Australian institutes, the data supported the hypothesis that there is a correlation between the frequency of tweets and the occurrence of natural disasters. The substantial online discussion sparked by these events, including news reports, discussions about post-disaster recovery, and calls for government action, underscored the heightened engagement on Twitter during this period.

    -  **User stances in climate change discussions on Twitter**

       The exploration of user stances in climate change discussions on Twitter revealed a diverse spectrum of viewpoints. Approximately 47% of users maintained neutrality, 28% expressed skepticism, and 25% advocated for climate change. This dynamic distribution emphasized the ongoing debate in climate change discourse and highlighted the importance of education and advocacy efforts to shape public opinion. Sentiment analysis further provided a nuanced understanding of user sentiments within each tweet, contributing to the classification of stances based on sentiment analysis.

## Table of Contents
- [Literature](https://github.com/Rising-Stars-by-Sunshine/STATS201-Final-project-Jenny/tree/main/Literature)
- [Method](https://github.com/Rising-Stars-by-Sunshine/STATS201-Final-project-Jenny/tree/ea4406d612ac986a8529266ebb671c5a864fa9d0/Method)
- [Data](https://github.com/Rising-Stars-by-Sunshine/STATS201-Final-project-Jenny/tree/ea4406d612ac986a8529266ebb671c5a864fa9d0/Data)
- [Code](https://github.com/Rising-Stars-by-Sunshine/STATS201-Final-project-Jenny/tree/ea4406d612ac986a8529266ebb671c5a864fa9d0/Code)
- [Result](https://github.com/Rising-Stars-by-Sunshine/STATS201-Final-project-Jenny/tree/a3fe2d8daca1576e95440ddf6d17a9ff5104fc42/Results)
- Spotlight
- More about the author
- References

## Spotlight
- **[Poster](https://www.canva.com/design/DAF1hUBwwuM/WJmKBJOVM69UGGlLisD07g/edit?utm_content=DAF1hUBwwuM&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)**

<img width="397" alt="image" src="https://github.com/Rising-Stars-by-Sunshine/STATS201-Final-project-Jenny/assets/125801773/5a08d9c4-77cd-42dd-a84b-bc045eb375e1">

- **Figures and visualizations**

<img width="842" alt="image" src="https://github.com/Rising-Stars-by-Sunshine/STATS201-Final-project-Jenny/assets/125801773/95d635e4-e356-4171-b2f9-456f9f99efba">

*Figure1. Most populaer topics related to #climatechange*

<img width="787" alt="image" src="https://github.com/Rising-Stars-by-Sunshine/STATS201-Final-project-Jenny/assets/125801773/bc31e4ee-6e6f-40b0-9d56-4291ccc561cb">

*Figure2. Topics over time during the first half of 2022*

<img width="680" alt="image" src="https://github.com/Rising-Stars-by-Sunshine/STATS201-Final-project-Jenny/assets/125801773/81df5563-eb24-4181-a718-07852969551f">

*Figure3. Similarity matrix for popular topics*

<img width="475" alt="image" src="https://github.com/Rising-Stars-by-Sunshine/STATS201-Final-project-Jenny/assets/125801773/37b7482d-bb62-49cf-b112-49528dbcbd29">

*Figure4. Stance classification based on sentiment analysis*

## More about the Author
- **Headshot**

![_DSC2255](https://github.com/jennycheng1112/STATS201_Autumn2023_Week2_Sunshine.github.io/assets/125801773/4fdcc3d1-f6d7-4e94-868f-93e2578698de)

- **Self-introduction**

  Hi I'm Jenny Zheng from Duke Kunshan University, Class of 2026.

  **Intended major:** Computation and Design with Social Policy track
  
  **Research projects focus:** quantitative social science and environmental science; analyzing public perceptions on societal problems.
  
  Besides, I am also interested in consulting and finance, where I'd like to apply my skills to business-world practice.
  
  **Other experiences**:
  - Bain & Company, Part-time assistant
    - PE fund, FMCG, Manufacturing
    - Strategy, Due diligence
  - GoodWe, Investment intern
    - industry research on renewable energy
  - Duke Kunshan University, Peer tutor
    - STATS101, Applied statistical methods

- **Final reflections**
  - **Intellectual Growth:**

    Gaining proficiency in machine learning has afforded me a more profound comprehension of its contemporary applications. In the realm of social science, employing machine learning and diverse packages to address societal issues has empowered me to explore and resolve these topics more thoroughly. Moreover, the classroom setting facilitated a better grasp of machine learning applications, as students could conduct research aligned with their individual interests. Consequently, the class structure and environment significantly facilitated my in-depth exploration of the practical applications of machine learning.

  - **Interdisciplinary Growth:**
  
    In taking this course and learning peer's research directions, I was able to observe how interdisciplinary collaboration truly unfolds in research. Specifically, as a computation and design major, most of my research stems from design thinking. However, adding a research topic concerning finance, data science and linguistic perspective of the impact and features of language impairment allowed me to further broaden my knowledge. Furthermore, witnessing the different approaches that students from various majors take in conducting this research was intriguing. It was interesting to see the diversity of approaches.

  - **Professional growth:**

    Gaining a general understanding of machine learning has significantly contributed to my professional growth, enabling me to engage in discussions with a diverse range of designers and artists. Particularly, in light of the prevailing trend where many designers utilize machine learning as a tool to enhance their work, I view my decision to advance my professional growth in this direction as a meaningful step forward.

  - **Living a purposeful life:**

    In the future, I aspire to solve real-world problems with my data science skills and industry knowledge. With a focus on addressing global issues and societal problems like climate change, I aim to establish myself as a prominent advocate for applying data science to real-world issues. In essence, my overarching goal is to contribute to the design and implementation of innovative solutions that promote sustainability, and positive societal impact. I envision a future where my work not only enhances learning processes but also inspires fellow data scientists and designers to create solutions that prioritize care and support for our world.

## References

### Data Source
- Title: Climate Change Tweets
- URL: https://www.kaggle.com/datasets/die9origephit/climate-change-tweets

### Code Source
- Title: Easiest way to download kaggle data in Google Colab
- URL: https://www.kaggle.com/discussions/general/74235
  
- Title: Text-Analysis-with-OpenAI-GPT-3.5
- URL: https://github.com/ddtdanilo/Text-Analysis-with-OpenAI-GPT-3.5

### Articles & Literature
- Literature References in Chicago style

Chen, Xingyu, Lei Zou, and Bo Zhao. 2019. “Detecting Climate Change Deniers on Twitter Using a Deep Neural Network.” Proceedings of the 2019 11th International Conference on Machine Learning and Computing - ICMLC ’19. https://doi.org/10.1145/3318299.3318382. ‌ ‌Hamed, Ahmed Abdeen, Alexa A. Ayer, Eric M. Clark, Erin A. Irons, Grant T. Taylor, and Asim Zia. 2015. “Measuring Climate Change on Twitter Using Google’s Algorithm: Perception and Events.” International Journal of Web Information Systems 11 (4): 527–44. https://doi.org/10.1108/ijwis-08-2015-0025.

Kryvasheyeu, Yury, Haohui Chen, Nick Obradovich, Esteban Moro, Pascal Van Hentenryck, James Fowler, and Manuel Cebrian. 2016. “Rapid Assessment of Disaster Damage Using Social Media Activity.” Science Advances 2 (3): e1500779. https://doi.org/10.1126/sciadv.1500779.

Kirilenko, Andrei P., and Svetlana O. Stepchenkova. 2014. “Public Microblogging on Climate Change: One Year of Twitter Worldwide.” Global Environmental Change 26 (May): 171–82. https://doi.org/10.1016/j.gloenvcha.2014.02.008.

Kirilenko, Andrei P., Tatiana Molodtsova, and Svetlana O. Stepchenkova. 2015. “People as Sensors: Mass Media and Local Temperature Influence Climate Change Discussion on Twitter.” Global Environmental Change 30 (January): 92–100. https://doi.org/10.1016/j.gloenvcha.2014.11.003.

Veltri, Giuseppe A., and Dimitrinka Atanasova. 2015. “Climate Change on Twitter: Content, Media Ecology and Information Sharing Behaviour.” Public Understanding of Science 26 (6): 721–37. https://doi.org/10.1177/0963662515613702.

“Natural Disaster Data Book 2022 (an Analytical Overview) - World | ReliefWeb.” 2023. Reliefweb.int. October 12, 2023. https://reliefweb.int/report/world/natural-disaster-data-book-2022-analytical-overview.

CDP. 2022. “2022 Australian Flooding.” Center for Disaster Philanthropy. April 19, 2022. https://disasterphilanthropy.org/disasters/2022-australian-flooding/.


- Literature References in Bibtex

```
@article{chen2019detecting,
  title={Detecting Climate Change Deniers on Twitter Using a Deep Neural Network},
  author={Chen, Xingyu and Zou, Lei and Zhao, Bo},
  booktitle={Proceedings of the 2019 11th International Conference on Machine Learning and Computing - ICMLC ’19},
  year={2019},
  doi={10.1145/3318299.3318382},
  url={https://doi.org/10.1145/3318299.3318382}
}

@article{hamed2015measuring,
  title={Measuring Climate Change on Twitter Using Google’s Algorithm: Perception and Events},
  author={Hamed, Ahmed Abdeen and Ayer, Alexa A. and Clark, Eric M. and Irons, Erin A. and Taylor, Grant T. and Zia, Asim},
  journal={International Journal of Web Information Systems},
  volume={11},
  number={4},
  pages={527--544},
  year={2015},
  doi={10.1108/ijwis-08-2015-0025},
  url={https://doi.org/10.1108/ijwis-08-2015-0025}
}

@article{kryvasheyeu2016rapid,
  title={Rapid Assessment of Disaster Damage Using Social Media Activity},
  author={Kryvasheyeu, Yury and Chen, Haohui and Obradovich, Nick and Moro, Esteban and Van Hentenryck, Pascal and Fowler, James and Cebrian, Manuel},
  journal={Science Advances},
  volume={2},
  number={3},
  pages={e1500779},
  year={2016},
  doi={10.1126/sciadv.1500779},
  url={https://doi.org/10.1126/sciadv.1500779}
}

@article{kirilenko2014public,
  title={Public Microblogging on Climate Change: One Year of Twitter Worldwide},
  author={Kirilenko, Andrei P. and Stepchenkova, Svetlana O.},
  journal={Global Environmental Change},
  volume={26},
  month={May},
  pages={171--182},
  year={2014},
  doi={10.1016/j.gloenvcha.2014.02.008},
  url={https://doi.org/10.1016/j.gloenvcha.2014.02.008}
}

@article{kirilenko2015people,
  title={People as Sensors: Mass Media and Local Temperature Influence Climate Change Discussion on Twitter},
  author={Kirilenko, Andrei P. and Molodtsova, Tatiana and Stepchenkova, Svetlana O.},
  journal={Global Environmental Change},
  volume={30},
  month={January},
  pages={92--100},
  year={2015},
  doi={10.1016/j.gloenvcha.2014.11.003},
  url={https://doi.org/10.1016/j.gloenvcha.2014.11.003}
}

@article{veltri2015climate,
  title={Climate Change on Twitter: Content, Media Ecology and Information Sharing Behaviour},
  author={Veltri, Giuseppe A. and Atanasova, Dimitrinka},
  journal={Public Understanding of Science},
  volume={26},
  number={6},
  pages={721--737},
  year={2015},
  doi={10.1177/0963662515613702},
  url={https://doi.org/10.1177/0963662515613702}
}

@book{reliefweb2023,
  title = {Natural Disaster Data Book 2022 (an Analytical Overview) - World},
  author = {{ReliefWeb}},
  year = {2023},
  note = {ReliefWeb, October 12, 2023},
  url = {https://reliefweb.int/report/world/natural-disaster-data-book-2022-analytical-overview}
}

@online{cdp2022,
  title = {2022 Australian Flooding},
  author = {{CDP}},
  year = {2022},
  url = {https://disasterphilanthropy.org/disasters/2022-australian-flooding/},
  note = {Center for Disaster Philanthropy, April 19, 2022}
}

```
