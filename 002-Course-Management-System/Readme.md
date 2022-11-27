# Code Challenge #2: Course management system and rendering lists of attendees

|Challenge Details      |                                            |
|:----------------------|:-------------------------------------------|
|Difficulty             |Medium                                      |
|Expected time to finish|2 hours (roughly estimated, take your time!)|
|Technologies           |JavaScript, HTML, CSS                       |

# The Task at Hand
You are tasked with implementing parts of a course management system at a local college. Your job is to process various student and course enrolment data for the teaching staff and print list of attendees for each course offered. Every course has specific requirements.

## Requirements
* Process the files `students.json` and `classes.json`, which contain the student data and class enrolments, respectively. (It is okay to hardcode the JSON into your code: no need to download it programmatically.)
* Prepare a simple HTML page that takes a ``classId`` as a query parameter (e.g. `localhost/?classId=1`) and presents a sheet of class details as per the following requirements:

    * Display the name of the class.
    * Display the instructor's name.
    * Display a list (table) of attendees and their details as required by each class:

|Class Id|Data (table columns)                           |Order By                        |
|:-------|:----------------------------------------------|:-------------------------------|
|1       |registrationNr, lastName, firstName, age       |lastName ASC, then firstName ASC|
|2       |lastName, firstName, age, satScore             |satScore DESC                   |
|3       |registrationNr, lastName, firstName, email     |registrationNr ASC              |
|4       |registrationNr, lastName, satScore             |age DESC, then satScore ASC     |
|5       |registrationNr, lastName, gender, age, satScore|gender ASC, then age ASC        |

# Challenges
* You are dealing with data processing according to pre-defined criteria. There is some variety involved. Try to come up with proper abstractions to handle such variety without too much code repetition.