# Datasets Overview

## 1. Iris Dataset
This dataset contains measurements of iris flowers from three different species. Each sample is described by four numerical features.
## Features
- Sepal Length (cm) – Length of the sepal;
- Sepal Width (cm) – Width of the sepal;
- Petal Length (cm) – Length of the petal;
- Petal Width (cm) – Width of the petal.

**Target Classes**\
Each flower belongs to one of the following species:
- Iris Setosa
- Iris Versicolour
- Iris Virginica

### Dataset Source
[Iris Dataset](iris.csv)


## 2. Income Classification Dataset (Adult/Census Income)
This dataset is used to predict whether a person earns more than $50K per year based on various demographic and work-related attributes.

## Prediction Task
Classify individuals as earning <=50K or >50K.
### Features
- **age**: continuous;
- **workclass**: type of employment (e.g., Private, Self-emp, Government);
- **fnlwgt**: an estimate of the number of individuals in the population with the same demographics as single individual;
- **education**: highest level of education (e.g., Bachelors, HS-grad, Masters);
- **education-num**: numerical encoding of education level
marital-status: marital situation;
- **occupation**: type of job (e.g., Tech-support, Sales, Exec-managerial);
- **relationship**: relationship status within a household
race: e.g., White, Black;
- **sex**: Female or Male;
- **capital-gain**: continuous;
- **capital-loss**: continuous;
- **hours-per-week**: weekly working hours;
- **native-country**: country of origin;
- **salary**: target label (<=50K or >50K)

### Dataset Source
[Salary Dataset](salary.csv)

## 3. Fake News Detection Dataset
This dataset includes a collection of fake and real news articles used to train models for binary text classification.

## Prediction Task
Classify articles as fake or real.

## Features
- **title**: article headline;
- **text**: full article content;
- **subject**: news category or topic;
- **date**: publication date;

### Dataset Source
Copy and paste on Google Colab
```bash
import gdown
url = "https://drive.google.com/file/d/1kcODu96_hMF7GRNAJDfYPhGsSy-BGjtg/view?usp=drive_link"
gdown.download(url=url, fuzzy=True)
```

## 4. MRI Brain Tumor Dataset
A medical imaging dataset containing brain MRI scans categorized by tumor type. The images are organized into separate folders for training and testing.

## Prediction Task
Classify MRI scans into one of several tumor types.

Each of these folders contains four subfolders, corresponding to tumor classes such as:

- glioma_tumor;
- meningioma_tumor;
- pituitary_tumor;
- no_tumor.

The images are in standard formats (JPEG)

### Dataset Source
Copy and paste on Google Colab
```bash
import gdown
url = "https://drive.google.com/file/d/131473heJER2iO3D5pO0XjIquRegEh3Ib/view?usp=drive_link"
gdown.download(url=url, fuzzy=True)
```
