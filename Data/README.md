# Description
The dataset, originally from [Kaggle](https://www.kaggle.com/datasets/die9origephit/climate-change-tweets), encapsulates daily Twitter discussions on 'Climate Change' from January 1, 2022, to July 19, 2022.

Selected during a year marked by unprecedented global extreme weather events, this dataset offers a unique window into public sentiment during impactful climatic occurrences. The temporal scope aligns with the research's focus on understanding the correlation between climate discourse, extreme weather events, and environmental policy releases.

Leveraging machine learning, OpenAI's GPT-3.5 for sentiment analysis and BERTopic for topic modeling will be deployed. This comprehensive approach aims to uncover nuanced sentiment variations and prevalent topics within the discussions. The dataset's extensive timeframe enables iterative exploration, allowing for refined insights into the evolving dynamics of public perception concerning climate change on Twitter amidst the backdrop of the climate crisis.

# Data Dictionary

| Column Name      | Definition                                      | Description                                           | Frequency                 | Range                   | Unit         | Type     | Sample Observations                                      |
| ----------------- | ----------------------------------------------- | ----------------------------------------------------- | -------------------------- | ----------------------- | ------------ | -------- | -------------------------------------------------------- |
| UserScreenName   | The Twitter user's screen name or handle.       | Identifies the user on Twitter.                        | Varies (Each tweet author) | N/A                     | N/A          | Categorical | "Lauren Boebert", "George L Ruggiere", "Act on Climate Vic"        |
| UserName         | The user's Twitter username.                    | User's unique identifier on Twitter.                  | Varies (Each tweet author) | N/A                     | N/A          | Categorical | "@laurenboebert", "@ruggiere_l", "@ActOnClimateVic"  |
| Timestamp        | The timestamp when the tweet was posted.        | Indicates when the tweet was published.               | Daily                      | 01/01/2022 - 19/07/2022 | Date & Time  | Temporal   | "2022-01-17T21:10:40", "2022-01-17T22:03:54", "2022-01-17T23:07:18"      |
| Text             | The structure of Twitter posts, including user handles, timestamps, and brief content.                        | The actual text of the tweet.                         | Daily                      | Varies                  | N/A          | Text      | "PETRIFIED CLIMATE PARENT@climate_parent·Jan 17", "Gerry McK@GMcK2012·Jan 17"               |
| Embedded_text    | Any text embedded within the tweet.             | Additional text within the tweet.                     | Occasional                 | Varies                  | N/A          | Text      | "The only solution I’ve ever heard the Left propose for climate change is more taxes, more control and less freedom.", "The climate crisis is front page news in South Gippsland. The community is connecting the dots between climate change and coastal erosion. It's time for govts to act! #ClimateImpactsVic #Auspol #SpringSt"          |
| Emojis           | Emojis used in the tweet to express emotions.   | Emoticons conveying sentiments.                       | Occasional                 | Varies                  | N/A          | Text      | "🌍❤️🌿", "🔥🌊", "😢"                                      |
| Comments         | The number of comments received on the tweet.    | Count of user comments on the tweet.                  | Daily                      | 0 to ∞                 | Count        | Numeric   | 1683, 2259, 11.7K                                                   |
| Likes            | The number of likes (favorites) received.       | Count of user likes on the tweet.                     | Daily                      | 0 to ∞                 | Count        | Numeric   | 1, 12, 22                                                |
| Retweets         | The number of times the tweet has been retweeted.| Count of times the tweet has been shared.             | Daily                      | 0 to ∞                 | Count        | Numeric   | 0, 23, 17                                                 |
| Image link       | Link to any images associated with the tweet.   | URL link pointing to images in the tweet.             | Occasional                 | Varies                  | N/A          | Text      | "[http://example.com/image.png](https://pbs.twimg.com/media/FJVoK_gaIAAQcR9?format=jpg&name=small)", "https://pbs.twimg.com/tweet_video_thumb/FJVdjMmWQAMl9on.jpg", "[http://image-link.com](https://pbs.twimg.com/card_img/1549249134355423232/kb0dAHjG?format=jpg&name=small)" |
| Tweet URL        | The URL link to the tweet on Twitter.            | URL link leading to the original tweet on Twitter.    | Daily                      | Varies                  | N/A          | Text      | "[http://twitter.com/ClimateWatcher/status/123456789](https://twitter.com/laurenboebert/status/1483220748487569409)", "[https://twitter.com/ruggiere_l/status/1483192848086233089](https://twitter.com/ruggiere_l/status/1483192848086233089)", "[https://twitter.com/ActOnClimateVic/status/1483207758334021633](https://twitter.com/ActOnClimateVic/status/1483207758334021633)" |

This detailed data dictionary provides comprehensive information about each variable, including its definition, description, frequency, range, unit, type, and sample observations. The data dictionary is still based on the original dataset, further cleaned and processed version is now available in **cleaned data**([Data/processed data/README.md](https://github.com/Rising-Stars-by-Sunshine/STATS201-PS2-Jenny/tree/7fcd9fe3ae3db0487654d0c5ef1a68fbbec370ba/Data/processed%20data))

# Data Dictionary for newly added columns in processed data

| Column Name      | Definition                                      | Description                                           | Frequency                 | Range                   | Unit         | Type     | Sample Observations                                      |
|-------------------|-------------------------------------------------|-------------------------------------------------------|---------------------------|-------------------------|--------------|----------|----------------------------------------------------------|
| mentioned_users   | Users mentioned in the tweets                   | List of users mentioned in the tweets                  | Per tweet                 | Varies                  | N/A          | Text     | Climate change doesn’t cause volcanic eruptions. |
| partial_clean     | Partially cleaned tweet text                    | Tweet text cleaned with specific options               | Per tweet                 | Varies                  | N/A          | Text     | climate change doesnt cause volcanic eruptions. |
| cleaned_text      | Fully cleaned tweet text                        | Tweet text fully cleaned using preprocessor           | Per tweet                 | Varies                  | N/A          | Text     | climate change doesnt cause volcanic eruptions. |        