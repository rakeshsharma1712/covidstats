
# Covid statistic extract

During Covid time, the management wanted to follow covid related stats from some relible source.
There was a website https://www.covid19india.org/ which was maintained by a group of volunteers to provide this data.
Everything was going fine, when admin of this site decided to  stop support to this site on 31st Oct 2021.



To fill the gap created by absence of above site, we referred government website https://www.mygov.in/covid-19.
But the bigest challenge with this website was that we cannot refer to prev day stats. It shows only daily basis stats.
So I created a POC to extract covid data from website https://www.mygov.in/covid-19 and store it in excel file.

This is a daily batch run which hits government website https://www.mygov.in/covid-19 and extracts daily data.
As an output two files were created: Daily basis file and single file with all days.
In future, this file can be stored in cloud DB if needed.




