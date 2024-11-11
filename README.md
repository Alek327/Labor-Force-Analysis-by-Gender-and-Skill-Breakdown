# Labor Force Analysis by Gender and Skill Breakdown

This repository contains an R script that calculates the labor force by gender and skill levels based on population, labor force participation rate (LFPR), and gender and skill distribution data. The output is a systematic breakdown of labor force by region, gender, and skill level.

## Features
- Loads population, LFPR, gender distribution, and skill distribution data files.
- Reshapes data from wide to long format for easy manipulation.
- Calculates total labor force, then segments by gender and skill level.
- Outputs results to an Excel file for further analysis.

## Requirements
- **R** version 4.0 or higher
- **Libraries**:
  - `dplyr`
  - `tidyr`
  - `readxl`
  - `openxlsx`

## Installation

To run this script, ensure you have the required R packages installed:

```r
install.packages("dplyr")
install.packages("tidyr")
install.packages("readxl")
install.packages("openxlsx")

## Usage

Clone the repository:

git clone https://github.com/yourusername/labor-force-analysis.git

Open the R script in your preferred R environment.
Run the script to load each data file interactively:

Population Data
LFPR Data
Gender Distribution Data
Skill Distribution Data

The script will output a file named Labor_Force_Gender_Skill_Breakdown.xlsx, which contains the labor force breakdown by region, year, gender, and skill level.

## Data Requirements

Each data file should be structured with the following assumptions:

Population and LFPR data: Columns for each region and a "Year" column.
Gender Distribution: Columns named in the format Region_Gender (e.g., NW_Male, NW_Female).
Skill Distribution: Should include columns for skill levels (e.g., low, middle, high, capitalist).

## Output

The output Excel file includes the following columns for each region and year:

Male and Female labor force breakdown by skill level: Low, Middle, High, and Capitalist.

## License

This project is licensed under the GNU General Public License v3.0. See the LICENSE file for details.

## Contributing

Contributions are welcome! Please submit a pull request for review.

## Acknowledgments

This project was created to support systematic labor force analysis by gender and skill level across Italian regions.

## Contact

For any questions or suggestions, please reach out to Oleksandr Galychyn on LinkedIn.


