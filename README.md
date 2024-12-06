# Node.js File System Task

This Node.js application demonstrates basic file system operations using the Express framework. The application provides two API endpoints to create and retrieve timestamped text files.

## Features

- **Create Timestamped File**: Generates a text file with the current timestamp as its content and filename.
- **List Timestamped Files**: Retrieves all text files stored in the `TimeStamp` folder and returns their filenames as a JSON response.

## Endpoints

### 1. Create Timestamped File

- **URL**: `/`
- **Method**: `GET`
- **Description**: This endpoint creates a text file in the `TimeStamp` folder. The filename and content of the file are set to the current timestamp.
- **Response**: Returns the content of the created file.

#### Example Response
```txt
2024-01-29T17-59-13.269Z
```
### 2. List Timestamped Files
URL: /getTextFiles
Method: GET
Description: This endpoint retrieves all text files stored in the TimeStamp folder and returns their filenames as a JSON response.
Response: Returns a JSON array of filenames.

### Example Response

[
  "2024-01-29T17-58-38.521Z.txt",
  "2024-01-29T17-58-45.671Z.txt",
  "2024-01-29T17-59-13.269Z.txt",
  "2024-01-29T17-59-15.237Z.txt"
]


