# Case-Study-Flattening-JSON-Data-Using-Power-BI
## Objective
The purpose of this case study is to demonstrate how JSON data was converted into a structured, flattened file format using Power BI. This process was essential to prepare the data for analysis and reporting.

## Background
● JSON (JavaScript Object Notation) is a commonly used data format for APIs and data storage.
● While JSON is flexible and hierarchical, it often requires flattening to make it suitable for analysis in tabular formats.
● The goal was to use Power BI to:
  1. Import a complex JSON file.
  2. Transform the data into a structured format.
  3. Export the transformed data for further use.

## Challenges
## Complex Hierarchies: The JSON file contained nested arrays and objects.
## Dynamic Structure: Some keys and values varied in depth and presence across records.
## Efficiency: The solution needed to be robust and reusable for similar datasets.

## Approach
## Step 1: Import JSON File
  1. Opened Power BI Desktop.
  2. Used the Get Data option to import the JSON file.
  3. Inspected the hierarchical structure using the built-in Navigator.

## Step 2: Transform Data
  1. Navigated to the Power Query Editor:
     ● Expanded nested arrays and objects using the expand buttons in the query editor.
     ● Used Rename Columns for clarity and conciseness.
  2. Applied Transform Column to remove "+91-" string from the phone column.
  3. Used custom steps for:
    ● Combining multi-level nested data into a single table.

## Step 3: Data Validation
  1. Validated the transformed data to ensure completeness and accuracy.
  2. Ensured that all records were flattened into a tabular format with unique rows.

## Step 4: Export Structured File
  1. Loaded the transformed data into the Power BI data model.
  2. Exported the data to a CSV file using the Export Data feature for use in other systems.

## Outcome
  ● Successfully converted the hierarchical JSON data into a flattened, structured format.
  ● The structured file included all relevant fields and relationships, ready for analysis.
  ● The process is reusable for similar datasets, providing a scalable solution.

## Key Learnings
## 1. Power BI Versatility: The Power Query Editor is highly effective for handling complex data transformations.
## 2. JSON Complexity: Thorough understanding of the JSON structure is essential for efficient flattening.
## 3. Data Preparation: Preparing data in Power BI can streamline analytical workflows and enhance data accessibility.

## Included all the relevant files:
  ● The original JSON file structure.
  ● Steps in the Power Query Editor.
  ● The final flattened file or exported CSV.

## Conclusion
This case study highlights the power of Power BI as a tool for transforming JSON data into a structured format. By leveraging its robust data transformation capabilities, JSON hierarchies were efficiently flattened, paving the way for seamless data analysis and reporting.

