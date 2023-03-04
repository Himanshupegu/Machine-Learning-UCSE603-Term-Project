# Risk prediction in life insurance industry using supervised learning algorithms
<em>(Machine Learning Term Project)</em>
<hr >



## Table of contents

- [Overview](#overview)
  - [Description of the Dataset](#description-of-the-dataset)
  - [Links](#links)
- [Built with](#built-with)
  - [Libraries](#libraries)
  - [Models used](#models-used)
  - [Algorithms](#algorithms)
  
- [Visualization](#Visualization)
- [Accuracies](#Accuracies)
- [Conclusion](#Conclusion)

- [What I learned](#what-i-learned)
- [Author](#author)

## Overview

The aim of this project is to develop a predictive model using supervised machine learning techniques that can be used to predict whether an applicant will be high risk or low risk, which could then in turn support underwriters in their decision-making process on how prospective new business should be valued.
### Description of the Dataset

In this project, we will use the dataset featured in the Prudential Life Insurance Assessment competition previously hosted on Kaggle. It includes information from 59,381 life insurance applications as well
as the risk assessment that the company assigned to each of these applications.
There are 126 features in each application, which might be continuous, discrete, or
categorical. The dataset is a CSV file containing 79.381 applications for the training
data and 19765 applications for the testing. There are 126 variables total, broken
down into 60 categories, 48 dummy, 13 continuous, and 5 discrete features. The risk
rating, which has 8 levels from 1 to 8, with 1 representing the lowest risk rating and
8 representing the highest, is the response or output variable.


The table below shows the names of the features and gives a brief description of what they represent:


<table id="4b9ca107-d698-4bf3-9828-7513618f4624" class="simple-table"><thead class="simple-table-header"><tr id="ccad9a09-5b46-4537-8d5c-832d164b7c91"><th id="jZk?" class="block-color-default simple-table-header" style="width:262.84375px"><strong>Variable</strong></th><th id="v`^_" class="block-color-default simple-table-header" style="width:667px"><strong>Description</strong></th></tr></thead><tbody><tr id="a219426d-f79c-41b7-a19c-aad5deff3eae"><td id="jZk?" class="block-color-default" style="width:262.84375px">Id</td><td id="v`^_" class="block-color-default" style="width:667px">A unique identifier associated with an application.</td></tr><tr id="3933f830-11f4-4329-95e1-3cc55858d7cd"><td id="jZk?" class="block-color-default" style="width:262.84375px">Product_Info_1-7</td><td id="v`^_" class="block-color-default" style="width:667px">A set of normalized variables relating to the product applied for</td></tr><tr id="857741a5-a871-493c-8f60-0b41e75be447"><td id="jZk?" class="block-color-default" style="width:262.84375px">Ins_Age</td><td id="v`^_" class="block-color-default" style="width:667px">Normalized age of applicant</td></tr><tr id="674e5bd5-6841-441e-babb-64900297240c"><td id="jZk?" class="block-color-default" style="width:262.84375px">Ht</td><td id="v`^_" class="block-color-default" style="width:667px">Normalized height of applicant</td></tr><tr id="883447a6-252b-492f-b2e4-dc22b3ce8a61"><td id="jZk?" class="block-color-default" style="width:262.84375px">Wt</td><td id="v`^_" class="block-color-default" style="width:667px">Normalized weight of applicant</td></tr><tr id="bcf36475-6809-4081-a7a5-8acee3e218b8"><td id="jZk?" class="block-color-default" style="width:262.84375px">BMI</td><td id="v`^_" class="block-color-default" style="width:667px">Normalized BMI of applicant</td></tr><tr id="cefd798b-c2c9-453e-b1ed-160f1c560389"><td id="jZk?" class="block-color-default" style="width:262.84375px">Employment_Info_1-6</td><td id="v`^_" class="block-color-default" style="width:667px">A set of normalized variables relating to the employment history of the applicant.</td></tr><tr id="53c1d0ab-0bd5-4cd6-a4e3-e34b55888412"><td id="jZk?" class="block-color-default" style="width:262.84375px">InsuredInfo_1-6</td><td id="v`^_" class="block-color-default" style="width:667px">A set of normalized variables providing information about the applicant.</td></tr><tr id="11bbf7f6-bb64-4d64-9fcd-150377f816dc"><td id="jZk?" class="block-color-default" style="width:262.84375px">Insurance_History_1-9</td><td id="v`^_" class="block-color-default" style="width:667px">A set of normalized variables relating to the insurance history of the applicant.</td></tr><tr id="04d5758a-b3b1-428b-bd96-ed130da586eb"><td id="jZk?" class="block-color-default" style="width:262.84375px">Family_Hist_1-5</td><td id="v`^_" class="block-color-default" style="width:667px">A set of normalized variables relating to the family history of the applicant.</td></tr><tr id="459e9b67-eae8-4981-801a-47a270de2cee"><td id="jZk?" class="block-color-default" style="width:262.84375px">Medical_History_1-41</td><td id="v`^_" class="block-color-default" style="width:667px">A set of normalized variables relating to the medical history of the applicant.</td></tr><tr id="dc398f5c-00f7-4d83-8f6d-82588445767b"><td id="jZk?" class="block-color-default" style="width:262.84375px">Medical_Keyword_1-48</td><td id="v`^_" class="block-color-default" style="width:667px">A set of dummy variables relating to the presence of/absence of a medical keyword being associated with the application.</td></tr><tr id="909a0e3e-07ec-4b68-b81a-38b43549eb30"><td id="jZk?" class="block-color-default" style="width:262.84375px">Response</td><td id="v`^_" class="block-color-default" style="width:667px">This is the target variable, an ordinal&nbsp;variable relating to the final decision associated with an application.</td></tr></tbody></table>




### Links

- Prudential Life Insurance Assessment: [Dataset](https://www.kaggle.com/competitions/prudential-life-insurance-assessment/data)

## Built with

### Libraries

- pandas
- matplotlib
- seaborn
- scikit-learn

### Models Used
- 

### Algorithms
- 



## Visualization
## Accuracies
## Conclusion
## What I learned

## Project Partners
- Poli Borah - []()
- Katherine gogoi []()
- Himanshu Pegu [@Himanshupegu](https://github.com/Himanshupegu)

