# Title [How to Choice a Good Title?](https://www.nature.com/articles/s41562-021-01152-2)
## Project information
- **Author**: Ni Zheng, Computation and Design/Social Policy, Class of 2026, Duke Kunshan University
- **Instructor**: Prof. Luyao Zhang, Duke Kunshan University
- **Disclaimer**: Submissions to the Final Project for [STATS201 Introduction to Machine Learning for Social Science, 2023 Autumn Term (Seven Week - Second)](https://ms.pubpub.org/) instructed by Prof. Luyao Zhang at Duke Kunshan University.
- **Acknowledgments**: Thanks Prof.Luyao for her guidance and enriching instruction in STATS201. Thanks my peers for creating a collaborative environment that enhanced my learning experience.
- **Project Summary**:
  - **Summarize the Background/Motivation**

  In recent years, climate change has been a focal point of intense debate, sparking widespread discussions on various platforms, particularly on the internet. This heightened discourse is mirrored by the escalating pace of climate change and the frequent occurrences of natural disasters. As society grapples with the increasing impact of climate-related incidents, public perceptions and discussions on climate change have undergone notable shifts. This research aims to navigate this evolving landscape by closely examining Twitter discussions during a crucial period in 2022. The focus is on capturing the changing dynamics and correlations between public sentiments and climatic events, contributing to a deeper understanding of the ongoing discourse surrounding climate change.
  - **Research Questions**
  
    1. **What are the most prevalent topics in climate change discussions on Twitter, and how do the dynamic shifts over time reflect  public perception towards climate change during the first half of 2022?**
    2. **What is the correlation between the frequency of tweets and the occurrence of natural disasters during the first half of 2022?**
    3. **How do different user stances contribute to climate change discussions on Twitter?**

  - **Application Scenario (Data Source)**
  
  The research relies on a Kaggle-sourced dataset, covering daily Twitter discussions on 'Climate Change' from January 1, 2022, to July 19, 2022. This dataset, chosen during a year marked by unprecedented global extreme weather events, offers a unique insight into public sentiment during impactful climatic occurrences. Leveraging machine learning, specifically OpenAI's GPT-3.5 for sentiment analysis and BERTopic for topic modeling, the study aims to explore the correlation between climate discourse, extreme weather events, and environmental policy releases. The extensive timeframe allows for iterative exploration, providing refined insights into the evolving dynamics of public perception concerning climate change on Twitter amid the climate crisis.
  
  - **Methodology**

    *1. Research Question Formulation*
    
    *1.1 Objective*
    - What are the most prevalent topics in climate change discussions on Twitter, and how do the dynamic shifts over time reflect public perception towards climate change during the first half of 2022?
    - What is the correlation between the frequency of tweets and the occurrence of natural disasters during the first half of 2022?
    - How do different user stances contribute to climate change discussions on Twitter?
    
    *1.2 Significance*
    
    Understanding the intricate relationship between real-world events, environmental policies, and public discourse on social media is paramount (*Chen, Zou, and Zhao, 2019*). This research contributes valuable insights for policymakers, researchers, and the broader public.
    
    *2. Operational Measures*
    
    *2.1 Variables*
    
    - *Dependent Variable (Y):* Public perception of climate change discussions on Twitter (measured by tweet frequency).
    - *Independent Variables (X):* The occurrence of extreme weather events, Release of environmental policy.
    
    *2.2 Data Type*
    
    Time-series data collected by filtering the top daily tweets based on the hashtag 'Climate Change' during the first half of 2022.
    
    *3. Hypothesis Development*
    
    *3.1 Prediction Hypothesis*
    
    Anticipates a positive correlation between the frequency of extreme weather events, significant environmental policy releases, and public perception of climate change discussions on Twitter.
    
    *3.2 Justification*
    
    Grounded in recent findings (*Chen, Zou, and Zhao 2019*), external events stimulate increased discussions about climate change on social media.
    
    *4. Machine Learning Algorithm Selection*
    
    *4.1 Sentiment Analysis*
    
    - *Algorithm:* OpenAI's GPT-3.5 model.
    - *Justification:* GPT-3.5's advanced natural language processing for nuanced sentiment classification.
    
    *4.2 Topic Modeling*
    
    - *Algorithm:* BERTopic.
    - *Justification:* Efficacy in uncovering thematic clusters within text data.
    
    *4.3 Linear Regression Analysis*
    
    - *Algorithm:* Linear Regression.
    - *Justification:* Suitable for exploring relationships between sentiments and public perceptions of climate change.
    
    *5. The Machine Learning Workflow*
    
    *5.1 Model Development*
    - Comprehensive dataset collection from Twitter (Jan-Jul 2022).
    - Tweet classification using OpenAI's GPT-3.5 model.
    - Topic modeling with BERTopic.
    - Sentiment analysis for discerning emotional inclinations.
    - Linear regression analysis to investigate the correlation between sentiments and public perceptions.
    
    *5.2 Results Presentation*
    
    - Training and Testing through cross-validation.
    - Data Visualization of thematic clusters, sentiment trends, and linear regression results.
    - Comparative Analysis with representative accounts embodying different stances.
    
    *5.3 Model Evaluation*
    
    - Criteria: Precision, F1 Score.
    - Comparison with Representative Accounts to validate stance classification.
    
    *6. Iterative Improvement*
    
    - *OpenAI's GPT-3.5:*
      - Feedback Mechanism for user input.
      - Bias Mitigation strategies.
    
    - *BERTopic:*
      - Cross-Validation with Diverse Data to enhance generalization.


  - [Results]
  - [Intellectual Merits and Practical impacts of your project.]

## Table of Contents
- literature
- method
- data
- code
- results
- spotlight
- more about the author
- references

## Literature

## Method

## Data

## Code

## Result

## Spotlight
- Posters
- Figures
- Slides
- Presentations
- Review articles
- Media appearance

## More about the Author
- headshot
- self-introduction
- Final reflections 
  - intellectual growth
  - professional growth
  - living a purposeful life

## References

### Data Source
- Data Source Title and URL
### Code Source
- Code Source Title and URL
### Articles
- Article Source Title and URL
### Literature
- Literature References in [Chicago Author-Date](https://www.chicagomanualofstyle.org/tools_citationguide/citation-guide-2.html) Style and [BibTex](https://scholar.google.com/) 

Levin, Dan, and Luyao Zhang. 2020. “Bridging Level-K to Nash Equilibrium.” *The Review of Economics and Statistics* 104 (6): 1329–40. https://doi.org/10.1162/rest_a_00990.

```
@article{levin2022bridging,
  title={Bridging level-k to nash equilibrium},
  author={Levin, Dan and Zhang, Luyao},
  journal={Review of Economics and Statistics},
  volume={104},
  number={6},
  pages={1329--1340},
  year={2022},
  publisher={MIT Press One Rogers Street, Cambridge, MA 02142-1209, USA journals-info~…}
}
```
