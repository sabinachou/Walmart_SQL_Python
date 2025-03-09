# 🛒 Walmart Data Analysis: End-to-End SQL + Python Project P-9  

## 📌 Project Overview  
This project is an **end-to-end data analysis solution** designed to extract **critical business insights** from **Walmart sales data**.  
We leverage:  
✔️ **Python** for data processing and analysis  
✔️ **SQL (MySQL & PostgreSQL)** for advanced querying  
✔️ **Structured problem-solving** techniques to analyze key business metrics  

This project is ideal for **data analysts** looking to develop skills in:  
✔️ **Data manipulation**  
✔️ **SQL querying**  
✔️ **Building data pipelines**  

---

## 🔥 Project Pipeline  

### 1️⃣ Set Up the Environment  
📌 **Tools Used**: Visual Studio Code (VS Code), Python, SQL (MySQL and PostgreSQL)  
📌 **Goal**: Create a **structured workspace** within VS Code and organize project folders for smooth development.  

### 2️⃣ Set Up Kaggle API  
📌 **API Setup**: Obtain your Kaggle API token from [Kaggle](https://www.kaggle.com/) by navigating to **Profile Settings** → **Download JSON file**.  
📌 **Configure Kaggle**:  
```bash
mkdir ~/.kaggle
mv kaggle.json ~/.kaggle/
chmod 600 ~/.kaggle/kaggle.json

### 3️⃣ Download Walmart Sales Data  

📌 **Data Source**: Use Kaggle API to download the **Walmart sales dataset**.  

📌 **Dataset Link**: [Walmart Sales Dataset](https://www.kaggle.com/)  

📌 **Storage**: Save the data in the `data/` folder.  

#### 📥 Download Data Using Kaggle API  
```bash
# Ensure Kaggle API is set up
mkdir -p ~/.kaggle
mv kaggle.json ~/.kaggle/
chmod 600 ~/.kaggle/kaggle.json

# Download Walmart sales dataset
kaggle datasets download -d <dataset-path> -p data/ --unzip
