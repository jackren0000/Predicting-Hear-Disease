### **Predicting Heart Disease with Machine Learning (´• ω •`) ♡**

Every year, millions of people are affected by cardiovascular diseases. What if we could use data to spot the warning signs early? That's exactly what this project is about! We're diving into a health dataset to build a model that can predict the likelihood of a patient having heart disease.

#### **Our Game Plan 🗺️**

1.  **A Peek at the Data (EDA):** First things first, we explored the dataset to understand our patients. We looked at things like age, cholesterol, and chest pain types using cool visualizations to see what the data was telling us.

2.  **Data Cleanup 🧹:** Real-world data can be messy! We found some weird zero values for things like cholesterol (which is impossible!) and cleaned them up by replacing them with the median value. This makes our data much more reliable.

3.  **Finding the Clues (Feature Selection):** Not all data points are created equal. We used a heatmap to find which factors had the strongest correlation with heart disease. The biggest clues turned out to be:
    *   **ST_Slope_Flat**
    *   **ChestPainType_ASY**
    *   **ExerciseAngina_Y**

4.  **Building the Model 🤖:** With our clean data and key features, we trained a **K-Nearest Neighbors (KNN)** classifier. It's a simple but powerful model that makes predictions based on the 'neighbors' of a data point. Our model achieved an accuracy of **76%** using the `ST_Slope_Flat` feature!

#### **Technologies We Used 🛠️**

*   Python
*   Pandas & NumPy
*   Scikit-learn
*   Matplotlib & Seaborn
*   Jupyter Notebook

#### **Try It Yourself! 🚀**

Want to run the analysis? Easy peasy.

1.  **Clone the repo:**
    ```bash
    git clone https://github.com/jackren0000/Predicting-Hear-Disease.git
    ```
2.  **Install the goodies:**
    ```bash
    pip install pandas numpy scikit-learn matplotlib seaborn jupyter
    ```
3.  **Fire up the notebook:**
    ```bash
    jupyter notebook main.ipynb
    ```