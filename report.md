# OCR assignment report

## Feature Extraction (Max 200 Words)

[In the Feature section, I choose PCA method as my solution. 
In order to complete the feature extraction, we have 2 steps before 
we reduce dimensions to finish: feature normalization and zero mean
normalization. The process can be regarded as finding new vectors from
original vectors and project it onto the PCA axes. Take n-Dimensions to
k-Dimensions for instance, we can find k vectors u1, u2,...uk which 
defines a new vector space and then projected with them. So in the 
program, the first thing to do is to find the mean vector of data 
and the transform matrix of PCA. After calculation with the data, the 
result of both eigenvalues and eigenvectors are achieved. Afterwards, 
the values of mean are subtracted from all data points and the 
points are able to projected onto the PCA axes which finally 
produce the final feature vector.]

## Classifier (Max 200 Words)

[In the classifier section, I chose Nearest Neighbor Classifier as my
preferred classifier according its convience. The Nearest
Neighbor Classifier doesn't need to consider the format and data of each spiece as
a non-parametric method. The first step is to identify whether the feature 
already has or not. Depend on the situation, we can use all feature if 0 
feature parameter has been supplied. Desired features chosen from training
and test data was then selected in order to calculate the distance(cosine 
distance) between chosen vectors. Then the  indices of the maximum values 
of the nearest vectors along the given axis are returned. ]

## Error Correction (Max 200 Words)
[Upload a clear dictionary and attempt to write a function about how to detect 
sequential characters whether they are words or not.]

## Performance

The percentage errors (to 1 decimal place) for the development data are
as follows:
- Page 1: [Insert percentage here, e.g. 98.0%]
- Page 2: [Insert percentage here, e.g. 96.7%]
- Page 3: [Insert percentage here, e.g. 72.3%]
- Page 4: [Insert percentage here, e.g. 44.5%]
- Page 5: [Insert percentage here, e.g. 30.4%]
- Page 6: [Insert percentage here, e.g. 23.6%]

## Other information (Optional, Max 100 words)

[Optional: highlight any significant aspects of your system that are
NOT covered in the sections above]
