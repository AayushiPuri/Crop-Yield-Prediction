# Crop-Yield-Prediction
# Predicting Agricultural Crop Yields Using Deep Learning Techniques

## **Overview**
This project focuses on predicting agricultural crop yields, specifically within the context of the Indian agricultural ecosystem, using deep learning models such as **Multi-layer Perceptron (MLP)** and **Convolutional Neural Networks (CNN)**. The primary objective is to create models capable of accurately forecasting crop yields, which can significantly aid in agricultural planning and decision-making.

## **Key Findings**

### **MLP Model**
- The **MLP** model, a simple yet effective architecture, successfully predicted crop yields by capturing non-linear relationships within the dataset.
- It handled feature interactions well, showing that even relatively straightforward models can provide meaningful predictions for crop yield forecasting.

### **CNN Model**
- The **CNN** model, typically used for image-based tasks, was adapted to process tabular data and demonstrated promising results in capturing complex feature interactions.
- By using convolutional layers with the **ReLU** activation function, the CNN model identified local patterns and relationships, suggesting that CNNs could be useful for agricultural data where spatial dependencies or local correlations exist.

### **Feature Engineering & Preprocessing**
- Data preprocessing, including the **mean imputation** of missing values and **outlier removal** via the **Interquartile Range (IQR)**, enhanced model performance.
- **Feature engineering**, such as creating new features like **Fertilizer_per_Area** and **Pesticide_per_Area**, significantly improved prediction accuracy.

### **Data Encoding**
- **One-hot encoding** of categorical variables such as 'Crop', 'Season', and 'State' enabled the models to better understand the relationship between these factors and crop yield, leading to more accurate predictions.

## **Future Scope**

1. **Advanced Feature Engineering**
   - Incorporating additional data like weather patterns, soil health metrics, and market trends could improve model accuracy. Feature selection techniques such as **SHAP values** could help identify the most impactful features.

2. **Model Enhancement**
   - Further hyperparameter tuning and model refinement, including regularization techniques or deeper neural networks, could improve model performance. Exploring deeper CNN architectures may also help capture more intricate patterns.

3. **Real-Time Data Integration**
   - Integrating real-time data sources, such as **satellite imagery** or **IoT-based environmental sensors**, could enable the model to adapt dynamically to changing environmental conditions, improving prediction accuracy.

4. **Scalability for Larger Datasets**
   - Expanding the model to handle larger and more diverse datasets from various regions, crop types, and time periods would make it more applicable to a broader range of agro-climatic zones.

5. **Model Deployment Optimization**
   - For deployment in resource-constrained environments, optimization techniques like **model pruning** and **quantization** will be essential to reduce computational costs. Deploying the model on edge devices, such as smartphones used by farmers, could make this technology more accessible in rural areas.

6. **Hybrid Models**
   - Exploring hybrid models that combine the strengths of CNNs for feature extraction and MLPs for non-linear mapping could result in better predictive performance.

## **Conclusion**
Both the MLP and CNN models have shown significant potential for predicting agricultural yields. The future scope lies in refining these models, integrating real-time data, and optimizing them for large-scale deployment, ensuring sustainable agricultural practices and enhanced food security.

## **References**
1. Y. LeCun, Y. Bengio, and G. Hinton, "Deep learning," Nature, vol. 521, no. 7553, pp. 436–444, 2015.
2. J. Schmidhuber, "Deep learning in neural networks: An overview," Neural Networks, vol. 61, pp. 85–117, 2015.
3. R. Agrawal and M. Kumar, "Predictive analytics in agriculture: A deep learning perspective," Journal of Agronomy Research, vol. 10, pp. 123–134, 2021.
4. T. Chen and C. Guestrin, "XGBoost: A scalable tree boosting system," in Proceedings of the 22nd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining, 2016, pp. 785–794.
5. M. Young, The Technical Writer's Handbook. Mill Valley, CA: University Science, 1989.
