# Planned revisions to reproduction of Malcomb
Author: Ola, Zalecki

Created October 12, 2023

## List of changes 

1. Changing the numeric classification mode

## Analysis

Classification methods in data visualization have an impact on how the the data appears on the map. Therefore, these methods affect the patterns and how we interpret them. Because the original publication (Malcomb) uses the Jenks Natural Breaks method, the reproduction also uses this method to classify the data. I wonder if this is indeed the most ideal method of classification and if that has an effect on how adaptive capacity is visualized. 

## Results

I will first generate a histogram to consider the distribution of the values of the reproductions adaptive capacity scores. I will interpret the distribution and then based on that interpretation decide if another classification method would be more appropriate to use. I will be referring to this list of numeric classification methods that are available on QGIS: equal count (quantile), equal interval, fixed interval, logarithmic scale, pretty breaks, natural breaks(jenks), and standard deviation. 

## Discussion

I will interpret the results of my changes by generating another map of {r reproduction-figure-4-map} but with another classification mode based on my consideration of the distribution of values in the histogram. Different classification methods change the appearance of the patterns of data. If my new revised map shows a spatial distribution of adaptive capacity that is wildly different from the one already in the reproduction, I beleive that is something that should be considered as a point of uncertainty.  
