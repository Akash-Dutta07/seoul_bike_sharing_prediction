

![Image](https://github.com/user-attachments/assets/a3bb9611-f4ee-4fec-bbb3-a037bb678203)

Rental bikes have been introduced in many urban cities to enhance mobility and provide greater comfort for commuters. Ensuring that these bikes are readily available and accessible at the right time is essential, as it helps minimize waiting times for users. A key challenge in maintaining a stable supply of rental bikes is accurately predicting the number of bikes required each hour. The dataset used for this purpose includes various weather parameters such as temperature, humidity, windspeed, visibility, dew point, solar radiation, snowfall, and rainfall, along with hourly bike rental counts and date information.










## **📄Description**
- Models Used: Logistic Regression, Support Vector Machine (SVM), and Random Forest (RF) and many more models are used to figure out the best accuracy model
- Features Analyzed: some features where dropped and some where analysed, for better prediction
- Model Evaluation: Models were evaluated based on accuracy, precision, recall, and F1-score.
- Best Performing Model: XGBRegressor is found to be the most accurate and interpretable model for predicting.
 

## **📥Datasets**


unzip and study the file 
- https://drive.google.com/file/d/1XdamlNyf_m4mUafau9DSum1LyJqLOgrJ/view?usp=drive_link


## **🔧Requirements**
- joblib==1.4.2
- numpy==1.26.4
- pandas==2.2.2
- python-dateutil==2.9.0.post0
- pytz==2024.1
- pywin32==306
- scikit-learn==1.6.1
- scipy==1.15.2
- six==1.16.0
- threadpoolctl==3.5.0
- tzdata==2024.1
- wcwidth==0.2.13
- webencodings==0.5.1 








## How to Use This Repository

You can access and use this repository on your local system using **Visual Studio Code**, or work with it using **Google Colab** or **Jupyter Notebook**.

### Option 1: Using Visual Studio Code (VSC)

1. **Open Visual Studio Code** on your system.  
2. **Clone the Repository**: Open the terminal in VSC and run:
   ```bash
   git clone <repository-url>
   ```
   Replace `<repository-url>` with the actual URL of this repository.

3. **Navigate to the Project Directory**:
   ```bash
   cd <repository-name>
   ```
   Replace `<repository-name>` with the name of the cloned repository.

4. **Open the Project in VSC**:
   ```bash
   code .
   ```

### Option 2: Using Google Colab

1. **Go to Google Colab**: https://colab.research.google.com/
2. **Upload the necessary `.ipynb` notebook file** or  
   open directly from GitHub by using **File > Open notebook > GitHub** and pasting the repo URL.
3. Run the notebook and interact with the ML model in your browser.

### Option 3: Using Jupyter Notebook

1. Ensure you have Jupyter installed. If not, install it via pip:
   ```bash
   pip install notebook
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd <repository-name>
   ```

3. **Launch Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```

Now, explore the project, modify the code, and play with the ML model as needed!



