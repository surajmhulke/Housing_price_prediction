
## About the Author

Suraj Hulke is a Data Scientist at HCL Technologies with two years of experience in the field. He specializes in Python, Machine Learning, NLP, Deep Learning, and various databases, including MongoDB, SQL, Oracle, MySQL, and PostgreSQL. Suraj is proficient in popular Python libraries such as Pandas, NumPy, TensorFlow, Keras, and has hands-on experience with cloud platforms like AWS, Amazon SageMaker, and Google Colab. He is also well-versed in web development tools like Flask and has expertise in using Git and GitHub for version control.

Suraj's passion for data science and machine learning has led him to contribute to open-source projects and collaborate on innovative solutions. With a commitment to making data science accessible and user-friendly, Suraj's work aims to deliver accurate predictions while maintaining an open-source philosophy.

Feel free to connect with on GitHub to explore my projects and contribution.

# Housing Price Prediction in Beijing

This project is designed to predict housing prices in Beijing using Machine Learning techniques. Whether you are a potential homebuyer or a real estate enthusiast, this project aims to answer your questions and provide a data-driven perspective on housing prices.

## Project Description

### Problem Statement
Thousands of houses are sold every day, and potential buyers often wonder about the fair market price for a property. This project seeks to address these concerns by leveraging the power of data and machine learning to predict housing prices accurately.

### Best Possible Solutions
Three primary approaches are considered for solving this problem: 
1. **Housing Expert:** Utilizing domain knowledge from real estate experts.
2. **Intuition About House:** Intuition-based pricing.
3. **Using Machine Learning:** Employing data-driven machine learning techniques.

### Introduction About Project
Predicting house prices can be a daunting task due to the multitude of factors that affect pricing, such as house structure, rooms, kitchen, parking space, and gardens. Machine learning can assist in finding the perfect house and making accurate price predictions.

### Tools and Libraries
#### Tools
- Python
- Jupyter Notebook
- Flask
- HTML
- CSS
- JavaScript
- Heroku
- GitHub

#### Libraries
- Pandas
- Scikit-Learn
- Numpy
- Seaborn
- Matplotlib

## Data Collection

For this project, we utilized data available on Kaggle. The dataset contains 26 columns and 318,851 rows, featuring key information about the properties in Beijing.

- URL
- Transaction ID
- Coordinates (longitude and latitude)
- Community ID
- Transaction Time
- Active Days on Market
- Number of Followers
- Total Price
- Average Price by Square Foot
- House Square Footage
- Number of Living Rooms
- Number of Drawing Rooms
- Number of Kitchens
- Number of Bathrooms
- Floor Height
- Building Type
- Construction Time
- Renovation Condition
- Building Structure
- Ladder Ratio
- Elevator Presence
- Property Ownership Duration (Five Years or Less)

## Project Flow

### Exploratory Data Analysis (EDA)

#### Data Cleaning
We started with 26 columns but removed unnecessary ones (e.g., URL, Transaction ID, Community ID). Data cleaning included:
- Handling missing values
- Removing corrupted data
- Date and text parsing

#### Feature Engineering
We discovered outliers and applied the IQR method for outlier removal. We identified the top 30 features related to the total price, including factors like transaction time, community average, square footage, and more.

#### Data Normalization
We used min-max normalization to scale numerical features between 0 and 1.

### Choosing the Best ML Model
We explored multiple machine learning models, including Linear Regression, KNN, Decision Trees, and Random Forest.

### Model Creation
Random Forest emerged as the best-performing model with 90% accuracy on test data after hyperparameter tuning. The model was saved using pickle.

### Model Deployment
The model was integrated into a user-friendly web interface using HTML, CSS, and Flask.

### Model Conclusion
The model predicts housing prices with 90% accuracy on test data and 94% accuracy on training data.

### Project Innovation
- User-friendly
- Open source
- High accuracy
- GUI-based application

### Limitations and Next Steps
**Limitations:**
- Lack of a mobile application
- Potential for further accuracy improvements
- Large model size (~310MB)
- Limited feature set

**Next Steps:**
- Develop a mobile application
- Reduce model size using Principal Component Analysis (PCA)


