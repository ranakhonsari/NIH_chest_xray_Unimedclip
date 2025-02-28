# **NIH Chest X-ray Classification with UniMedCLIP**  

This repository applies **UniMedCLIP** as a classifier on a sample subset of the **NIH Chest X-ray** dataset from Kaggle. The results are analyzed and visualized using **SQL** and **Google Looker Studio**.  

## **Project Overview**  
- The main focus of this project **is not model performance**. Instead, it demonstrates how to:  
  - Use **UniMedCLIP** for **chest X-ray classification**.  
  - Store predictions in a **PostgreSQL** database.  
  - Visualize results using **Looker Studio**.  
- A **pretrained UniMedCLIP checkpoint** is used.  
- For better performance, you can:  
  - **Fine-tune the model** on the dataset.  
  - **Replace UniMedCLIP** with another model.  

---

## **Dataset & Model**  
- **NIH Chest X-ray (Sample)**: [Kaggle Dataset](https://www.kaggle.com/datasets/nih-chest-xrays/sample)  
- **UniMedCLIP**: [GitHub Repository](https://github.com/mbzuai-oryx/UniMed-CLIP)  

---

## **Setting Up Looker Studio with NeonDB**  
To visualize data in **Looker Studio**, you need to connect your **Neon PostgreSQL database**. Follow these guides:  
- **Step-by-step connection guide**: [Medium Article](https://medium.com/@santosobudi.aris/building-dynamic-dashboards-a-step-by-step-guide-using-looker-studio-and-neon-cloud-postgresql-d43ebdeadef8)  
- **NeonDB connection details**: [Official Docs](https://neon.tech/docs/connect/connect-postgres-gui)  

---

## **How to Use This Repo**  
1. **Run the colab notebook**: This would connect to the neonDB, perform inference, and store predictions in PostgreSQL (NeonDB).  
2. **Connect Looker Studio** to NeonDB for data visualization.  

---

## **Project Report** 📄  
For a detailed analysis and results, check out the **full report**:  
[📑 View Report (PDF)](./chest_xray_report.pdf)
