# 🔀 Parallel DAG Example in Airflow

This project demonstrates how to define and execute parallel tasks in **Apache Airflow** using the **BashOperator**.  
It simulates a basic ETL flow where tasks run in parallel and later converge, highlighting how Airflow handles task dependencies and branching.

---

## 🚀 What This Project Does

1. **Extracts** data in parallel using two separate tasks  
2. **Loads** the extracted data in parallel  
3. **Transforms** the data after both load tasks are completed  

The tasks are simulated using `sleep` commands for simplicity.

---

## 🛠️ Tech Stack

- **Apache Airflow**
- **Python**
- **Docker + Docker Compose**
- **BashOperator**

---

## 📸 Output Screenshots

*Here are some screenshots showcasing the key outputs and results from running the pipeline.*
![image](https://github.com/user-attachments/assets/d099d8d9-18fd-4fdd-a58e-43d0b0c6f667)


---

## 📚 Acknowledgment

This DAG is based on a practice example from the Udemy course:  
**[The Complete Hands-On Course to Master Apache Airflow](https://www.udemy.com/course/the-complete-hands-on-course-to-master-apache-airflow/)** by *Marc Lamberti*.  
The structure has been recreated and documented here for personal learning and hands-on reinforcement.
