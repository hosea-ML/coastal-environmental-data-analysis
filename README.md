# Coastal Environmental Data Analysis with Python

## Overview

This project is a Python practice project focused on analyzing synthetic coastal environmental monitoring data.

The project was created as part of my journey in learning Python and applying programming concepts to an area that interests me: **coastal and marine geospatial science**.

The notebook demonstrates how fundamental Python data structures and programming concepts can be applied to organize, process, and analyze environmental data.

> Note: The environmental measurements in this project are synthetic data created for programming practice. They should not be interpreted as real environmental observations from Lagos.

## Project Scenario

The project uses a simplified coastal monitoring station containing monthly observations for:

* Salinity
* Temperature
* pH
* Shoreline change
* Coastal hazards

The station data is organized using nested Python data structures so that environmental measurements remain connected to their corresponding months.

## Data Structure

The monitoring station is represented using several Python data structures:

* Dictionary — stores the overall station information and environmental measurements.
* Tuple — stores the station location as a fixed pair of city and country.
* Nested dictionaries — connect environmental parameters to their monthly measurements.
* Sets — represent hazards recorded during each month.
* Lists — used during numerical data preparation.

## What I Practiced

### Python Dictionaries

I practiced:

* Creating dictionaries
* Accessing nested dictionary values
* Iterating through dictionaries using `.items()`
* Building new dictionaries
* Dictionary comprehensions
* Counting values using dictionaries

### Sets

I practiced:

* Creating sets
* Checking whether an item exists in a set
* Using `.update()`
* Collecting unique hazard types
* Counting hazard occurrences

### Tuples

The station location is represented as:

```python
("Lagos", "Nigeria")
```

This demonstrates the use of a tuple for a fixed collection of related values.

### Loops and Conditionals

The project uses:

* `for` loops
* Nested loops
* `if` statements
* Accumulator variables
* Minimum and maximum value tracking

## Analysis Performed

The notebook includes several small analyses.

### Salinity

I calculated:

* Total monthly salinity
* Average salinity
* Highest salinity and its month
* Lowest salinity and its month

### Temperature

I calculated:

* Average temperature
* Highest temperature and its month
* Lowest temperature and its month

### Comparing Measurements

I compared monthly salinity and temperature using their shared month keys.

For example:

```text
Salinity - Temperature
```

The month is preserved as the dictionary key so that each result remains associated with its corresponding observation period.

### Coastal Hazards

I analyzed the monthly hazard data to:

* Identify unique hazard types
* Identify months in which hazards occurred
* Count how many times each hazard occurred

For the synthetic dataset, the hazard types include:

* Flooding
* Pollution

## Technologies Used

* Python
* Jupyter Notebook

## Project Structure

```text
coastal-environmental-data-analysis/
│
├── coastal_environmental_analysis.ipynb
├── README.md
└── .gitignore
```

## Learning Objectives

The main goal of this project was not to build a production environmental monitoring system, but to strengthen my understanding of Python fundamentals by applying them to a practical environmental scenario.

Through this project, I practiced moving from:

```text
Raw Data
   ↓
Python Data Structures
   ↓
Loops and Conditions
   ↓
Data Processing
   ↓
Simple Environmental Analysis
```

## Future Improvements

As I continue developing my Python and geospatial skills, I plan to extend this type of project by working with:

* Real environmental datasets
* Numpy
* Pandas
* Data visualization
* Geospatial data
* GIS analysis
* Satellite imagery
* Google Earth Engine
* Machine learning for environmental applications

## Author

Oluwabusola Adebayo Hosea

Learning Python, AI/ML, and geospatial science with a focus on practical environmental applications.
