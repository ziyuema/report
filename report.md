# OCR assignment report

## Feature Extraction (Max 200 Words)

[In order to complete the feature extraction, we have 2 steps before 
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

[Describe and justify the design of your classifier and any
associated classifier training stage.]

## Error Correction (Max 200 Words)

[Describe and justify the design of any post classification error
correction that you may have attempted.]

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
