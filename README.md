# PySpark Data Processing Tutorial

A comprehensive guide to working with PySpark DataFrames, demonstrating essential data manipulation techniques and best practices.

## Overview
This repository contains examples and code snippets for processing and analyzing data using PySpark, with a focus on DataFrame operations and transformations.

## Features
- DataFrame creation and basic operations
- Column manipulation and transformations
- Data filtering and selection
- Binary column creation
- Display formatting optimization

## Code Examples

### Creating Binary Columns
```python
# Example of creating a binary column based on gender
df_pyspark.withColumn('Is_Male', df_pyspark['Gender'] == 'Male')
```

### Display Formatting
```python
# Vertical display for better readability
df_pyspark.show(vertical=True)

# Limit number of displayed rows
df_pyspark.show(3)
```

## Dataset Description
The tutorial uses a fitness-related dataset containing the following columns:
- Age
- Gender
- Weight (kg)
- Height (m)
- Max_BPM
- Avg_BPM
- Resting_BPM
- Session_Duration (hours)
- Calories_Burned
- Workout_Type
- Fat_Percentage
- Water_Intake (liters)
- Workout_Frequency (days/week)
- Experience_Level
- BMI

## Prerequisites
- Apache Spark
- Python 3.x
- PySpark SQL

## Installation
```bash
pip install pyspark
```

## Usage
1. Clone the repository
2. Install dependencies
3. Run Jupyter notebooks or Python scripts
4. Follow along with the examples

## Contributing
Feel free to submit issues, fork the repository, and create pull requests for any improvements.

## License
MIT License

