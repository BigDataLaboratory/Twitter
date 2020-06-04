# Dataset Description

Each dataset file (blackFridayRetweets, worldSeriesRetweets and streamingSampleRetweets) is a tsv (tab-separated-values) representing the directed graph of the same collection.

Each line of the dataset files is an edge between two nodes, represented by numeric value:
•	the first one is the source node
•	the second one is the destination node
The first node represents a Twitter account retweeting any tweet of the second node.


All collections are filtered from Twitter
stream using a set of stop words related to specific events:

•	Black Friday 2015: the day following Thanksgiving Day in the United States.
The event started 10-27-2015 and ended the 11-1-2015, we can see that the observation period started after the beginning of the event.

•	World Series 2015: the annual championship series of Major League Baseball (MLB) in North America, contested since 1903 between the American League (AL) champion team and the National League (NL) champion team.
The event was on the 11-27-2015, and it falls within the observation period.


The third one is composed by the Italian tweets of the whole Twitter stream, filtered by the Italian language, denoted Streaming Sample. To derive the Streaming Sample we use a list of the most frequently used Italian stop words and the Twitter native selection function for languages:

•	Streaming Sample: the tweets extraction is based on the set of stop words typical of the Italian language: articles, prepositions, conjunctions, adverbs, etc.


Statistics on the collections:

## Nodes	Edges	\#tweets	Start Time	End Time
World Series
474,258	840,490	1,932,330	10-30-2015 2:07:07PM	11-27-2015 11:06:06AM
## Black Friday	
2,700,815	3,811,922	9,891,400	11-13-2015 2:38:16PM	12-18-2015
1:32:17PM
## Streaming 
2,541,739	13,708,317	74,749,330	10-26-2015 11:27:12AM	12-12-2015 05:50:45AM



## License
Data are distributed under the terms of the Creative Commons Attribution 4.0 which you can find provided in the file COPYING.
