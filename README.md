## Search for illegal amber mining HOWTO

This is a description of methodology for this project: http://texty.org.ua/d/2018/amber_eng.
Main idea - use machine learning to find all places of illegal amber mining in Nothern-West regions of Ukraine on satellite images.


## Motivation

In 2010 world prices for amber started to surge. Due to this in 2012 demand was so high that north-western part of Ukraine became place of "amber rush" and "new Wild West". Thousands of prospectors starts to search for gems with shovels and later with water pumps. Hundreds of areas in forests / agricultural land became a desert, a lifeless moon landscape.

We decided to estimate, for the first time, an environmental impact of this phenomenon. 


## Main steps 

1. Research how patches of land with illegal mining could look on satellite images (searching on images for some known locations)
2. Find which map providers have relatively recent satellite images with good resolution. Find examples of places with mining on images.
3. Find and download initial training set
4. Split each image to superpixels (approx same regions)
5. Use neural net to extract features for each superpixel
6. Create labelled set of superpixels for binary classificator
7. Create machine model to classify superpixels
8. Apply model for each image from region of interest
9. Create interactive map with places found by our model
   


We present most informative, as for this moment, interactive map of impact on environment due to illegal amber mining in Ukraine.