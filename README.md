# YoutubeTrendingVideosAnalysisPBI
Repository made for DataGlowUp, a challenge created by Heitor Sassaki on Linkedin, ir order to instigate the creation of a data analysis portfolio

# About the dataset
The challenge was proposed basen on a famous dataset about Youtube Trending Videos.
You can see more of it here: https://www.kaggle.com/datasets/datasnaek/youtube-new

# About the process
It took a dark and long time to understand how data from a complete stranger domain is extracted and could be manipulated. What is relevant? What can be done? What are the key metrics? What did others analysts do?
Based on that unknown realm, the main goal of the analysis is to be a exploratory analysis. I tried to discover some relevant information about the trending videos: the lifecycle, big numbers distribution, when to post and what is the lenght distribuion of a video title. There is a huge backlog of things to explore, and I hope that in a near future i can look again at this dataset.

# What's next?
A few things that can still be done and added to the PBI:
- Ask for help with the UX and interface lol I tried to make it more like an infographic, but there is some room for improvement
- Add boxplots along with the histograms
- Add tooltips and text
- Trending permanence (there is some patterns about the videos that keep trending for so long? the reason of the session is to unravel the novelty)
- Big numbers growth (hows does the videos that keep on trending perform? what is th views acquisition by period?)
- Impact of channel size on trending (a huge subscription base counts towards trending? or a small and loyal group is better?)
- What people read before they see? In other words, does a video title impact on trending? a sentiment analysis can be done?

# Why use PowerBI
This dataset was extensively analyzed before me. You can find tons of NBs and medium posts about the same theme. Sadly, i found academic papers that used the same analysis by different authors.
So, i felt that i couldn't contribute anymore using python/pandas, although it would be challenging and important to me.
The main reason for picking PowerBI was to force me to develop DAX and PowerQuery habilities, along the statistical and distribution capabilities using PBI. Just a few lines of code in Python and the deed is done!
Besides that, the use of cross filtering and interaction along the dashboard could lead to find differences between any of the categorical data.
Lastly, if we choose to alter the dataset or analyse based on a single parameter, like country or video category, for each analysis we would need to run the NB and read all the data and charts. On PBI it's all done, and we can treat it as a product, improving and receiving upgrades along the time, as listed in "What's next".
