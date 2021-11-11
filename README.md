# Predicting whether an applicant is capable of repaying a loan
<a style="margin:30px" href="https://www.featuretools.com">
    <img width=50% src="https://www.featuretools.com/wp-content/uploads/2017/12/FeatureLabs-Logo-Tangerine-800.png" alt="Featuretools" />
</a>

**As a bank decides which applicants to provide loans, they may wish to predict if the applicant will default on the loan. Through automated feature engineering, we can identify the predictive patterns in the financial data that can be used to ensure that clients capable of repayment are not rejected.**

In this tutorial, we show how [Featuretools](https://www.featuretools.com) can be used to perform feature engineering on a multi-table dataset of 300 thousand applicant financial information provided by Home Credit to train an accurate machine learning model to predict what if an applicant will repay a loan.

## Highlights

* We automatically generate 1820 features using Deep Feature Synthesis.
* We are able to generate features, check that we are content with those features, and create the feature matrix.
* We develop are able to generate features in 1 hour vs 10 hours with manual feature engineering.

## Running the tutorial
1. Clone the repo

    ```
    git clone https://github.com/bineshjose/NitcSoms
    ```

2. Install the requirements

    ```
    pip install -r requirements.txt
    ```
    
    *You will also need to install **graphviz** for this demo. Please install graphviz according to the instructions in the [Featuretools Documentation](https://docs.featuretools.com/getting_started/install.html)*

3. Download the data

    You can download the data from [Kaggle](https://www.kaggle.com/c/home-credit-default-risk/data). After downloading, save the CSV to a directory called `input` in the root of this repository.

4. Run the Tutorial notebook: <br>
[Automated Loan Repayment](https://github.com/Featuretools/Automated-Manual-Comparison/blob/master/Loan%20Repayment/notebooks/Automated%20Loan%20Repayment.ipynb)

    ```
    jupyter notebook
    ```

