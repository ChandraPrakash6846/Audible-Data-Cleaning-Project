# Audible Data Cleaning Project

## Project Overview
This project demonstrates comprehensive data cleaning and transformation of an Audible audiobooks dataset using Power Query in Excel. The raw dataset contained multiple quality issues including inconsistent formatting, mixed data types, and unstructured text fields that required systematic standardization to make the data analysis-ready.

## Project Objectives
- **Data Standardization**: Ensure consistent formatting across all text and numeric columns
- **Data Type Conversion**: Convert text-based fields to proper data types (dates, durations, currencies)
- **Data Structure Optimization**: Split combined fields and merge related information
- **Data Quality Assurance**: Handle missing values and inconsistent entries

## 🔧 Data Cleaning Tasks Performed

### Text Standardization
- Standardized book titles to proper title case
- Removed "Writtenby:" and "Narratedby:" prefixes from author/narrator columns
- Split multiple authors/narrators into separate columns using comma delimiter

### Data Type Conversions
- Converted `releasedate` from text to proper Date format
- Transformed `time` column from text (e.g., "2 hrs and 20 mins") to Excel Duration format
- Changed `price` column to numeric format, replacing "Free" values with 0
- Extracted numeric ratings from text fields (e.g., "4.5 out of 5 stars")

### Data Structure Enhancements
- Merged `releasedate` and `language` columns into unified `releaseinfo` field
- Ensured currency values display with consistent decimal places
- Created structured columns for multi-value fields

##  Technologies Used
- **Microsoft Excel** with **Power Query Editor**
- **Data Transformation Functions**: Capitalize Each Word, Split Column, Extract Text, Replace Values
- **Data Type Conversions**: Date, Duration, Currency, Decimal Number
- **Advanced Power Query Features**: Custom Columns, Conditional Logic

##  Project Impact
The cleaned dataset now enables:
- Accurate sorting and filtering by date, price, and duration
- Proper mathematical calculations and aggregations
- Reliable analysis of author/narrator performance
- Consistent reporting and visualization capabilities

##  Getting Started
1. Download the dataset from: [Audible Dataset](https://drive.google.com/file/d/1yjyozaSrwShoaROq-TDuSgC5HNLLmrTE/view?usp=sharing)
2. Open in Excel and access Power Query Editor
3. Apply the transformation steps outlined above
4. Load cleaned data back to Excel for analysis

**Skills Demonstrated**: Data Cleaning, Power Query, Data Transformation, Data Quality Management, Excel Advanced Features
