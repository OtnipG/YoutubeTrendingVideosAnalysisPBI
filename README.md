# YoutubeTrendingVideosAnalysisPBI
Repository made for DataGlowUp, a challenge created by Heitor Sasaki on Linkedin, in order to instigate the creation of a data analysis portfolio.
This one is the DataGlowUp#29

# About the dataset
The challenge was proposed basen on a famous dataset about Youtube Trending Videos.
You can see more of it here: https://www.kaggle.com/datasets/datasnaek/youtube-new

# About the process
It took a dark and long time to understand how data from a complete stranger domain is extracted and could be manipulated. What is relevant? What can be done? What are the key metrics? What did others analysts do?
Based on that unknown realm, the main goal of the analysis is to be a exploratory analysis. I tried to discover some relevant information about the trending videos: the lifecycle, big numbers distribution, when to post and what is the lenght distribuion of a video title. There is a huge backlog of things to explore, and I hope that in a near future i can look again at this dataset.

# Steps of Analysis
1. Read available information on Kaggle, such as code samples, dataset description and discussion
2. Search for other portfolios and analysis from medium, google and kaggle, looking for what other people have analyzed before
3. Search for academic papers about youtube trending, inspired by a paper from III International Congress in Digital Humanities
4. Manipulation of the Dataset on PBI:
   4.1 Group all files from the countries and creation of a country column
   4.2 Treatment of the trending date
   4.3 Analysis of categories id (could be a same id for different countries? luckily it wasn't)
   4.4 Split of publish time in publish date and publish hour
   4.5 Remotion of errors in publish_time
   4.6 Filter rows with null and blank values in publish_time
   4.7 Creation of Columns: DaysToTrend, TitleWords, TitleLength, TagsCount
   4.8 Filter rows with "#NAME?" or "#NAME!" or "#VALUE!" or "#VALUE?" in video_id
5. Validation and discovery of the data:
   5.1 Categories
   5.2 Publish and trend dates (max, min, registers, unique videos)
   5.3 Creation of measures and sampling over some videos (First Appearence, Last Appearence, Max Value, Min Value, Sum of values)
6. DataViz 

# PowerBI Link


# What's next?
A few things that can still be done and added to the PBI:
- Ask for help with the UX and interface lol I tried to make it more like an infographic, but there is some room for improvement
- Add boxplots along with the histograms
- Add tooltips and text analysis on visuals
- Edit filter interaction
- Trending permanence (there is some patterns about the videos that keep trending for so long? the reason of the session is to unravel the novelty)
- Big numbers growth (hows does the videos that keep on trending perform? what is th views acquisition by period?)
- Interesting metrics about channels (like_dislike ratio, engagement, hate videos (more dislikes than likes)
- Impact of channel size on trending (a huge subscription base counts towards trending? or a small and loyal group is better?)
- What people read before they see? In other words, does a video title impact on trending? a sentiment analysis can be done?
- Replicate what was done in PBI with Python

# Why use PowerBI
This dataset was extensively analyzed before me. You can find tons of NBs and medium posts about the same theme. Sadly, i found academic papers that used the same analysis by different authors.
So, i felt that i couldn't contribute anymore using python/pandas, although it would be challenging and important to me.
The main reason for picking PowerBI was to force me to develop DAX and PowerQuery habilities, along the statistical and distribution capabilities using PBI. Just a few lines of code (copied from someone else's work) in Python and the deed is done!
Besides that, the use of cross filtering and interaction along the dashboard could lead to find differences between any of the categorical data.
Lastly, if we choose to alter the dataset or analyse based on a single parameter, like country or video category, for each analysis we would need to run the NB and read all the data and charts. On PBI it's all done, and we can treat it as a product, improving and receiving upgrades along the time, as listed in "What's next".

# Lessons learned
0. <b>DONE IS BETTER THAN PERFECT. KEEP THAT IN MIND</b>
1. God, please send me a product/project manager to help me prioritizing. Oh shit, I'm one, what am I doing?
   Sometimes we can feel very confident and anxious with so many things to analyze, but keep it simple. Start small and continue to improve. I haven't done this and was buried in a spiral of fear and despair for not delivering anything.
2. Make a backlog and prioritize. You can use a RICE score to find out what to do first.
3. If it take so long, either you are overcomplicating or it is not so easy to be done. On both scenarios, pick a easier path. (Occam's razor)
4. Writing a full article in english for the very first time is soooo uncomfortable for non native speakers, but you can do it (and also can make mistakes, but it's fine)
5. Rely on others for support. Usually we tend to do our work alone, with no help and no one to discuss. Talk to a friend, try to explain what you're doing to a family member, ask for help from a more experienced person in the field you are working..
6. The first thing to do is to find out who's your audience and what you intend to tell, it will save you tons of hours.
