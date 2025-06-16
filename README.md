# 🎓 University Admission Predictor

This project uses **Linear Regression** to predict a student's **chance of admission** to a university based on academic factors like GRE, TOEFL, CGPA, and research experience.

---

## 📊 Dataset Overview

The dataset contains the following features:

- **GRE_Score**: Graduate Record Exam score (out of 340)
- **TOEFL_Score**: Test of English as a Foreign Language score (out of 120)
- **University_Rating**: Rating of the university (1 to 5)
- **SOP**: Statement of Purpose strength (1 to 5)
- **LOR**: Letter of Recommendation strength (1 to 5)
- **CGPA**: Undergraduate GPA (out of 10)
- **Research**: Research experience (0 or 1)
- **Chance_of_Admission**: Target variable (value between 0 and 1)

---

## ⚙️ Technologies Used

- Python 3.x
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## 📌 Project Structure

```bash
.
├── university_admission.csv        # Dataset
├── admission_predictor.py         # Main script
└── README.md                      # Project documentation
