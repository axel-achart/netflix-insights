# Netflix Insights Project (Data Analysis)

## 🧠 AI Focus & Methods

**Artificial Intelligence:** Branch of computer science enabling machines to perform tasks associated with human intelligence, including learning, reasoning, problem solving, natural language understanding, and decision-making.

**Machine Learning:** A subset of AI, it empowers machines to "learn" from data via mathematical models.

**Data Preprocessing:** The step where raw data is cleaned and structured to prepare for analysis.

**Descriptive Data Analysis:** Summarizes data using simple tables and mathematical indicators such as mean, range, etc.

---

## 🌍 Chosen Domain: Healthcare

AI applications in healthcare include:
- Detecting medical anomalies automatically from images (e.g., tumors, malformations)
- Predicting disease progression based on historical data
- Optimizing care by analyzing medical records to suggest best treatments
- Managing hospital flow by forecasting spikes in patient arrivals

**Real-world example:** A hospital could use machine learning to predict ER patient arrivals daily, taking into account seasons, local events, and more.

---

## 📦 Context & Data Used

This project forms part of a training program in AI and data science. The objective is to introduce foundational concepts of data analysis by examining a real-world case: the **Netflix catalogue analysis**.

**Dual goals:**
1. **Conduct an AI Watch:** Pin down the following key concepts—
   - Artificial intelligence
   - Machine learning
   - Data preprocessing
   - Descriptive data analysis
2. **Apply these concepts:** Analyze actual data using Python and Jupyter Notebook.

### 🗂️ Data Format

- File: `netflix_titles.csv` (~8,800 entries, 12 columns)
- Contains both qualitative and quantitative fields

### 🔍 Column Descriptions

| Column        | Description                         |
|---------------|-------------------------------------|
| `show_id`     | Unique identifier                   |
| `type`        | Movie or TV Show                    |
| `title`       | Title of the work                   |
| `director`    | Director                            |
| `cast`        | Main actors                         |
| `country`     | Country of origin                   |
| `date_added`  | Date added to Netflix               |
| `release_year`| Release year                        |
| `rating`      | Classification (PG, TV-MA, etc.)    |
| `duration`    | Duration (minutes or seasons)       |
| `listed_in`   | Genres or categories                |
| `description` | Brief content summary               |

---

## 📈 Observations & Findings

### 📊 Content Type Breakdown

- Most entries are **movies**, with a strong but growing presence of **TV series**.
- Historically, Netflix focused on films but is now investing more in original series.

### 📅 Release Year Distribution

- Most entries date from **2010 to 2021**.
- Very few works released prior to 2000.
- Indicates a strong emphasis on recent content.

### 🗓️ Date Added to Netflix

- **2019, 2020, and 2021** saw surges in content added.
- Reflects Netflix’s worldwide expansion and increased output of original productions.

### ⏱️ Work duration

- **Movies:** Most run between **80-120 minutes**.
- **Series:** Most have **1 to 3 seasons**.

### 🎭 Genre Breakdown

- Common genres include:
  - Dramas
  - Comedies
  - International TV Shows
  - Documentaries
- Netflix’s catalogue is highly diversified, with a focus on international content and factual programming.

---

## 🧠 Takeaways

Analyzing Netflix’s catalogue highlights how data science can:
- Clarify content offerings and user trends
- Reveal production and distribution patterns
- Demonstrate the critical nature of **pre-processing**, **descriptive analysis**, and **visualization** in any data project

🎯 **This project serves as a gateway to applying artificial intelligence in a real domain: entertainment.**
