# Breast Cancer Wisconsin (Diagnostic) Data Set
## Breast Cancer
### Source
This dataset was obtained from the UCI Machine Learning Repository website at: **https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29**

### Data description
#### Breast Cancer dataset
	RangeIndex: 1599 entries, 0 to 1598
	Data columns (total 12 columns):
	 #   Column                Non-Null Count  Dtype  
	---  ------                --------------  -----  
	 0   fixed_acidity         1599 non-null   float64
	 1   volatile_acidity      1599 non-null   float64
	 2   citric_acid           1599 non-null   float64
	 3   residual_sugar        1599 non-null   float64
	 4   chlorides             1599 non-null   float64
	 5   free_sulfur_dioxide   1599 non-null   float64
	 6   total_sulfur_dioxide  1599 non-null   float64
	 7   density               1599 non-null   float64
	 8   pH                    1599 non-null   float64
	 9   sulphates             1599 non-null   float64
	 10  alcohol               1599 non-null   float64
	 11  quality               1599 non-null   int64  
	dtypes: float64(11), int64(1)
	memory usage: 150.0 KB


### Data Set Information:

Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image. A few of the images can be found at [Web Link]

Separating plane described above was obtained using Multisurface Method-Tree (MSM-T) [K. P. Bennett, "Decision Tree Construction Via Linear Programming." Proceedings of the 4th Midwest Artificial Intelligence and Cognitive Science Society, pp. 97-101, 1992], a classification method which uses linear programming to construct a decision tree. Relevant features were selected using an exhaustive search in the space of 1-4 features and 1-3 separating planes.

The actual linear program used to obtain the separating plane in the 3-dimensional space is that described in: [K. P. Bennett and O. L. Mangasarian: "Robust Linear Programming Discrimination of Two Linearly Inseparable Sets", Optimization Methods and Software 1, 1992, 23-34].


### Attribute Information:

1.  ID number
2. Diagnosis (M = malignant, B = benign)
3-32)

Ten real-valued features are computed for each cell nucleus:

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