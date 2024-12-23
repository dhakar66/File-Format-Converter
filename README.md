CSV to JSON File Converter
This project is a Python-based tool designed to convert structured CSV files into JSON format efficiently. 
It uses predefined schemas to dynamically map and transform CSV data into JSON, ensuring compatibility and accuracy. 
This tool is ideal for data engineering workflows involving ETL (Extract, Transform, Load) processes.



How It Works

Input Data:
CSV files stored in a structured directory (e.g., data/retail_db/<dataset_name>/part-*).
Schema definitions stored in a schemas.json file in the source directory.


Output:
JSON files saved in a mirrored structure under the target directory (e.g., data/retail_db_json/<dataset_name>/).


Execution:
Run the script with specific datasets or process all datasets defined in the schema.
