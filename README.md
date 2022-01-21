# NFL_4th_Down_Go-For-It_Project

## Motivation
As a football fan, I noticed a league-wide trend where it felt like more teams were going for it on 4th down. After the 2021 NFL regular season ended, I came across a [tweet](https://twitter.com/StatsbyLopez/status/1481096715235217413) from Michael Lopez who is the Director of Football Data and Analytics for the NFL. This sparked my interest in digging deeper into the numbers to find the league-wide trends in go-for-it rates. I wanted to also to find if there was a benefit to going-for-it in 4th and short situations as well as how often teams went for it in such situations in the 2021 season. Additionally, this gave me a great opportunity to work on my data visualization skills with interactive plots using plotly and plots with NFL team logos. 

## Data
The [data](https://github.com/nflverse/nflfastR-data) comes from nflfastR which has scraped NFL play-by-play data from the 1999 NFL season. Since I had no experience in working with nflfastR, I found a great Python tutorial from [@Deryck97](https://gist.github.com/Deryck97) which can be found [here](https://gist.github.com/Deryck97/dff8d33e9f841568201a2a0d5519ac5e).

## League-Wide Go-For-It Rate in 4th and short opportunities
I wanted to first re-create the plot that Michael Lopez tweeted out. I used data from the past 15 seasons starting from the 2007 season. I did this by isolating the data with 4th-and-1, 4th-and-2, and 4th-and-3 opportunies. I then grouped by season and took the probability of going-for-it by dividing the number of passes and runs over the total sum of fourth-and-short plays. I also subsetted the data using win probability in order to remove garbage time plays. Here is the final result:


## References
* [nflfastR website](https://www.nflfastr.com/)
* [nflfastR beginner guide](https://www.nflfastr.com/articles/beginners_guide.html#next-steps)
* [nflfastR data](https://github.com/nflverse/nflfastR-data)
* [@Deryck97](https://gist.github.com/Deryck97)  [nflfastR Python Guide](https://gist.github.com/Deryck97/dff8d33e9f841568201a2a0d5519ac5e)
