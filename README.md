# 📊 Tracking Maternal Health Progress Toward SDG 3.1

This project uses machine learning, specifically IBM Watsonx.ai's AutoAI, to classify maternal health indicators into relevant **Sustainable Development Goals (SDGs)** — primarily targeting **SDG 3.1**, which aims to reduce the global maternal mortality ratio.

---

## 🚀 Objective

To predict SDG goals based on health and welfare indicators from the Government of India’s SDG dataset, thereby supporting data-driven public health policy and resource allocation.

---

## 🧠 Model Overview

- **Tool Used**: IBM Watsonx.ai AutoAI
- **Best Model**: Extra Trees Classifier (selected via AutoAI)
- **Deployment**: IBM Cloud Watson Machine Learning (WML) as REST API
- **API Endpoint**:  
  `https://au-syd.ml.cloud.ibm.com/ml/v4/deployments/acd8e673-34ef-4fa9-bfb4-21e6283bb7f7/predictions?version=2021-05-01`

---

## 🗂 Dataset

- **Source**: [data.gov.in – National Indicator Framework v3.1](https://data.gov.in)
- **Type**: Tabular dataset with indicators like:
  - Antenatal Care Coverage
  - Adolescent Birth Rate
  - Skilled Birth Attendance
  - Healthcare Expenditure
  - ICDS Beneficiaries


---

## ⚙️ How to Use the API

1. Replace your API key in the script
2. Use the provided payload format
3. Run the request using Python (`requests` module)

📂 Sample code: `api_inference/score_model.py`

---

## 📸 Sample Output

- Model prediction:  
  `1.3: Implement nationally appropriate social protection systems`

- Confidence:  
  `100%`

---

## 📈 Evaluation

- Automatically evaluated using Watson AutoAI
- Metrics: Accuracy, F1-Score (via cross-validation)
- Prediction results aligned well with real-world indicator mapping

---

## 📌 Tools & Libraries

- IBM Watsonx.ai
- IBM Watson ML Deployment
- Google Colab
- Python:requests,json,pandas,sklearn,numpy

---

## 🌍 Future Scope

- Add global datasets and real-time public health streams
- Develop dashboards for government integration
- Implement LLM/NLP models to auto-tag indicators from text

---

## 📚 References

- [data.gov.in](https://data.gov.in)
- [IBM Cloud Docs](https://cloud.ibm.com/docs)
- [WHO Maternal Health](https://www.who.int/data)
- [scikit-learn.org](https://scikit-learn.org)

---

## 🪪 License

MIT License (Add `LICENSE` file if applicable)

---



## 🏗 Project Structure

