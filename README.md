[EN]
# Titanic Survival Prediction with Deep Learning

This project aims to predict the survival of passengers aboard the Titanic using a deep learning model. The dataset used in this project is sourced from Kaggle's Titanic dataset.

## Project Overview

The Titanic dataset contains information about the passengers who were aboard the Titanic. The goal of this project is to develop a deep learning model that can accurately predict which passengers survived the disaster.

## Data Dictionary

- **survival**: Survival status (0 = No, 1 = Yes)
- **pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **sex**: Gender of the passenger
- **age**: Age of the passenger (in years)
- **sibsp**: Number of siblings/spouses aboard the Titanic
- **parch**: Number of parents/children aboard the Titanic
- **ticket**: Ticket number
- **fare**: Passenger fare
- **cabin**: Cabin number
- **embarked**: Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)

## Dataset

The dataset can be downloaded from [Kaggle's Titanic Dataset](https://www.kaggle.com/c/titanic/data).

## Project Workflow

1. **Data Import and Exploration:** 
   - Importing the dataset and understanding the data structure.
   - Checking for missing values and performing exploratory data analysis (EDA).

2. **Data Preprocessing:**
   - Handling missing values for 'Age', 'Fare', 'Cabin', and 'Embarked' columns.
   - Encoding categorical variables and feature scaling.
   - Engineering new features such as 'FamilySize', 'Ticket_Length', and 'Cabin_Number'.

3. **Model Development:**
   - Building a deep learning model using TensorFlow and Keras.
   - Training the model on the training dataset and evaluating its performance.

4. **Model Evaluation:**
   - Evaluating model accuracy and loss using validation data.
   - Fine-tuning the model parameters to improve performance.

## Results

**Data Loading and Processing:** The Titanic dataset was preprocessed to handle missing data and transform categorical variables.

**Model Creation:** A deep learning model was built and trained using TensorFlow and Keras.

**Model Training and Evaluation:** The model was trained and evaluated using training and test datasets. After completing the training, the model's performance on the validation dataset was assessed, showing an accuracy of 90%. This accuracy represents a significant improvement compared to the results obtained using simple machine learning algorithms.

## Notes

This project is a continuation of the Titanic Survival Prediction project, which addressed the same problem using machine learning. It aims to test the applicability and performance of deep learning techniques.
The dataset and code used in this project are shared as open source and are open for further development and contributions.

[TR]

# Titanic Survival Prediction with Deep Learning

Bu proje, Titanic yolcularının hayatta kalma durumlarını derin öğrenme modeli kullanarak tahmin etmeyi amaçlamaktadır. Projede Kaggle'ın Titanic veri seti kullanılmıştır.

---

## Proje Genel Bakış

Titanic veri seti, Titanic'te bulunan yolcular hakkında bilgi içermektedir. Bu projenin amacı, bir derin öğrenme modeli geliştirerek yolcuların bu felaketten hayatta kalıp kalamayacağını doğru bir şekilde tahmin etmektir.

---

## Veri Sözlüğü

- **survival**: Hayatta kalma durumu (0 = Hayır, 1 = Evet)
- **pclass**: Bilet sınıfı (1 = 1. sınıf, 2 = 2. sınıf, 3 = 3. sınıf)
- **sex**: Yolcunun cinsiyeti
- **age**: Yolcunun yaşı (yıl cinsinden)
- **sibsp**: Titanic'teki kardeş/eş sayısı
- **parch**: Titanic'teki ebeveyn/çocuk sayısı
- **ticket**: Bilet numarası
- **fare**: Yolcu ücreti
- **cabin**: Kabin numarası
- **embarked**: Gemiye biniş limanı (C = Cherbourg; Q = Queenstown; S = Southampton)

---

## Veri Seti

Veri setine [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data) bağlantısından ulaşabilirsiniz.

---

## Proje Akışı

1. **Veri Yükleme ve Keşifsel Analiz:**
   - Veri setini yükleyerek yapısını anlamak.
   - Eksik verileri kontrol etmek ve keşifsel veri analizi (EDA) yapmak.

2. **Veri Ön İşleme:**
   - 'Age', 'Fare', 'Cabin' ve 'Embarked' sütunlarındaki eksik verileri doldurmak.
   - Kategorik değişkenleri kodlama ve özellikleri ölçeklendirme.
   - `FamilySize`, `Ticket_Length`, ve `Cabin_Number` gibi yeni özellikler oluşturmak.

3. **Model Geliştirme:**
   - TensorFlow ve Keras kullanarak bir derin öğrenme modeli oluşturmak.
   - Modeli eğitim verileri üzerinde eğitmek ve performansını değerlendirmek.

4. **Model Değerlendirme:**
   - Doğruluk ve kayıp metriklerini kullanarak model performansını değerlendirmek.
   - Model parametrelerini ince ayarlayarak performansı artırmak.

---

## Sonuçlar

- **Veri İşleme:** Titanic veri seti, eksik veriler temizlenerek ve kategorik değişkenler dönüştürülerek hazırlandı.
- **Model Oluşturma:** TensorFlow ve Keras ile bir derin öğrenme modeli oluşturuldu ve eğitildi.
- **Model Performansı:** Eğitim ve test veri setleri üzerinde modelin performansı değerlendirildi. Model, doğrulama veri setinde %90 doğruluk oranına ulaştı. Bu sonuç, basit makine öğrenimi algoritmalarına kıyasla önemli bir iyileşme göstermektedir.

---

## Notlar

Bu proje, Titanic Survival Prediction projesinin bir devamıdır. Bu çalışmada makine öğrenimi yerine derin öğrenme yöntemlerinin uygulanabilirliği ve performansı test edilmiştir. Veri seti ve projede kullanılan kod açık kaynak olarak paylaşılmıştır ve geliştirmelere açıktır.
