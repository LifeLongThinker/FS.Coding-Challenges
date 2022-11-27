# Code Challenge #1: Reading a CSV file and displaying its contents as an HTML table

|Challenge Details      |                       |
|:----------------------|:----------------------|
|Difficulty             |Easy                   |
|Expected time to finish|2 hours                |
|Technologies           |JavaScript, HTML, CSS  |

# Basic Task
On a simple web page, allow the user to select a CSV file. Process the CSV file and present its contents as an HTML table on screen. Turn e-mail addresses into clickable mailto-links.

# Requirements
1. The user should be able to click a button and select the `addresses.csv` file for processing (JS).
2. Its *entire* contents should then be rendered as a table on screen (HTML).
3. If any line of the file is malformed or empty, it should be skipped.
4. Lines starting with a `#` are comments and to be skipped/excluded from processing.
5. The first line contains field names and should be rendered as column headers.
6. E-mail addresses should be rendered as clickable mailto-links.