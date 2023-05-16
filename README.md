# datasets
[Title]Multimodal Named Entity Recognition Model Based on Cross-Modal Feature Enhancement Mechanism

## Dataset download 
Twitter's text dataset has been uploaded,Download the Twitter's image dataset from this link:
https://pan.baidu.com/s/1bGu8H7B1uR74qYZ4OkfX7Q?pwd=arwu

## Dataset statistics
We divided the Twitter-2015 and Twitter-2017 datasets into three parts: training set, development set, and validation set. These two Twitter datasets contain a large number of tweets and rich image information, and are widely used in natural language processing and social media analysis. The following are statistical information tables for two datasets.

Entity Type	Twitter-2015
Train    Dev    Test	Twitter-2017
Train    Dev    Test
Person	  2217     552    1816	  2943     626    621
Location	  2091     522    1697	  731      173    178
Organization	  928      247    839	  1674     375    395
Miscellancous	  940      225    726	  701      150    157
Total	  6176     1546   5078	  6049     1324   1351
Num of Tweets	4000     1000   3257	  3373     723    723

## Data Format
We set an image id for each picture, and we put this image id in the begging of a tweet. Here's an example of a tweet data.

IMGID:16_05_28_482

LeBron B-PER 

James I-PER

Comments O 

on O 

Reaching O

6 O

th O 

Straight O

NBA B-ORG

Finals O


