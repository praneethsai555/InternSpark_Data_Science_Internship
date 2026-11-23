# InternSpark Data Science Internship — Zomato Dataset Analysis

## Project goal
Analyze restaurant and rating data to understand ratings, cuisines, location hotspots, price patterns, and text trends. Prepare a cleaned dataset, visualizations, key findings, five platform recommendations, and a PDF report.

## Dataset
Download the Zomato dataset from the Kaggle link given in the InternSpark task:
https://www.kaggle.com/datasets/bhanupratapbiswas/zomato

After downloading the ZIP:
1. Extract it.
2. Find the restaurant data CSV file.
3. Copy the CSV file(s) into this project's `data/` folder.
4. Keep the original CSV file unchanged.

## Run in VS Code
1. Install Python and VS Code.
2. Install the Python and Jupyter extensions in VS Code.
3. Open this project folder in VS Code.
4. Open the VS Code terminal: **Terminal → New Terminal**.
5. Create a virtual environment:
   - Windows: `python -m venv .venv`
   - Activate: `.venv\\Scripts\\activate`
6. Install dependencies: `pip install -r requirements.txt`
7. Open `Zomato_Dataset_Analysis.ipynb`.
8. Select the Python kernel from `.venv`.
9. Run **Run All** from the notebook menu.

## Outputs
The notebook creates these files in `outputs/`:
- `zomato_cleaned.csv`
- PNG charts: rating distribution, cuisine vs rating, location hotspots, price vs rating, correlation heatmap, and wordcloud
- `zomato_analysis_report.pdf`

## Notes
- The notebook handles common column-name variations and missing values.
- If the dataset does not contain review text, the wordcloud uses cuisine names instead.
- Price comparisons use the most common currency to avoid mixing currencies.
- Review the actual output and update the report's wording if your dataset has different columns or results.

## GitHub
Do not upload `.venv/` or unnecessarily large raw dataset files. Upload the notebook, README, requirements, and (if acceptable for your internship) generated outputs. Check the dataset's license/terms before redistributing it.
