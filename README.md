# Heart Failure Prediction

In this notebook, we aim to predict heart failure using a dataset containing various clinical features. Heart disease is one of the leading causes of death worldwide, and early prediction can help in taking preventive measures. We will explore the dataset, preprocess it, build a machine-learning model, and evaluate its performance.

![Heart Failure Prediction](https://media.licdn.com/dms/image/C4D12AQG6uYy-OXdhVg/article-cover_image-shrink_600_2000/0/1573170080567?e=2147483647&v=beta&t=evLlzd_oOwrJKeBkQAXGPiJNAPeW4CxvI3MUBIaAe6A)


## Attribute Information

- **👤 Age:** Age of the patient [years]

- **🔘 Sex:** Sex of the patient [M: Male, F: Female]

- **💓 ChestPainType:** Type of chest pain

  - TA: Typical Angina
  - ATA: Atypical Angina
  - NAP: Non-Anginal Pain
  - ASY: Asymptomatic

- **💉 RestingBP:** Resting blood pressure [mm Hg]

- **🩺 Cholesterol:** Serum cholesterol level [mg/dl]

- **🍬 FastingBS:** Fasting blood sugar

  - 1: If FastingBS > 120 mg/dl
  - 0: Otherwise

- **📉 RestingECG:** Resting electrocardiogram results

  - Normal: Normal
  - ST: ST-T wave abnormality
  - LVH: Left ventricular hypertrophy by Estes' criteria

- **❤️‍🔥 MaxHR:** Maximum heart rate achieved [Numeric value between 60 and 202]

- **🚴‍♂️ ExerciseAngina:** Exercise-induced angina

  - Y: Yes
  - N: No

- **📏 Oldpeak:** ST depression value [Numeric value measured in depression]

- **📈 ST_Slope:** Slope of the peak exercise ST segment

  - Up: Upsloping
  - Flat: Flat
  - Down: Downsloping

- **🫀 HeartDisease:** Output class
  - 1: Heart disease
  - 0: Normal

**Cholesterol**

- Cholesterol is good less than 200
- Cholesterol is BORDERLINE HIGH 200 --> 239
- Cholesterol is HIGH 240 and higher

## Observations

- **For Fasting blood sugar:-**

  - **Most** people in the data **fastingBS < 120 mg/dl**,
  - **Few** people in the data **fastingBS > 120 mg/dl**

  - Most of the patients in the data are **males**
  - The number of **healthy women** is more than **patients** in the data

- **order of the type of chest pain on the disease:-**

  1- **ASY**

  2- **NAP**

  3- **ATA**

  4- **TA**

- **No Exercise Angina:-**
  - The number of **healthy** people is **more** than the number of **patients**
- **Yes Exercise Angina:-**

  - The number of **patients** is **more** than the number of **healthy** people

- **order of the slope of the peak exercise on the disease:-**

  1- **Flat**

  2- **Up**

  3- **Down**

---


## 📣 Feedback


If you have any feedback, please reach out to us at mahmoud3laa2210@gmail.com

## 🔗 You can follow me on

[![portfolio](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MahmoudAlaa22)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mahmoudalaa2210/)
[![linkedin](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white)](https://www.kaggle.com/mahmoudalaa22210)
