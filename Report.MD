In this Week 5 project, I focused on learning and applying NumPy to my cleaned supply chain dataset. 
This week was all about moving beyond Python lists into arrays, performing fast numerical operations, and extracting meaningful insights from costs, quantities, and lead times.

![My image Description](https://github.com/R887645/TDI-Python-Learning-Week-5-Project-/blob/main/Intro%20Wk%205.png?raw=true)

# Key Skills Practiced
- Creating arrays from CSV columns using .to_numpy()

- Indexing and slicing arrays to access subsets of data

- Performing element‑wise operations without loops

- Using statistical functions (mean, std, percentile, min, max)

- Broadcasting operations across arrays (e.g., applying shipping markup or profit margins)

- Detecting outliers using statistical thresholds

- Comparing supplier performance with average costs and lead times


# What I Implemented

- Converted total_cost, quantity, and lead_time_days into NumPy arrays and verified them

- Calculated total revenue, average order value, min/max costs, and lead time ranges

- Built a statistical summary (mean, median, quartiles, std deviation) for each metric

- Identified products with above‑average costs and orders with below‑average lead times

- Compared suppliers by average cost and delivery time, highlighting the most efficient ones

- Detected unusual orders by flagging outliers more than 2 standard deviations from the mean

- **Tackled extra challenges:** profit score broadcasting, correlation analysis, and cost distribution bins


![My image Description](https://github.com/R887645/TDI-Python-Learning-Week-5-Project-/blob/main/Task%201.png?raw=true)

![My image Description](https://github.com/R887645/TDI-Python-Learning-Week-5-Project-/blob/main/Task%202A.png?raw=true)

# Extra Challenges

- **Profit Score Broadcasting:** Applied multiple profit margins (0.20, 0.25, 0.30) simultaneously using broadcasting to see how profits scale.

- **Correlation Analysis:** Found strong positive correlation between quantity and total cost, and a negative correlation between lead time and on‑time delivery.

- **Distribution Analysis:** Divided costs into bins (<$1000, $1000–$5000, $5000+) to reveal that most orders cluster in the mid‑range, with fewer high‑value transactions.

![My image Description](https://github.com/R887645/TDI-Python-Learning-Week-5-Project-/blob/main/Challenge%201A.png?raw=true)

![My image Description](https://github.com/R887645/TDI-Python-Learning-Week-5-Project-/blob/main/Challenge%201B.png?raw=true)

# Reflection
This project showed me how powerful NumPy is for numerical analysis. Arrays made calculations faster and cleaner compared to pure Python lists. 
I especially appreciated how broadcasting eliminated the need for manual loops when applying markups or profit margins.

**[View My week 4 full project here](https://github.com/R887645/TDI-Python-Learning-Week-5-Project-/blob/main/Week5_PersonalDataOrganizer%20(1).ipynb)**

One challenge I faced was fully understanding array broadcasting and how NumPy automatically aligns shapes when performing operations. 
I’ll continue exploring this concept in more depth going forward, since it’s key to writing efficient numerical code.

Overall, Week 5 helped me move from data cleaning into true analysis, uncovering supplier performance patterns, cost distributions, and statistical outliers.
