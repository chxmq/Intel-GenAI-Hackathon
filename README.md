## Intel-Hackaton RVCE - Stock Market Prediction

### Team Name: Yash Saraogi

#### Team Members:
1. Yash Saraogi: yashsaraogi.cs23@rvce.edu.in
2. Charan RK: charanrk2003@gmail.com
3. Nishasri R: nishakumbar6104@gmail.com
4. Vatsal Mehta: vatsalmehta163@gmail.com

## Problem Statement:
Stock Market Prediction using AI Analytics Toolkit for predicting Microsoft stocks in the Intel OneAPI AI analytics toolkit Hackathon using trained models.

## Intel One API AI Analytic Toolkit:
We leveraged the powerful toolkits provided by Intel for exceptional performance and efficiency in our project. Key toolkits utilized include Modin, ITEX, and Scikit-learn.

## Dataset:
- **Name:** msft-daily-max.csv (as attached above)

## Steps:
- Download the dataset csv file from the above attached
- Download the stock file with and without intel tools as a comparison of the performance between the same.
- Post downloading run the same on the intel developer cloud after creating the instance and running the notebook.

- pip install chart_studio
- pip install xgboost
- pip install lime
- pip install shapash

## Tech Stack:
1. **Intel® Extension for Scikit-learn:** Enhances Scikit-learn with Intel optimizations.
2. **Modin:** Drop-in replacement for Pandas, designed for parallelizing data manipulation tasks.
3. **Intel® Optimization for TensorFlow:** Boosts TensorFlow performance.

## Scikit-learn for Traditional Machine Learning:
Utilized various regression models such as Support Vector Machine (SVM), Decision Tree, Random Forest, and Linear Regression from the Scikit-learn library.

## Modin for Pandas Parallelization:
Modin accelerates data manipulation tasks using Pandas, efficiently parallelizing operations for handling large datasets in stock market analysis.

## Intel oneAPI for Heterogeneous Parallel Computing:
Complemented Scikit-learn and Modin with Intel oneAPI to harness the power of heterogeneous parallel computing. Used oneAPI's Data Parallel C++ to parallelize machine learning algorithms, optimizing performance across different hardware architectures.

## Intel Developer Cloud Integration:
To further enhance our project's scalability and performance, we utilized the Intel Developer Cloud. Leveraging cloud resources allowed us to seamlessly scale computations and optimize our models for various hardware configurations. This integration facilitated efficient collaboration and resource utilization throughout the development process.

## Combined Approach for Enhanced Performance:
Integrated Scikit-learn, Modin, Intel oneAPI, and Intel Developer Cloud for a comprehensive stock market prediction approach. Leveraged Scikit-learn for traditional machine learning, Modin for efficient data manipulation, and oneAPI for parallelization across diverse hardware. The Intel Developer Cloud played a crucial role in ensuring scalability and efficient utilization of cloud resources.

## Best Performing Model: LSTM (Long Short-Term Memory Networks)
LSTM, a type of artificial neural network (ANN) in deep learning, provided the best accuracy on the dataset. It features feedback connections and is effective in capturing intricate patterns within financial data.

## Future Scopes:
The future scope of stock market prediction using Scikit-learn, Modin, Intel oneAPI, and cloud platforms is promising. Anticipate advancements in AI and ML techniques, including the integration of complex models such as recurrent neural networks (RNNs) and transformers for more accurate predictions. Incorporation of real-time data, advanced data sources, and the rise of quantum computing may revolutionize stock market forecasting.

**Note:** Ensure proper setup of Intel toolkits and dependencies for optimal performance. Refer to documentation for detailed instructions.

---
*Disclaimer: This README serves as documentation for the Intel OneAPI AI analytics toolkit Hackathon project and is subject to updates.*
