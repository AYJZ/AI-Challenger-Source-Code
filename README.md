# AI-Challenger-Source-Code

This project focuses on predicting enzyme activity using various machine learning algorithms. Enzymes play a crucial role in various industries, and optimizing their activity traditionally involves time-consuming repetitive experiments. We aim to simplify this process by searching the best machine learning model that can accurately predict enzyme activity based on input parameters. 

Moreover, we're taking it a step further by creating a user-friendly website. This platform bridges the gap between the technical aspects of data analysis and the ease of use for users who may not have programming expertise.

To provide a more comprehensive overview, the project can be distilled into three components:
1. **Data Preparation**: This component focuses on gathering and preprocessing the enzymatic reaction dataset. It ensures that the data is clean, scaled, and structured for effective analysis. Dummy data generation with standard deviation and mean is also employed to expand the dataset. 
2. **Model Training**: In this phase, we trained machine learning models to predict enzyme activity. We partitioned the dataset into training and testing subsets and utilize cross-validation techniques to estimate how well the trained regression models are likely to perform on new data. Various regression algorithms, such as Linear Regression, Random Forest, Decision Tree, Linear Regression, and Support Vector Regression, are employed and evaluated for accuracy. Random Forest and Decision Tree are proven to work the best. 
3. **Web Interface**: Finally, we created a user-friendly website that allows users to upload their data in CSV format. The website then automatically processes the data using the trained models, enabling users to select the best algorithm for their specific dataset and view predictions. This is the webpage link: https://mlprediction.org/
   

In summary, this project seeks to combine advanced machine learning techniques with user-friendly web development to enhance the field of enzyme activity prediction and beyond. Our goal is to make this complex process more accessible and efficient, benefiting both experts and those new to the field.
