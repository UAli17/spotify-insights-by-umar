# 🎧 Spotify Data Analysis – Umar Ali

This project demonstrates how to extract, transform, analyze, and visualize Spotify playlist data using modern data engineering tools. Built in Azure Databricks with PySpark and SparkSQL, the data pipeline leverages the Spotify Web API to extract track metadata and audio features, which are then transformed and stored as Delta Tables. Insights are visualized in Power BI to uncover patterns in music behavior and preferences.

---

## 📌 Key Features

- 🔌 **Spotify API Integration** – Extracts playlist, track, album, and audio feature data
- 🧹 **ETL Pipeline in Databricks** – PySpark, SparkSQL, and Delta Lake for transformation
- 📊 **Interactive Visualizations** – Power BI dashboards with multi-layered insights
- 🧠 **Analytical Outputs**:
  - Top 5 longest albums
  - Album popularity distribution
  - Energy level classification
  - Tracks per musical key
  - Track recommendations

---

## ⚙️ Tech Stack

| Layer         | Tools/Services                     |
|---------------|------------------------------------|
| API           | Spotify Web API                    |
| Data Platform | Azure Databricks (PySpark, SparkSQL)|
| Storage       | Delta Tables                       |
| Visualization | Power BI                           |
| Language      | Python                             |
| Version Control | Git & GitHub                    |

---

## 🧪 Getting Started

### ✅ Prerequisites

- Azure Databricks account
- Spotify Developer account
- Power BI Desktop
- Python 3.x
- Required packages: `requests`, `pyspark`, `json`

---

### 🔧 Installation & Setup

1. **Clone the Repository**
```bash
git clone https://github.com/UAli17/spotify-insights-by-umar.git
cd spotify-insights-by-umar

2. **Install Python Dependencies**
pip install -r requirements.txt

3. **Get Spotify Credentials**
Go to the Spotify Developer Dashboard
Create an app to get your:
CLIENT_ID
CLIENT_SECRET

4. **Configure Secrets in Databricks**
Use Databricks Secret Scopes:
SPOTIFY_CLIENT_ID=your_client_id
SPOTIFY_CLIENT_SECRET=your_client_secret

5. **Upload and Run the notebook**
Open spotify-data-analysis.ipynb inside /src/ in Databricks
Replace the default playlist ID with your own
Run the notebook to generate data tables

📊 Power BI Dashboard
The final results are visualized in Power BI. The report includes:

🎵 Top 5 Longest Albums – by total track duration

📈 Album Popularity – based on Spotify’s popularity score

⚡ Energy Distribution – categorized into energetic levels

🎹 Tracks per Audio Key – musical key frequency

🤖 Recommended Tracks – generated using the Spotify recommendation API

👤 About the Author
Umar Ali
Data Engineer | Python & SQL | Analytics & Automation
🔗 LinkedIn • 📫 U_ali17@outlook.com
