# New Left Plot
by Leo Impett


Some basic plotting to visualize the images which have accompanied articles in the New Left Review (since its relaunch). Visualisations made in Python with Plotly. 

There are two versions of the visualization - each is useful in different ways:

# Entropy vs. Volume Number

## [Fast Version](entropy_hover.html)
No images - just the x-y dots. Shows the image, and link to original image and source article, on hover. Very fast (if your internet connection is too). 

## [Slow Version](thumbs.html)
Quite slow, but with tiny thumbnail previews of the images themselves. Also includes links to the original images (on the NLR website); hover over the centre of a datapoint to get the clickable link to its original. 

# 'Image Similarity' (neural network features reduced to 2 dimensions by T-SNE)

## [Fast Version](tsnePoints_hover.html)

## [Slow Version](tsne.html)

All charts are selectable by author. The author is inferred automatically from the article URL (only the first author is taken). 

