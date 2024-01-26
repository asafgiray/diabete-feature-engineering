## TR
## Diyabet Hastalığı Tahmini

Bu proje, bir kişinin diyabet hastalığına sahip olup olmadığını tahmin etmek için bir makine öğrenmesi modeli geliştirmeyi amaçlamaktadır. Veri seti, ABD'nin Phoenix şehrinde yaşayan Pima Indian kadınları üzerinde yapılan diyabet araştırması için toplanmış verileri içermektedir. Bu veriler, hamilelik sayısı, glikoz, kan basıncı, cilt kalınlığı, insülin, vücut kitle indeksi, diyabet soy ağacı fonksiyonu, yaş gibi çeşitli özelliklerden oluşmaktadır. Hedef değişken, bir kişinin diyabet test sonucunun pozitif (1) veya negatif (0) olup olmadığını belirtir.

## Proje Adımları

### Keşifçi Veri Analizi (EDA)

1. **Genel Resim:** Veri setinin yapısını inceleme.
2. **Numerik ve Kategorik Değişkenlerin Yakalanması:** Veri setindeki numerik ve kategorik değişkenleri belirleme.
3. **Numerik ve Kategorik Değişkenlerin Analizi:** Değişkenlerin dağılımlarını, istatistiklerini ve özelliklerini inceleme.
4. **Hedef Değişken Analizi:** Kategorik değişkenlere göre hedef değişkenin ortalaması ve hedef değişkene göre numerik değişkenlerin ortalaması hakkında bilgi edinme.
5. **Aykırı Gözlem Analizi:** Aykırı değerleri belirleme ve işleme alma.
6. **Eksik Gözlem Analizi:** Eksik verileri tespit etme ve işleme alma.
7. **Korelasyon Analizi:** Değişkenler arasındaki ilişkileri inceleme.

### Özellik Mühendisliği

1. **Eksik ve Aykırı Değerlerin İşlenmesi:** Eksik ve aykırı değerleri belirleme ve işleme alma.
2. **Yeni Değişkenler Oluşturma:** Mevcut değişkenlerden yeni özellikler türetme.
3. **Encoding İşlemleri:** Kategorik değişkenlerin sayısal formata dönüştürülmesi.
4. **Numerik Değişkenler için Standartlaştırma:** Numerik değişkenlerin ölçeklendirilmesi.
5. **Model Oluşturma:** Makine öğrenimi modelinin geliştirilmesi.

## Kullanılan Kütüphaneler ve Araçlar

- Python
- pandas
- NumPy
- scikit-learn
- matplotlib
- seaborn

## Proje Sonuçları

Makine öğrenimi modeli kullanılarak geliştirilen Diyabet Hastalığı Tahmini projesi, veri analizi ve özellik mühendisliği adımlarını içermektedir. Proje sonuçlarına göre, geliştirilen modelin test veri setinde %79 doğruluk oranı elde ettiği görülmektedir. Ayrıca, modelin hatırlama (recall), hassasiyet (precision), F1 puanı ve AUC değerleri de başarılı sonuçlar göstermektedir.

---

Bu proje ile ilgili herhangi bir sorunuz veya geri bildiriminiz varsa, lütfen bizimle iletişime geçmekten çekinmeyin.

## ENG
## Diabetes Disease Prediction

This project aims to develop a machine learning model to predict whether a person has diabetes or not. The dataset contains data collected from Pima Indian women living in Phoenix, USA, as part of a diabetes research study. The data includes various features such as the number of pregnancies, glucose level, blood pressure, skin thickness, insulin, body mass index, diabetes pedigree function, age, etc. The target variable indicates whether a person's diabetes test result is positive (1) or negative (0).

## Project Steps

### Exploratory Data Analysis (EDA)

1. **General Overview:** Examine the structure of the dataset.
2. **Capturing Numerical and Categorical Variables:** Identify numerical and categorical variables in the dataset.
3. **Analysis of Numerical and Categorical Variables:** Examine the distributions, statistics, and characteristics of variables.
4. **Target Variable Analysis:** Understand the mean of the target variable by categorical variables and the mean of numerical variables by the target variable.
5. **Outlier Analysis:** Identify and handle outliers.
6. **Missing Value Analysis:** Detect and handle missing data.
7. **Correlation Analysis:** Explore relationships between variables.

### Feature Engineering

1. **Handling Missing and Outlier Values:** Detect and process missing and outlier values.
2. **Creating New Features:** Derive new features from existing variables.
3. **Encoding Operations:** Convert categorical variables into numerical format.
4. **Standardization for Numeric Variables:** Scale numeric variables.
5. **Model Building:** Develop machine learning models.

## Libraries and Tools Used

- Python
- pandas
- NumPy
- scikit-learn
- matplotlib
- seaborn

## Project Results

The Diabetes Disease Prediction project includes data analysis and feature engineering steps. According to the project results, the developed model achieved an accuracy rate of 79% on the test dataset. Additionally, the recall, precision, F1 score, and AUC values of the model also demonstrate successful performance.

---

If you have any questions or feedback regarding this project, please feel free to contact us.
