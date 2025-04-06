# Branch Optimization for Fawry Using KDTree and Spatial Analysis

This project aims to optimize branch selection for Fawry by leveraging spatial analysis and the KDTree algorithm. The goal is to maximize sales coverage while minimizing operational costs.

## Features

- **Spatial Analysis**: Efficiently find nearby locations using KDTree.
- **Branch Optimization**: Select branches to maximize sales and minimize costs.
- **Visualization**: Compare sales and operational costs for selected branches.
- **Metrics Calculation**: Evaluate performance with metrics like sales achieved, costs saved, and coverage percentage.
- **Excel Export**: Save recommended branches to an Excel file for further analysis.

## Requirements

- Python 3.7+
- Libraries:
  - `pandas`
  - `numpy`
  - `scipy`
  - `matplotlib`
  - `openpyxl` (for Excel file handling)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/branch-optimization.git
   cd branch-optimization
   ```

2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Place the input Excel file (`Fawry - Data Science - AI Task.xlsx`) in the project directory.
2. Run the script:
   ```bash
   python Fawry.ipynb
   ```
3. The script will:
   - Load and process the data.
   - Perform spatial analysis using KDTree.
   - Optimize branch selection.
   - Save the recommended branches to `Recommended_Branches.xlsx`.
   - Display visualizations and metrics.

## Output

- **Excel File**: `Recommended_Branches.xlsx` containing the selected branches with their details.
- **Visualization**: A bar chart comparing sales and operational costs for selected branches.
- **Metrics**:
  - Total potential sales
  - Total sales achieved
  - Percentage of sales achieved
  - Total operational costs
  - Selected operational costs
  - Percentage of costs saved
  - Total profit
  - Coverage percentage

## Example Metrics

After running the script, you will see metrics like:
```
Total Potential Sales: $1,000,000.00
Total Sales Achieved: $750,000.00
Percentage of Sales Achieved: 75.00%
Total Operational Costs: $500,000.00
Selected Operational Costs: $300,000.00
Percentage of Costs Saved: 40.00%
Total Profit: $450,000.00
Coverage Percentage: 60.00%
```

## Visualization

The script generates a bar chart comparing sales and operational costs for the selected branches.

## Notes

- Ensure the input Excel file has the correct structure with sheets named `Type A` and `Type B`.
- The script assumes no sales data for `Type B` branches and assigns an estimated sales value of `0`.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Fawry for providing the data and task requirements.
- Libraries used: `pandas`, `numpy`, `scipy`, `matplotlib`.

## Contact

For any questions or issues, please contact [your-email@example.com].
