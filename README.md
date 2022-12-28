# K-means algorithm using python library Assignment 3

<h1>
	1.	K-means clustering
</h1>
<p> 
In this this exercise, you will implement the K-means algorithm. You will experiment with an example 2D dataset that will help you gain an intuition of how the K-means algorithm works.
The K-means algorithm is a method to automatically cluster similar data examples together. Concretely, you are given a training set 〖{x〗^((1)),…,x^((m) )} (where x^((i))∈R^n), and want to group the data into a few cohesive “clusters”. 
</p>
<p> 
DataSet. Given Data in the csv file: k-means.csv
There are 2 columns (X1,X2). Use pd.read_csv for loading data and substitute “,” with “.”
</p>

<h3>
Implementation of K-means algorithm (80%). 
<\h3>

<p>a)	load and visualize initial data. 	</p>

<p>b)	Solve same problem by K-means algorithm using python library	</p> 

<p>c)	Test following pairs and define their cluster:  (0.3; 5.2), (2; 4.4), (1.1; 5.2), (5.2; 2.9), (5.3; 3.3), (6.1; 2.8)	</p>

<p>d)	Visualize clusters. 	</p>

<p>e)	calculate silhouette_score	</p>


<h3>
Report (20%).
</h3>

<p>
Write codes, their explanation and achieved results for each step (1-4) of homework in the report. Codes must be in text format. You can take screen shots only for output of program. 
</p>

<p>
The K-means algorithm will always converge to some final set of means for the centroids. Note that the converged solution may not always be ideal and depends on the initial setting of the centroids. Therefore, in practice the K-means algorithm is usually run a few times with different random initializations. One way to choose between these different solutions from different random initializations is to choose the one with the lowest cost function value (distortion). 
At the end, you may try to visualize your data to see whether your code works correctly (Figure 1). 
</p>