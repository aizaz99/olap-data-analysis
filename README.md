📊 OLAP Operations in Python with Pandas
This project demonstrates the use of OLAP (Online Analytical Processing) operations—slice, dice, roll-up, drill-down, and pivoting—using Python and Pandas on a sample sales dataset.

📝 Project Overview
We analyze a sales dataset using Pandas to perform:

Slice: Filter records by region

Dice: Filter records by multiple conditions (region & category)

Roll-up: Aggregate total sales by region

Drill-down: Aggregate total sales by region and month

Pivot Table: Create an OLAP-style pivot table showing total sales by region and month (including row/column totals)

Each operation includes printed outputs and short explanations.

📁 Dataset
The dataset is a small CSV file containing 12 sales records with the following columns:


OrderID	Region	Product	Category	Month	Sales	Quantity
Example rows:

python-repl
Copy
Edit
1001,North,Laptop,Electronics,January,1200,2
1002,North,Phone,Electronics,January,800,5
...
Stored as data_sales.csv.

🚀 How to Run
Clone this repository:

bash
Copy
Edit
git clone https://github.com/your-username/olap-pandas.git
cd olap-pandas
Install dependencies:

bash
Copy
Edit
pip install pandas
Run the script:

bash
Copy
Edit
python olap_analysis.py
✅ Alternatively, open olap_analysis.ipynb in Jupyter Notebook.


✨ Sample Outputs

Region	February	January	Total
North	2670	2300	4970
South	3100	2900	6000
Total	5770	5200	10970
📚 Key Learning
This project demonstrates how OLAP operations can be simulated in Python using groupby() and pivot_table() for multidimensional analysis, useful for BI and reporting.
