# Assignment 2: Collecting your own data.

Some great stories come out of reporters collecting their own datasets. Here are some examples:
* [Governors with very low approval ratings](https://fivethirtyeight.com/features/chris-christie-is-still-more-popular-than-governors-who-were-literally-criminals/)
* [Every Trump tweet insulting anything](https://www.nytimes.com/interactive/2016/01/28/upshot/donald-trump-twitter-insults.html)
* [White House visitors](https://www.politico.com/interactives/databases/trump-white-house-visitor-logs-and-records/index.html)
* [Emergency room bills](https://erbills.vox.com/)

## Assignment

Think about an area you're interested in, or one you may do your final project on, and come up with a dataset you wish existed. Then submit the following:

* A description of the question you're curious about, and an explanation about how this data could turn into a story. (Imagine this as your justification to your editor as to why this is worth your time)
* A list of the things you want to know about any data point
* An explanation of how you'd go about collecting that data (you don't actually have to do it on an ongoing basis, especially if it involves staking something out, just tell me how you would do it).
* A table including at least five data points in this dataset
* You can put your data in a google sheet (in which case, put the link in your homework) or make a table directly in the document you submit.
* Your dataset cannot be something you can just find elsewhere. For example, do not pick something like "all earthquakes above magnitude 7 in the US" because someone (the USGS) already has exactly that data collection. If you want to do earthquakes, add more information such as the number of injuries and deaths reported in the media, and possibly include a link to the relevant media report as one of your columns.
* Submit this assignment as `assigment2.md`. Remember your assignment *must* be written in markdown.

## Can we have an example?

### Sure.

Sarah Huckabee Sanders conducted press conferences for the Trump administration. She has a varied wardrobe, and I wonder if there are any colors she prefers. For example, does she avoid blue, since it's typically associated with Democrats? Since the press secretary is the public face of the White House, I'm interested in whether there's a style story related to her fashion decisions.

Here are the features I'll be collecting, and an explanation of why:
* The color of Sanders' shirt or jacket (the outermost layer when there are multiple layers) (or N/A if Sanders did not conduct the press conference)
* The date of the press conference
* The time of the press conference (start time)
* The location of the press conference (I'm curious whether this makes any difference - does she dress differently in the press room than elsewhere?)
* The outdoor temperature at the time of the press conference (this might be a counfounding factor, for example if she is more likely to be wearing a winter jacket)
* A list of other people who spoke from the podium at the press conference, separated by semicolons
* A link to an image of Sanders at the press conference from one of the following news sources: NYT, WaPo, WSJ, Politico, CNN, CSPAN.

I will collect the data by watching part of the press conference and recording this information. I will use weather.gov to find the temperature in the city where the press conference is taking place. I will find the image by looking at the news sources cited above.

Color | Date | Time | Location | Temperature | Other speakers | Image link
---- | ----- | ---- | -------- | ----------- | -------------- | ----------
tk | tk | tk | tk | tk | tk | tk


*You actually have to collect 5 datapoints from your proposed dataset -- this is just an example*
