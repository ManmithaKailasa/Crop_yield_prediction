# Crop_yield_prediction
This project implements a machine learning solution for predicting crop yield based on historical agricultural data. It utilizes a Decision Tree Regressor model to estimate crop production and yield per acre, providing insights that can be valuable for farmers, agricultural planners, and policymakers

-Data Upload and Preprocessing: Users can upload crop datasets in CSV format. The application preprocesses the data by encoding categorical features (State, District, Season, Crop) using Label Encoding and normalizing the numerical features.

-Decision Tree Regression: A Decision Tree Regressor model is trained on the preprocessed data to learn the relationships between various input features and crop production.

-Model Training and Evaluation: The application splits the uploaded dataset into training and testing sets, trains the Decision Tree Regressor on the training data, and evaluates its performance using Root Mean Squared Error (RMSE) on the testing data.

-Crop Yield Prediction: Users can upload separate test datasets to predict crop yields. The application preprocesses the test data and uses the trained model to estimate production and yield per acre for each record in the test dataset.

-Graphical User Interface (GUI): The Tkinter-based GUI provides a user-friendly interface for all functionalities, including data upload, preprocessing, model training, and prediction. Results are displayed within the GUI.

-Tech Stack:
.Python
.Tkinter
.Pandas
.Scikit-learn (sklearn)
.NumPy
.Matplotlib (for potential future visualization enhancements)

-Potential Applications:
.Informing farmers about expected yields, enabling better planning of harvesting and sales.
.Assisting agricultural planners in resource allocation and crop management strategies.
.Supporting policy decisions related to agriculture and food security.

-How to Use:
.Install the required Python libraries (pandas, scikit-learn, numpy).
.Run the Python script.
.Use the GUI to upload a crop dataset, preprocess the data, train the model, and upload test data to predict crop yields.

-Future Enhancements:
.Implement more sophisticated machine-learning models (e.g., Random Forest, Gradient Boosting).
.Incorporate weather data, soil data, and other relevant factors to improve prediction accuracy.
.Develop interactive visualizations of the predicted crop yields.
.Create a more robust error handling and data validation system.
.Allow users to tune model hyperparameters.
