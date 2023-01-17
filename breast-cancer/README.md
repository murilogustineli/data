# Breast Cancer Wisconsin (Diagnostic) Data Set
## Breast Cancer
### Source
This dataset was obtained from the UCI Machine Learning Repository website at: **https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29**

### Data description
#### Breast Cancer dataset
	RangeIndex: 569 entries, 0 to 568
	Data columns (total 32 columns):
	#   Column  Non-Null Count  Dtype  
	---  ------  --------------  -----  
	0   0       569 non-null    int64  
	1   1       569 non-null    object 
	2   2       569 non-null    float64
	3   3       569 non-null    float64
	4   4       569 non-null    float64
	5   5       569 non-null    float64
	6   6       569 non-null    float64
	7   7       569 non-null    float64
	8   8       569 non-null    float64
	9   9       569 non-null    float64
	10  10      569 non-null    float64
	11  11      569 non-null    float64
	12  12      569 non-null    float64
	13  13      569 non-null    float64
	14  14      569 non-null    float64
	15  15      569 non-null    float64
	16  16      569 non-null    float64
	17  17      569 non-null    float64
	18  18      569 non-null    float64
	19  19      569 non-null    float64
	...
	30  30      569 non-null    float64
	31  31      569 non-null    float64
	dtypes: float64(30), int64(1), object(1)
	memory usage: 142.4+ KB


### Data Set Information:

Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image. A few of the images can be found at [Web Link]

Separating plane described above was obtained using Multisurface Method-Tree (MSM-T) [K. P. Bennett, "Decision Tree Construction Via Linear Programming." Proceedings of the 4th Midwest Artificial Intelligence and Cognitive Science Society, pp. 97-101, 1992], a classification method which uses linear programming to construct a decision tree. Relevant features were selected using an exhaustive search in the space of 1-4 features and 1-3 separating planes.

The actual linear program used to obtain the separating plane in the 3-dimensional space is that described in: [K. P. Bennett and O. L. Mangasarian: "Robust Linear Programming Discrimination of Two Linearly Inseparable Sets", Optimization Methods and Software 1, 1992, 23-34].


### Attribute Information:

1) ID number
2) Diagnosis (M = malignant, B = benign)
3) through 32) Ten real-valued features are computed for each cell nucleus:

	a) radius (mean of distances from center to points on the perimeter)
	b) texture (standard deviation of gray-scale values)
	c) perimeter
	d) area
	e) smoothness (local variation in radius lengths)
	f) compactness (perimeter^2 / area - 1.0)
	g) concavity (severity of concave portions of the contour)
	h) concave points (number of concave portions of the contour)
	i) symmetry 
	j) fractal dimension ("coastline approximation" - 1)
