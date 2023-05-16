# Machine-Learning-7126
 This is a repository about HKU-ECOM7126

## Assignment 1 – Insurance Claims Prediction

Wing On Insurance is a medium size insurance company in Hong Kong wanting to use machine learning to predict health insurance claims using past claim data the company has collected over the past few years.

The dataset consists of 1,320 cases, in .csv format and the following data dictionary:

![pic 1](https://github.com/seanxu-k/Machine-Learning-7126/blob/main/images/readme/image-20230313224245983.png)


Note: NT = New Territory

### Deliverable:

1. A report in PDF format.

2. The Colab notebook (Python programs with comments and notes) that you use to produce your results in .ipynb (Colab notebook format).

**You should include the following in your report:**

1. An account of what you have done in investigating and transforming your data and why.

2. Use Linear Regression to build a prediction engine. (Hint: You may not need to include all features in the dataset. Justify your decision.) DO NOT use other models for this assignment.

3. Any observation you may have in your project to the management of the company.

**Datasets provided: InsuranceDataset.csv**



## Assignment 2 – Diamond Classification

Diamond is one of the most valued gem stones in the world. The quality of a diamond is often graded according to what is well-known as the 4Cs: Carat, Cut, Colour and Clarity. There are also other objective and physical attributes, especially those that relates to the dimensions of the diamond. You are asked by your company to build a classification engine to classify any diamond into three classes: Low, Mid and High, based on data accumulated of grading by experts over the years. The ML classification engine will be used by newly trained gem expert to assist them in their job.

The dataset consists of 10,000 diamonds over various characteristics, in .csv format and the following data dictionary:

carat cut colour clarity

length, width

height depth ratio table

weight of the diamond (1 carat = 0.2 g) quality of the cut rated by experts (Fair, Good, Very Good, Premium, Ideal) rated from D (best) to J (worst) for our dataset a measure of how clear the diamond is as defined by GIA Clarity Chart ((I1 (worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (best) – see later the widest orthogonal dimensions looking from the top (also called x, y in mm. for round diamond, it is also called diameter and x = y) the height (also called depth z in mm) of the diamond depth percentage = height / mean (length, width) = 2 * z / (x + y) in % percentage of width of the top facet of the diamond to the width

(Note: GIA = Gemological Institute of America, an institute that define many standards for assessing diamond)

To learn more about the above parameters of a diamond, you are encouraged to visit the following website: https://www.diamonds.pro/education. The following information may also be helpful:

![pic 2](https://github.com/seanxu-k/Machine-Learning-7126/blob/main/images/readme/image-20230313224427650.png)

### Deliverable:

1. Design and implement a ML model to classify any new diamond in the three categories (Low, Mid and High grade).

2. A report in PDF format.

3. The Colab notebook (Python programs with comments and notes) that you use to produce your results in .ipynb (Colab notebook) format.

**You should include the following in your report:**

1. An account of what you have done in investigating and transforming your data and why.

2. Use Classification models you have learned so far to build a classification engine as specified.

3. Any observation you may have in your project to the management of the company.

**Datasets provided: DiamondDataset.csv**

## Assignment 3 - Customer Analysis (Unsupervised Learning)

A small e-commerce company want to understand its customers better using Machine Learning to target their loyalty program and promotion campaigns etc. Analyze the dataset provided (which is purposely kept small for exploration purpose).

### Deliverable:
You should include the following in your report (plus your Colab notebook with you Python code to get the results):

1. How you tackle the dataset and what you want to find out.

2. Analyze the data to achieve your objective and write a report to the management.

3. Discuss what you have learned from the data, try to make appropriate recommendation(s) to the management.

**Dataset provided: CustomerDataset.csv**

## Assignment 4 – Spam Email Prediction using Neural Network

A cyber security company wishes to develop a SPAM filter based Artificial Neural Network. A sample of 4,600 emails are collected within a certain period randomly from the company’s email server, and 48 of words, 6 characters (or symbols) and other features are randomly picked from these email samples as input to train the Neural Network. The emails are then carefully labeled as SPAM or HAM (not spam). Your job is to build a Neural Network based spam filter and demonstrate the quality of your model.

The dataset consists of 4,600 of labelled instances, in .csv format. The dataset is already randomized and the first 3,600 samples are for training, and the remaining 1,000 samples are for testing.

### Deliverable:
You should include the following in your report (plus your Colab notebook with you Python code to get the results):

1. Examine and understanding the feature set provided and handle any issues, if any, in the dataset.

2. Design a multi-layer neural network, train the network with the appropriate validation, then test your final model. You may wish to tune your model if time permits.

3. As a stretched goal (optional), try an ML model which is not a neural network and compare.

4. Discuss what you have learned from this assignment and discuss how you may build a better email spam filter.

**Dataset provided: SpamDataset.csv**
