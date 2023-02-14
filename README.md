# ISIC Image Classification with Deep Learning and Machine Learning

ISIC 2017 and 2020 Image Classification based on both datasets with traditional and deep learning approaches. It uses Tensorflow through Keras and Sci-Kit for the implementation. Traditional machine learning methods rely in the data provided to describe the lession. Deep learning (CNN) use only the image.

## Potential Improvements
Ensemble machine + deep learning methods could be used to mix both analysis and improve results

## Highlights

1. Traditional  machine learning methods used: SVM, Random Forests and Decision Trees
2. CNN VGG16-Based Solution Implemented
3. Class Imbalanced boarded from 3 perspectives:
    - Deleting Data
    - Balancing Data
    - No pre-processing at all

## How to run
1. Download ISIC 2017 and 2020 Datasets and add the images in the `/train2017` and `/train2020` Directories
2. Verify and substitute if neccesary the .csv files corresponding to these datasets (also included in this repo). Changes could've happened so it is important that the names of the images are updates
3. Install the neccesarry Dependencies mentioned in the `main.ipynb` file
    - Keras
    - Tensorflow
    - NumPy
    - Pandas
    - Matplotlib
    - Seaborn
    - sci-kit (sklearn)
    - missingno 
4. Run all the cells of the same file

## Demo Images

### Data Balancing
![image](https://user-images.githubusercontent.com/87340855/218802198-f0bb4049-7d93-4013-b6c2-e4a4c42212f0.png)

### Variable Correlation Analysis
![image](https://user-images.githubusercontent.com/87340855/218802374-ac3d2615-e07b-4db9-9d94-23cd8eb98165.png)

### Random Forest, SVM and Decision Tree Evaluation
![image](https://user-images.githubusercontent.com/87340855/218802628-4a164d57-090f-4f76-b666-e910c0185aca.png)

### CNN Analysis
![image](https://user-images.githubusercontent.com/87340855/218802799-bc888e22-e229-4be0-89af-b8a7e4a09483.png)
