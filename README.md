
## Election Dataset Analysis

This project analyzes the 2024 Indian Lok Sabha election results using Python and Jupyter Notebook. The dataset includes details about constituencies, candidates, parties, margins, and result statuses.

### Features
- Data loading and cleaning (handling missing values, correcting data issues)
- Exploratory data analysis (EDA) with summary statistics
- Insights into leading and trailing parties and candidates
- Data corrections for duplicate constituency names
- Aggregation of party-wise results
- **Data Visualization:**
	- Horizontal bar chart of leading party seat counts
	- Donut pie chart showing party-wise seat distribution
	- Histogram of victory margins
	- Bar chart of top 10 candidates by victory margin

### How to Run
1. Open `main.ipynb` in Jupyter Notebook or VS Code.
2. Run the cells sequentially to load the data, perform analysis, and view the visualizations.

### Requirements
- Python 3.x
- pandas
- numpy
- matplotlib

Install dependencies using:
```bash
pip install -r requirement.txt
```

### Dataset
- `election_results_2024.csv`: Contains the election results data.

### Visualizations
The notebook generates:
- A horizontal bar chart showing the number of seats won by each leading party (with minor parties grouped as "Others").
- A donut pie chart for party-wise seat distribution.
- A histogram showing the distribution of victory margins across constituencies.
- A bar chart of the top 10 candidates with the highest victory margins.

### Observations
- BJP is the leading party with control over 240 constituencies.
- INC is trailing in 167 constituencies.
- Margin is unique for each constituency, with 329,991 as the highest.
- Results have been declared for 542 out of 543 constituencies.

---

Feel free to explore and modify the notebook for deeper insights!
