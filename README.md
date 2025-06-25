# Data-Cleaning-Preprocessing
I built this notebook while wrestling with a pretty untidy customer-sales file from an old internship.  
The sheet had everything that scares a data person—blank cells, weird text labels, numbers stored as strings, and a few outrageously high “₹ 99,99,999” sales that clearly weren’t real. I decided to turn the clean-up process into a repeatable mini-workflow so I wouldn’t have to reinvent the wheel next time.

What you’ll find here is exactly what I use in my day-to-day work:

- **Straightforward Pandas/NumPy code**—no fancy wrappers, just the classics.
- **Visual sanity checks** with Seaborn, Matplotlib, and an occasional Plotly plot when I need to hover over points.
- **Step-by-step cells** (null handling → encoding → scaling → outlier trim) so you can comment out whatever you don’t need.
- A **final DataFrame** that’s genuinely plug-and-play for scikit-learn models—no hidden NaNs or mixed dtypes.

