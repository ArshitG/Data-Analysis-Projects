# Data-Analysis-Projects
---
## Table Of contents
1. [Basics Project in Jupyter Beginning](#Basics-Project-in-Jupyter-Beginning)
2. [Data analysis of GooglePlay and Appstore Project 1](#Data-analysis-of-GooglePlay-and-Appstore-Project-1)
3. [HackerNews Dataset Analysis](#HackerNews-Dataset-Analysis)
4. [Analyzing Ebay Car Sales Dataset](#Analyzing-Ebay-Car-Sales-Dataset)
5. [Exploratory Data Visualization on The I-94 Traffic Dataset](#Exploratory-Data-Visualization-on-The-I-94-Traffic-Dataset)
---
## Basics Project in Jupyter Beginning

This small file was just to to look around and get a feel of `Jupyter Notebook` , I opened a file, made a table and played around with code cells and markdown cells and understood the shortcuts of Jupyter Notebook and got the hang of Markdown references.

---
## Data analysis of GooglePlay and Appstore Project 1

This project contains alot of python coding without any important libraries such as Pandas or Numphy. This analysis was done using the basic python to understand all the processes of what is happening before using any libraries to cut short that process. I was
able to understand the logics used in Data analysis in this project, and working with real-life datasets is always fun! Here's a breif Introduction of what I did in the project:

* A [dataset](https://www.kaggle.com/lava18/google-play-store-apps) containing data about approximately ten thousand Android apps from Google Play. You can download the data set directly from this [link](https://dq-content.s3.amazonaws.com/350/googleplaystore.csv).
* A [dataset](https://www.kaggle.com/ramamet4/app-store-apple-data-set-10k-apps) containing data about approximately seven thousand iOS apps from the App Store. You can download the data set directly from this [link](https://dq-content.s3.amazonaws.com/350/AppleStore.csv).

`Our aim in this project is to find mobile app profiles that are profitable for the App Store and Google Play markets. We're working as data analysts for a company that builds Android and iOS mobile apps, and our job is to enable our
team of developers to make data-driven decisions with respect to the kind of apps they build.`

`At our company, we only build apps that are free to download and install, and our main source of revenue consists of in-app ads. This means that our revenue for any given app is mostly influenced by the number of users that use our app.
Our goal for this project is to analyze data to help our developers understand what kinds of apps are likely to attract more users.`

### Conclusion

`Above, We can see that e-readers and dictionaries are popular in googleplay store, SO we can tell there is still market for these. However, if we make a simple app that is similar to thousands of apps that are already in the market, 
We might not achieve anything with that. So our idea of doing something different by making an app that let's us read books and recommends songs based on the book,we can also add an in built player with a saved playlist for some really
popular books, and let users add their own choices onto that list. Since We want to keep our app free, buiyng the license for the songs can be expensive and out of budget, so we can give them an option to connect our app to their Spotify,
like Discord. We can also include some options like discussion forums and quizzes on books to make it more interactive.`

The conclusion above was for Google Play aand  The conclusion that I found after doing the analyis on both AppStore and Google Play was:

`In this project, we analyzed data about the App Store and Google Play mobile apps with the goal of recommending an app profile that can be profitable for both markets.`

`We concluded that making an app that is an advanced verion of e-reader, with music recommendations of each book, and options to connect it to spotify for better user 
experience can be a good idea. We can include Discussion Forums and quizes on the books to make the app more interactive.`

---
## HackerNews Dataset Analysis
In this Project, I mainly played around with the dates and times using the `Python datetime module`, exploring the datetime library was really fun and sometimes it was complex but understanding the complex problems
was why I chose to specialise in the data Science field. I'll do a little introduction about what this project was about:

`For all of you who do not know what HackerNews is,Hacker News is a site started by the startup incubator Y Combinator, where user-submitted stories (known as "posts") receive votes and comments, similar to reddit. Hacker News is extremely popular in technology and startup circles, and posts that make it to the top of the Hacker News listings can get hundreds of thousands of visitors as a result.You can find the original data set` **[here](https://dq-content.s3.amazonaws.com/356/hacker_news.csv)**

`In this Project,We're specifically interested in posts with titles that begin with either Ask HN or Show HN. Users submit Ask HN posts to ask the Hacker News community a specific question. Likewise, users submit Show HN posts to show the Hacker News community a project, product, or just something interesting. We are going to analyze a downsampled dataset of HackerNews posts to analyze the following things:`

`* Do Ask HN or Show HN receive more comments on average?`
`* Do posts created at a certain time receive more comments on average?`

`**You can get the downsampled dataset `**[here](https://dq-content.s3.amazonaws.com/356/hacker_news.csv)**

### Conclusion
`So, There we go, The top 5 hours to make a post for the most interaction. But this is for EST timezone, as mentioned in the documentation of the dataset. Since, my timezone is the same, I didn't need to, But you might! We found that Ask Posts made between the time 1500-1600 EST hours(3:00 pm-4:00 pm EST) received more comments. Keep in mind that we did not include the posts with no title, so essentially this analysis is only for the Ask posts.`

---

## Analyzing Ebay Car Sales Dataset
In this project, I used pandas and NumPy libraries of Python and used as many concepts of DataFrames and series as I could, to get a thorough understanding of the libraries, I used the pandas documentation to understand the arguments of each method I was using, I learned a lot in this project such as Boolean Indexing, aggregation, and storing aggregate data in a DataFrame.

### Introduction:

`
In this project, We are going to work with dataset of used cars from eBay Kleinanzeigen, a classifieds section of the German eBay website. The dataset was originally uploaded on Kaggle by user orgesleka, but it's not available there anymore. You can access the dataset `[here](https://data.world/data-society/used-cars-data)`. The dataset we are going to use is a less cleaned version of the data, with 50,000 data points. Our aim in this project is to clean the data and analyze used car listings.`

---

## Exploratory Data Visualization on The I-94 Traffic Dataset
In this project, I focused on Exploratory Data Visualization, I used the Matplotlib library and made use of bar charts, horizontal bar charts, line plots and scatter plots to represent and analyse different Data, It was really fun to use this library and I read alot of the documentation as I was using all the libraries. Here's a brief intoduction on the project and also the conclusion I got after completing the project:

### Introduction
`There are two types of Data Visualizations:`

`* Exploratory`
`* Explanatory`

`Exploratory data visualization is used by analysts for their own usage and to understand the data better, Whereas, Explanatory Data Visualization is used for communicating and explaining to others of the patterns found while exploration. In this Project, We will focus on Exploratory data visualization.`

`We're going to analyze a dataset about the westbound traffic on the I-94 Interstate highway.`

`John Hogue made the dataset available, and you can download it from the` [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Metro+Interstate+Traffic+Volume).

`The goal of our analysis is to determine a few indicators of heavy traffic on I-94. These indicators can be weather type, time of the day, time of the week, etc. For instance, we may find out that the traffic is usually heavier in the summer or when it snows.`

### Conclusion 

`#### Time Indicators:`
`* Warm Months(March-September) are busies than colder months(October-February)`
`* Business Days are busier than Weekends.`
`* Rush hours are 7 and 16 on business days.`
`#### Weather Indicators:`
`* Proximity thunderstorm with drizzle`
`* Shower snow`
`* Light rain and snow`




