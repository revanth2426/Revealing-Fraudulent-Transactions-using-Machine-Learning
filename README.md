# Revealing-Fraudulent-Transactions-using-Machine-Learning
Revealing Fraudulent Transactions using Machine Learning


KAGGLE ORGINAL Dataset
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

UPDATED DATASET
https://drive.google.com/file/d/12nY4AzZvQgvz9BVjsxX3RYseqtAVnY_F/view?usp=share_link


Firstly, we had to install some modules (can be done using command prompt)
•	Streamlit is a Python library used for building interactive web applications for data science and machine learning projects, by following command in cmd.

			pip install streamlit.
•	scikit-learn is a Python library for machine learning and data mining, providing a range of tools for classification, regression, clustering, and dimensionality reduction via a consistent interface.

			Pip install scikit-learn.
•	Joblib is a Python library for efficient and easy-to-use tools for saving and loading Python objects, especially large numerical data, to and from disk

			Pip install joblib.


1.	To start the project, the first step was to obtain the dataset from Kaggle via the provided link. The dataset was then uploaded to a Jupyter notebook, where all the necessary operations were performed. 

2.	After performing all the operations, the Jupyter notebook was saved and the JOBLIB module was used to dump the file in the form of a .pkl format. This allowed the file to be saved with all the relevant information up to the last stage of the notebook. The .pkl file was saved in the same directory as the notebook.

3.	The next step involved uploading the .pkl file to the Interface.py file, which utilized the Streamlit module to create an interface. To run the interface, we simply open the terminal and invoked the Streamlit module using the command "streamlit run Interface.py".

4.	Once the interface was launched, we entered the encrypted values for each data entry in the provided form. After entering all the required information, we must click on the "detect" button to determine whether the transaction was fraudulent or legitimate.
