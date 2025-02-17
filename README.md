# MongoDB Integration with Python

## Overview
This project demonstrates how to:
- Connect MongoDB with Python using the `pymongo` library.
- Create a database and a collection.
- Insert data (one by one or multiple) into MongoDB.
- Read, normalize, and split a JSON file into multiple parts.
- Upload the split JSON data into MongoDB.

## Prerequisites

1. Python 3.x
2. MongoDB (local or remote)
3. Install required libraries:
   - `pymongo`
   - `pandas`

## Steps

### Step 1: Connect to MongoDB
You need to connect to MongoDB using the `pymongo` library. This can be done using the MongoDB URI and specifying the database and collection to work with.

### Step 2: Insert Data
You can insert data into MongoDB in two ways:
1. Insert data one by one using the `insert_one` method.
2. Insert multiple documents at once using the `insert_many` method.

### Step 3: Read and Normalize JSON Data
To work with structured JSON data, you can use `pandas` to read and normalize the data. This will flatten any nested JSON structures, making the data easier to work with.

### Step 4: Split and Save JSON Data into 3 Parts
Once you have normalized the JSON data, you can split it into multiple parts and save them as separate JSON files. This can be done using the `numpy` library, which allows you to split data into smaller chunks.

### Step 5: Upload JSON Files to MongoDB
After splitting the data into multiple files, you can upload each file to MongoDB. Each file can be read and inserted into the database using the `insert_many` method.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
