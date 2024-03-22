# Final Year Project proposals

## Energy consumption prediction with neural networks

This project focuses on developing an energy consumption prediction model using neural networks, in particular RNN and Transformer architectures. By leveraging historical consumption data and considering influencing factors like time, weather, and external variables, neural networks can learn patterns and relationships to make robust predictions. The project entails data preprocessing, model architecture design, training, and validation. Evaluation metrics such as MAE and RMSE will quantify prediction accuracy, with visualization showcasing predicted versus actual consumption.

[neural networks: zero to hero](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ)

[blog](https://xiaochuany.github.io/1principle/posts/gist/makemore.html)

[example](https://github.com/xiaochuany/timeseries)

Datasets:

[uci](https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption)
 
[kaggle](https://www.kaggle.com/datasets/robikscube/hourly-energy-consumption)



## Time series analysis for climate data: statistical approach


This project focuses on utilizing time series analysis to study climate data patterns. By applying techniques like ARIMA, Seasonal Decomposition, and Fourier Transforms, the project aims to uncover trends, cyclic variations, and correlations within publicly available climate datasets.


[notes](https://web.stat.tamu.edu/~suhasini/teaching673/time_series.pdf)

Datasets:

[uci](https://archive.ics.uci.edu/dataset/882/large-scale+wave+energy+farm)  

[kaggle](https://www.kaggle.com/datasets/berkeleyearth/climate-change-earth-surface-temperature-data)




## Largest $k$-nearest neighbour distance

$k$-NN is an off-the-shelf machine learning method for classification and regression problems. In the case of classification, the class of a new data point will be determined by the majority vote of its $k$ neighbors, each carrying its own label. Given a random collection of points, the first part of the project aims to understand the worst-case scenario when finding the $k$-nearest neighbors. This involves characterizing the asymptotic limiting distribution of the largest $k$-NN distance as the number of points becomes large.

The second part of the project involves simulating the $k$-NN distances and justifying the theoretical results explored in the first part. These results will also be used to justify a fast implementation of the $k$-NN algorithm.

See, e.g. Penrose (2003) Random Geometric Graphs

[paper](https://arxiv.org/abs/2301.02506)


## Small clusters of random geometric graphs

Graphs are mathematical construct of pairwise interactions between objects.
In the context of random geometric graphs, objects are random points in $\mathbb R^d$, and edges are formed when two vertices come close to each other. 

This project provides an opportunity to explore in depth the theory  and application of random geometric graphs. The plan for the project is divided into theory part and coding part:

- Theory: characterize the asymptotic distribution of the total number of small clusters (cluster of order $k$ for some fixed $k$) as the total number of points grows to infinity.   
- Coding: simulate random geometric graphs and use algorithms (e.g. DFS) for finding the total number of clusters of a graph.   

See e.g. Penrose (2003) Random Geometric Graphs


[paper](https://arxiv.org/abs/2209.14758)

[tools for visualisation](https://networkx.org/documentation/stable/auto_examples/drawing/plot_random_geometric_graph.html)