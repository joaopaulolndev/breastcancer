# Breast Cancer Classification

##### Little Definition About Breast Cancer
> Breast cancer starts when cells in the breast begin to grow out of control. These cells usually form a tumor that can often be seen on an x-ray or felt as a lump. The tumor is malignant (cancer) if the cells can grow into (invade) surrounding tissues or spread (metastasize) to distant areas of the body.

# Problem Description

- Predicting if the cancer diagnosis is benign or malignant based on several observations/features 
- 30 features are used, examples:
        <br/>- radius (mean of distances from center to points on the perimeter)
        <br/>- texture (standard deviation of gray-scale values)
        <br/>- perimeter
        <br/>- area
        <br/>- smoothness (local variation in radius lengths)
        <br/>- compactness (perimeter^2 / area - 1.0)
        <br/>- concavity (severity of concave portions of the contour)
        <br/>- concave points (number of concave portions of the contour)
        <br/>- symmetry 
        <br/>- fractal dimension ("coastline approximation" - 1)
        <br/>
- Datasets are linearly separable using all 30 input features
- Number of Instances: 569
- Class Distribution: 212 Malignant, 357 Benign
- Target class:
         <br/>
         - Malignant
         <br/>
         - Benign
<br/><br/>
https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)


# Libraries
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Sklearn
