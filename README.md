# Accesing Data from Program Code - Project 02 

This project collects, processes, and visualizes **oncological gene expression datasets** from **The Cancer Genome Atlas (TCGA)**. It scrapes data from the **Xena Browser**, stores it in a **MiniO bucket**, and merges it with **clinical survival data** for further analysis.

---

## **Features**
- **Scrapes Gene Expression Data** from the Xena Browser.
- **Stores Data in MiniO Cloud Storage** (Non-Structured Storage).
- **Processes and Filters** the gene expression dataset for the **cGAS-STING gene pathway**.
- **Merges Gene Expression Data with Clinical Survival Data** (TCGA Clinical Data).
- **Stores Results in a MongoDB Database** for easy querying.
- **Exports Processed Data** to a `.txt` file for further analysis.
