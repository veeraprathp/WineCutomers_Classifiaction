# Wine Customer Classification using PCA and Logistic Regression

This project demonstrates the use of Principal Component Analysis (PCA) to reduce the dimensionality of a wine customer classification dataset, followed by implementing Logistic Regression for classification.

## Dataset

The dataset contains information on different wine samples with the following features:

- **Alcohol**
- **Malic Acid**
- **Ash**
- **Ash Alkalinity**
- **Magnesium**
- **Total Phenols**
- **Flavanoids**
- **Nonflavanoid Phenols**
- **Proanthocyanins**
- **Color Intensity**
- **Hue**
- **OD280/OD315**
- **Proline**
- **Customer Segment** (Target variable)

## Project Steps

1. **Data Preprocessing**:
    - Load the dataset.
    - splitting the training and test
      
2. **Principal Component Analysis (PCA)**:
    - Reduce the dimensionality of the dataset to 2 principal components.

3. **Classification using Logistic Regression**:
    - Implement Logistic Regression on the reduced dataset.
    - Evaluate the model performance.
    - Visulaized the traing and test set results
## Results

The implementation successfully reduces the dataset to 2 dimensions using PCA and applies Logistic Regression for classification got the acuuracy of 97 percentage. The results and insights from the project can be found in the notebooks and visualizations provided.

## Requirements

- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Google Colab


## Conclusion

This project demonstrates how PCA can be used for dimensionality reduction in a wine classification problem, followed by Logistic Regression for effective classification. The approach and results are documented in the provided notebooks.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

Thanks to the creators of the dataset and the open-source community for providing the tools and resources to make this project possible.
