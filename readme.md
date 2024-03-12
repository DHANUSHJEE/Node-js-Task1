Node js Task 1

Getting Started
Task1 Node.js


Install Dependencies:
npm init Yes
Run the Server
To start the server, run the following command in your terminal:

npm start
Usage
Generate Timestamp

Visit the main page at http://localhost:4000/ to generate a timestamp. The timestamp will be displayed on the web page, and a corresponding text file will be saved in the "TimeStamp" directory. The file name will be in the format dd-mm-yyyy HH-mm-ss.txt.

Example:

Web page: http://localhost:4000/
Text file: TimeStamp/01-03-2024 12-30-45.txt
View Text Files

Access the http://localhost:4000/getTextFiles endpoint to retrieve a list of text files saved in the "TimeStamp" directory. The response will be a JSON array containing the names of the text files.

Example:

["01-03-2024 12-30-45.txt", "28-02-2024 15-20-10.txt", "27-02-2024 09-05-30.txt"]