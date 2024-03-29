# rss
recommended rss feeds and some tips/tricks. 

Pull requests and general comments are very welcome!

# Overview
- Use [Feedly](https://feedly.com) for adding and managing RSS feeds (after the demise of [Google Reader](http://googlereader.blogspot.com/2013/03/powering-down-google-reader.html)).
- Use [Palabre (Android)](https://play.google.com/store/apps/details?id=com.levelup.palabre) to read RSS on the go (after the demise of [Flyne](https://twitter.com/flyneapp)).

# Tips and Tricks
## `Github`
- use ".atom" after github account to include as appropriate Feedly RSS feed (e.g., [https://github.com/engineerchange.atom](https://github.com/engineerchange.atom))
- follow single repo commits by doing something like: [https://github.com/engineerchange/rss/commits/master.atom](https://github.com/engineerchange/rss/commits/master.atom)

## `Reddit`
- use .rss after subreddit or filter to save as RSS feed (e.g., https://www.reddit.com/r/askscience/.rss or https://www.reddit.com/r/askscience/top/.rss)
- you can group subreddits into a single RSS feed (e.g., https://www.reddit.com/r/askscience+science/.rss)

## Other notes
- Check page source for "rss"
- add /feed/ before url for Medium. So https://medium.com/@melindagates becomes https://medium.com/feed/@melindagates
- Some websites have a /index.html in the baseurl to allow RSS readers to find it.

---

# Tools

## [RSS Subscription Extension (by Google)](https://chrome.google.com/webstore/detail/rss-subscription-extensio/nlbjncdgjeocebhnmkbbbdekmmmcbfjd/related?hl=en-US)
- A Chrome extension allowing you to quickly add a page to your RSS service of choice (e.g., Feedly).

## [Google Alerts](https://www.google.com/alerts)
- Google Alerts allow you to export as a digest to your e-mail or as an RSS feed.

## [Feed 43](https://feed43.com)
- use for websites that don't have clear RSS
- example of usage - [link](https://www.reddit.com/r/rss/comments/a7k3dk/how_can_i_convert_imdb_watchlists_or_raitings/edfv8kt/)

## [TwitRSS.me](https://twitrss.me)
- use for RSS of twitter user or twitter topics

# Top RSS Followings
- These are just the ones that I know and love! Please feel free to reach out with any you would like to add to my list!

## Data Science

### Company Blogs
- Kaggle > No Free Hunch - [http://blog.kaggle.com/feed/](http://blog.kaggle.com/feed/)
- RStudio Blog - [https://blog.rstudio.com/index.xml](https://blog.rstudio.com/index.xml)

### Individuals
- Anders Drachen (Game Analytics) - [https://andersdrachen.com/feed](https://andersdrachen.com/feed)
- Ben Wellington (I Quant NY) - [https://iquantny.tumblr.com/](https://iquantny.tumblr.com/)
- Caitlin Hudon (Haystacks) - [https://caitlinhudon.com/feed](https://caitlinhudon.com/feed)
- Catherine Ordun (Train Me, Test Me, Tease Me) - [https://tm3.ghost.io/rss](https://tm3.ghost.io/rss)
- John Mackintosh (HighlandR) - [https://johnmackintosh.com/feed.xml](https://johnmackintosh.com/feed.xml)
- Julia Silge - [https://juliasilge.com/index.xml](https://juliasilge.com/index.xml)

### Projects
- R-Bloggers - [https://feeds.feedburner.com/RBloggers](https://feeds.feedburner.com/RBloggers)

## Data Visualization

### Data Viz Communities / Groups
- eagereyes - [https://eagereyes.org/feed](https://eagereyes.org/feed)
- Information Is Beautiful - [https://feeds.feedburner.com/InformationIsBeautiful](https://feeds.feedburner.com/InformationIsBeautiful)
- r/dataisbeautiful - [https://reddit.com/r/dataisbeautiful.rss](https://reddit.com/r/dataisbeautiful.rss)

### Individuals
- Cole Nussbaumer Knaflic (Storytelling With Data) - [https://storytellingwithdata.com/feeds/posts/default](https://storytellingwithdata.com/feeds/posts/default)
- Nathan Yau (Flowing Data) - [https://feeds.feedburner.com/FlowingData](https://feeds.feedburner.com/FlowingData)

## Open Data
Hard to find good ones for this, as some just have floods of information with no real substance (e.g., Socrata's Catalog - [https://opendata.socrata.com/catalog.rss](https://opendata.socrata.com/catalog.rss) includes a lot of "Dataset Created: Payroll Report - End Date 1/9/2019" type of posts).

### Data Communities and Individual Groups
- r/datasets - [https://reddit.com/r/datasets.rss](https://reddit.com/r/datasets.rss)

### News Groups
- Baltimore Sun Data Git - [https://github.com/baltimore-sun-data.atom](https://github.com/baltimore-sun-data.atom)
- FiveThirtyEight Git - [https://github.com/fivethirtyeight/data/commits/master.atom](https://github.com/fivethirtyeight/data/commits/master.atom)
- LA Times Data Desk Git - [https://github.com/datadesk.atom](https://github.com/datadesk.atom)
- Sunlight Foundation Git - [https://github.com/sunlightpolicy.atom](https://github.com/sunlightpolicy.atom)

# Broken RSS Feeds
- [ProPublica/Nerds](https://www.propublica.org/nerds) - [https://feeds.propublica.org/propublica/nerds](https://feeds.propublica.org/propublica/nerds) - query out to ProPublica to fix on 1/23/2019. Asked via twitter on 2/25/2019. E-mailed IT manager on 2/27/2019 and received reply. Second email on 5/2/2019.
- [ProPublica/NewsApps](https://www.propublica.org/newsapps/) - [https://feeds.propublica.org/propublica/tools-data](https://feeds.propublica.org/propublica/tools-data) - query out to ProPublica to fix on 1/23/2019. Asked via twitter on 2/25/2019. E-mailed IT manager on 2/27/2019 and received reply. Second email on 5/2/2019.
