# ece143_indivproject
This repo is for UCSD ECE143 project - ad hoc communication towers problem.

by Chen-Lin Ko (A53203433)
'''
To cope with issuses in planning of ad-hoc communications towers, this porject is to analyze the coverage of communications
network and maximize the coverage area of any available towers when each towers are put up randomly and indenpendently.

Questions:
1. Given an overall desired coverage footprint and a sequence of n communications towers, what is the resulting resolved coverage?

2. What is the total area of coverage relative to the desired total coverage area of the original footprint? That is, are there any gaps in coverage?

3. On average, how many communications towers are required before full coverage is obtained?



Requirement:
This solution is based on python 2 and requires modules including numpy, random, matplotlib.pyplot, matplotlib.patches. 


Reference:
1. https://gist.github.com/zed/776423
2. https://github.com/boyw165/algorithm-challenge-python/tree/master/maximal-rectangle
3. https://www.geeksforgeeks.org/maximum-size-rectangle-binary-sub-matrix-1s/
4. http://matthiaseisen.com/pp/patterns/p0203/


Visualizing problem of overlapping in random towers planning, which can help to establish basic understanding to the problem
The overlapping area will lead to loss of communications to any towers
Therefore we need to implement methods to prevent any overlap between rectangle subsections by towers
'''
