# Code Challenge #1: Rendering addresses from a CSV file using HTML tables

|Challenge Details      |                                            |
|:----------------------|:-------------------------------------------|
|Difficulty             |Easy to Medium                              |
|Expected time to finish|2 hours (roughly estimated, take your time!)|
|Technologies           |JavaScript, HTML, CSS                       |

# The Task at Hand
On a simple web page, allow the user to select a CSV file. Process the CSV file and present its contents as an HTML table on screen. Turn e-mail addresses into clickable mailto-links.

# Requirements
1. The user should be able to click a button and select the `addresses.csv` file for processing (JS).
2. Its *entire* contents should then be rendered as a table on screen (HTML).
3. If any line of the file is malformed or empty, it should be skipped.
4. Lines starting with a `#` are comments and to be skipped/excluded from processing.
5. The first line contains field names and should be rendered as column headers.
6. E-mail addresses should be rendered as clickable mailto-links.

# Challenges
* Keep in mind that user input (including files) is not necessarily well-formed. Our code should handle exceptions gracefully.
* You can tie your implementation to the data specifics at hand (i.e. the specific column order, etc.) but that wouldn't make your code robust and future-proof. If you feel like it, try to keep your solution maintainable by abstracting over the details and deal with various types of input data (all CSV files).