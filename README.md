# DotConnect
line connected temporal scatterplot

The visualization draws two consecutive time frames together. Line connects the pair of before and after.
Before dot is drawn with an opacity to distinguish from the after. 
If the data has multiple time frames, clicking the 'next pair' button will switch to next one.

<img src="https://github.com/deardeer/DotConnect/blob/master/img.png" height="400">



### info

- DotConnect
  - data.csv, data1.csv //two random data example. You can draw with your own data by tranforming to this format
  - scatterplot.html //where I draw scatterplot
  - generatedata.ipynb //ipython to generate the random data

### to run 
[1] set up a server
enter the download directory, to run below command (python v3)

pytyon -m http.server 20897

[2] open the visualization
open below url in browser

http://localhost:20897/scatterplot.html
