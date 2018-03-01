# Diagnostic and Prognostic Breast Cancer

## Diagnostic Breast Cancer

- predicting field ->  diagnosis: B = benign, M = malignant

There are two main classifications of tumors. One is known as benign and the other as malignant. A benign tumor is a tumor that does not invade its surrounding tissue or spread around the body. A malignant tumor is a tumor that may invade its surrounding tissue or spread around the body.

- Number of attributes: 32 (ID, diagnosis, 30 real-valued input features)

### Attribute Information

1) ID number
2) Diagnosis (M = malignant, B = benign)
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

- Missing attribute values: none
- Class distribution: 357 benign, 212 malignant

## Prognostic Breast Cancer

- Predicting field -> outcome: R = recurrent, N = nonrecurrent
- Dataset should first be filtered to reflect a particular endpoint; e.g., recurrences before 24 months = positive, nonrecurrence beyond 24 months = negative.

- Number of attributes: 34

### Attribute Information

1) ID number
2) Outcome (R = recur, N = nonrecur)
3) Time (recurrence time if field 2 = R, disease-free time if 
	field 2	= N)
4-33) 
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

- Class distribution: 151 nonrecur, 47 recur
