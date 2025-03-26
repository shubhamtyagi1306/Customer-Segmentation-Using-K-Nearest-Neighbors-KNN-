# Customer-Segmentation-Using-K-Nearest-Neighbors-KNN-
This project applies the K-Nearest Neighbors (KNN) algorithm to segment customers based on their annual income and spending habits. The goal is to identify meaningful customer clusters that can help businesses improve targeted marketing strategies.

## **Dataset**
- **Source:** [Mall Customers Dataset](https://www.kaggle.com/datasets/shwetabh123/mall-customers)
- **Attributes:**
  - `CustomerID`: Unique identifier for customers
  - `Genre`: Gender of the customer
  - `Age`: Age of the customer
  - `Annual Income (k$)`: Annual income in thousand dollars
  - `Spending Score (1-100)`: Spending behavior rating

## **Project Steps**
### **1. Data Collection & Loading**
- Load the dataset containing customer information such as gender, age, income, and spending score.

### **2. Exploratory Data Analysis (EDA)**
- Analyze the dataset for missing values, summary statistics, and distributions.
- Use visualization techniques such as pair plots and histograms to understand data trends.

### **3. Data Preprocessing**
- Select relevant features (Annual Income & Spending Score) for customer segmentation.
- Standardize the data to ensure fair distance measurements in the KNN algorithm.

### **4. Implementing KNN Algorithm**
- Split the dataset into training and testing sets.
- Train the KNN model using a predefined number of neighbors (K).
- Predict customer clusters based on the trained model.

### **5. Model Evaluation**
- Evaluate the accuracy of the model using metrics like accuracy score and classification report.
- Analyze how well the model predicts customer segments.

### **6. Optimizing K Value**
- Test different values of K to determine the optimal number of neighbors.
- Plot error rates against different K values to identify the best choice.

### **7. Retraining & Final Evaluation**
- Retrain the KNN model using the optimal K value.
- Compare performance before and after optimization to ensure improvement.

### **8. Visualizing Customer Clusters**
- Use scatter plots to visualize how customers are grouped based on spending habits and income.
- Interpret results for business insights and marketing strategies.

## **Conclusion & Key Insights**
- Customers can be grouped based on their spending habits and income.
- Finding the optimal `K` value improved the model's performance.
- This segmentation helps businesses better target customer groups for marketing strategies.

