# Web-Crawler-in-Java
## HTML parser will parse out the relevant info corresponding to an input search string from a large set of HTML content
## The UI is created using JAVA Swing
## For database we used Flatfile for speed, simplicity and portability
## 3 components of the project
1. Multithreading
2. Parsing
3. File Handling

## The following classes are used for HTML Parser:
1. SimpleThread class: This class creates a threadpool and also a fixed number of worker threads(activated threads
2. WorkerThread class: This class defines all the tasks that a worker thread needs to perform
3. FileQ class: This class puts the HTML files into an infinite queue
4. FileRead class: Parses the content of the HTML file for a given search string
5. CheckFile class: Checks for data duplicity in the flat file
6. FileWrite class: Writes data into flat file

### Job of a thread: Choose a .html file, read its content, parsing it for a given string, writing relevent info into flatfile
