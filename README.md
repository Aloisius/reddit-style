# reddit-style

![](screenshot.png?raw=true)

This was created in order to better judge whether an article should be trusted based on the 
reputation of the news source.

This adds a label to links on Reddit's r/politics and r/news indicating if a site is:

* A Pulitzer prize winner for Journalism since 1981 (excluding commentary & photography)
* Fringe media: kooks, cranks, conspiracies, rumors, gossip, sensationalism, tabloid journalism, etc.
* Ideologically driven organizations

It also labels opinion articles to distinguish them from actual reporting.


## To Use


If using RedditEnhancementSuite, add by going to settings / appearance / 
stylesheet loader. Under loadStyleSheets, add a row with the following URL:

https://cdn.rawgit.com/Aloisius/reddit-style/master/tweaks.css


## Data

The categories used are arbitrary. Ideally, there would be some sort of letter grade for sources that 
encapsulates ethical standards, journalistic integrity, sensationalism and what not.



## To rebuild 

```shell
sass tweaks.scss tweaks.css
```

