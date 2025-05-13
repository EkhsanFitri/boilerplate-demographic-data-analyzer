# Demographic Data Analyzer

This is the boilerplate for the Demographic Data Analyzer project. Instructions for building your project can be found at https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-projects/demographic-data-analyzer

# Demographic Data Analyzer

This project analyzes demographic data from the [Adult Census Income Dataset](https://archive.ics.uci.edu/ml/datasets/adult) to extract various statistics about race, education, work hours, income, and occupation.

## Features

- Counts the number of each race represented in the dataset
- Calculates the average age of men
- Determines the percentage of people with a Bachelor's degree
- Calculates the percentage of people with and without higher education who earn >50K
- Finds the minimum number of hours worked per week
- Calculates the percentage of rich among those who work the fewest hours
- Identifies the country with the highest percentage of people earning >50K
- Finds the most popular occupation for those who earn >50K in India

## Files

- `adult.data.csv` — The dataset used for analysis
- `demographic_data_analyzer.py` — Main analysis code
- `main.py` — Script to run the analyzer and print results
- `test_module.py` — Unit tests for the analyzer

## Usage

1. **Install requirements**  
   This project uses Python 3 and `pandas`. Install dependencies with:
   ```sh
   pip install pandas
   ```

2. **Run the analyzer**
   ```sh
   python main.py
   ```

3. **Run the tests**
   ```sh
   python test_module.py
   ```

## Example Output

```
Number of each race:
 race
White                 27816
Black                  3124
Asian-Pac-Islander     1039
Amer-Indian-Eskimo      311
Other                   271
Name: count, dtype: int64
Average age of men: 39.4
Percentage with Bachelors degrees: 16.4%
Percentage with higher education that earn >50K: 46.5%
Percentage without higher education that earn >50K: 17.4%
Min work time: 1 hours/week
Percentage of rich among those who work fewest hours: 10.0%
Country with highest percentage of rich: Iran
Highest percentage of rich people in country: 41.9%
Top occupations in India: Prof-specialty
```

## License

This project is for educational purposes.