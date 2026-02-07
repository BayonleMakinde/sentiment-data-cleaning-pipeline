🌸 **Codveda – Task 1 | Python Data Analysis Intern**

**Social Media Sentiments: From Raw Text to Actionable Insights — A Data Story**

📊 **Python | Pandas | Data Preprocessing**

---
### 📌 Overview

Here’s the summary of the project: I used Pandas to clean 700+ sentiment records. I handled nulls/duplicates, normalized text for consistency, and transformed timestamps into datetime objects to engineer an 'Hour' feature for tracking peak engagement.

Instead of working with raw, noisy data, this script establishes a full analytical pipeline by connecting:
* User sentiment patterns
* Engagement metrics (Likes & Retweets)
* Temporal activity trends
* Global platform distribution

---
### ⚙️ Technical Workflow

1. **Data Auditing**: Initial inspection of 15 columns using `.info()` and `.isnull()`.
2. **Integrity Cleaning**: Automated removal of null values and duplicate records.
3. **Text Normalization**: Standardizing 'Sentiment' labels and converting 'Text' to lowercase.
4. **Time-Series Preparation**: Converting string timestamps to `datetime` objects.
5. **Feature Engineering**: Extracting 'Hour' from timestamps for engagement analysis.

---
### 🛠️ Tools & Libraries
* **Language:** Python 3.13
* **Libraries:** Pandas, NumPy
* **Environment:** Jupyter Notebook / VS Cod

  ---
  ![Alt Text](Screenshots/cleaned-data.png)
