## Project Overview
Amazon receives millions of reviews on all of their listed products. It would be useful for Amazon product owners to quickly know negative product reviews about their products. Not only would it be helpful to correctly classify negative reviews, but we also want to understand why the reviews are negative. This way product owners can take steps to recitfy issues as they arise which would increase customer satisfaction and generate additional revenue. 

## **Process for Text Classification:**
1) Gathering the Dataset: Navigate to https://course.fast.ai/datasets and click download for **Amazon Reviews: Polarity**. <br>
    * There are 3 columns in the train/test data, corresponding to class index (1 or 2), review title, and review text. Class 1 corresponds to a negative classification and class 2 to a positive classification. Each class has 1,800,000 training samples and 200,000 testing samples. 
2) EDA
   * Generate word cloud
3) Data preprocessing: 
    * Normalize Feature text
    * Vectorize text    
4) Modeling:
    * Logistic Regression
5) Extracting feature importance
   * Top 10 words for positive and negative sentiments
   
## **Running NLP_for_Customer_Reviews.ipynb**:
   * execute command `jupyter notebook NLP_for_Customer_Reviews.ipynb`

## **Using AWS Comprehend for Text Classification:**
1) Upload data to an S3 bucket
2) Use Comprehend to classify text


** Note- change to notebook?
## **Running Amazon_ecommerce_NLP.py**:
1) Clone the repository with:<br> `https://github.com/RahulReady/Amazon-ecommerce-NLP.git`
2) Navigate into the repo and create a virtual environment with:<br> `python3 -m venv <addVenvNamehere>`
3) Activate the virtual environment: <br>
On <ins>Windows</ins>, run:<br>
    `<addVenvNamehere>\Scripts\activate.bat`
<br>On <ins>Unix or MacOS</ins>, run: <br>
    `source <addVenvNamehere>/bin/activate`
4) Install the requirements with:<br> `pip install -r requirements.txt`
4) Run the 'Amazon_ecommerce_NLP.py' file with: <br>
    `python3 Amazon_ecommerce_NLP.py`<br>

** Note- Add more to comprehend.ipynb
## **Running Comprehend.ipynb**:
1) Setup a Jupyter Notebook via Sagemaker Studio.
2) Add stuff here

**Note: Original Problem Statement: https://github.com/aws-samples/amazon-sagemaker-architecting-for-ml/blob/master/Writeups/NLP:%20Text%20Classification.md
