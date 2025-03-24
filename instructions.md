# Instructions

<details>
  <summary>
    Exam 2 Format: Dictionary Operations: (50 pts)
  </summary>

  - You will be given **ONE** complex dictionary similar to the examples given below
  - You will be asked to perform 10 operations
  - All dictionary operations will be performed in a function `student_ops()`  inside part1.py
  - This function will be called in main.py inside main() function
</details>


<details>
  <summary>
    ✅ Create Project in PyCharm
  </summary>

  - Create a project in PyCharm (do not create any sub folders)
  - Create main.py, part1.py
  - Download the [students dictionary](https://github.com/suchialex/CINS3002-CW09/blob/main/students.pkl)
</details>


## Student Dictionary Operations

<details>
  <summary>
    Student Dictionary Structure:  
  </summary>

  - It is a complex dictionary with integral keys
  - (integer) -> (dictionary)
    - "name" -> (string)
    - "major" -> (string)
    - "gpa" -> (float)
    - "scores" -> (list of numbers)
    - "courses" -> (dictionary)
      - "fall2023" -> (set of strings)
      - "spring2024" -> (set of strings)
</details>

### In student_ops() function, perform these operations


<details>
  <summary>
    ✅ 1. Unpickle the dictionary
  </summary>
  
  - Unpickle the dictionary stored in students.pkl
  - 🚩 In the exam,
    - this will be the most important operation - without mastering this, you cannot proceed further
    - you may use suchi_print to print the dictionary structure and view the datatypes
</details>

<details>
  <summary>
    ✅ 2. Change name of a student - 1 user input
  </summary>

  - Get user input for CWID
  - Convert CWID to integer (use exception handling or test input using `isdigit()`)
  - If that CWID exists in the dictionary, change (or add) the name `Steven Franklin`
  - If CWID doesn't exist, then print `Student Not Found`
</details>


<details>
  <summary>
    ✅ 3. Change name of a student - 2 user inputs
  </summary>

  - Get user input for CWID
  - Convert CWID to integer (use exception handling or test input using `isdigit()`)
  - If that CWID exists in the dictionary, ask user to input a student name
  - Make sure this name doesn't have any numeric characters (spaces are allowed and special characters are allowed)
  - User must be prompted for valid name until he enters one
  - Name must have first letter of each word in uppercase
  - Change the student with that user entered CWID, to the vaidated user entered name
  - If CWID doesn't exist, then print `Student Not Found`
</details>


<details>
  <summary>
    ✅ 4. Enroll for a class for a term - 1 user input
  </summary>

  - Get user input for CWID
  - If that CWID exists in the dictionary, register that student for ENGL 1001 for spring2024
  - If CWID doesn't exist, then print `Student Not Found`
</details>


<details>
  <summary>
    ✅ 5. Enroll for a class for a term - 2 user inputs
  </summary>

  - Get user input for CWID
  - If that CWID exists in the dictionary (remember to convert it to integer using exception handling),
    - Get user input for a term
    - Register that student for ENGL 1001 for that term
  - If CWID doesn't exist, then print `Student Not Found`
</details>


<details>
  <summary>
    ✅ 6. Enroll for a class for a term - 3 user inputs
  </summary>

  - Get user input for CWID
  - If that CWID exists in the dictionary,
    - Get user input for a term
    - Get user input for course
    - Register that student for the course entered for the term entered by user
  - If CWID doesn't exist, then print `Student Not Found`
</details>


<details>
  <summary>
    ✅ 7. Add score - 1 user input
  </summary>
  
  - Get user input for CWID
  - If that CWID exists in the dictionary, add a score of 72 at the beginning of the list
  - If CWID doesn't exist, then print `Student Not Found`
</details>


<details>
  <summary>
    ✅ 8. Add score - 2 user inputs
  </summary>
  
  - Get user input for CWID
  - If that CWID exists in the dictionary,
    - Get user input for score and add the user entered score at the beginning of the list (remember, scores are all integers, so you must convert without raising an exception, using isdigit() before conversion will avoid exceptions)
  - If CWID doesn't exist, then print `Student Not Found`
</details>


<details>
  <summary>
    ✅ 9. Unenroll from courses - no user input
  </summary>
  
  - Unenroll cwid 10010100 from all courses in spring2024
</details>


<details>
  <summary>
    ✅ 10. Unenroll from courses - 1 user input
  </summary>

  - Get user input for CWID
  - If that CWID exists in the dictionary, unenroll from all courses in spring2024 (without raising exception)
  - If not, print `Student Not Found`
</details>


<details>
  <summary>
    ✅ 11. Unenroll from courses - 2 user inputs
  </summary>

  - Get user input for CWID
  - If that CWID exists in the dictionary
    - Get user input for term
    - Unenroll from student with user entered CWID from all courses in that term (without raising exception)
  - If not, print `Student Not Found`
</details>


<details>
  <summary>
    ✅ 12. Calculate Average - 1 user input
  </summary>

  - Get user input for CWID
  - If that CWID exists in the dictionary
  - Calculate and print to two decimal point precision, the average score of that student (must check if scores key is present)
</details>


<details>
  <summary>
    ✅ 13. Calculate Average - All students
  </summary>

  - For all students, print CWID and the average score rounded to two decimals, if scores are not present, print N/A
</details>


<details>
  <summary>
    ✅ 14. Give 10% bonus to all students for all assignments
  </summary>

  - For all students that have scores, increase each score by 10%
  - For students that have no scores, give a score of 100 (one element in a list)
  - For example, if a student has scores [50, 60, 70] their final scores should be [55, 66, 77]
</details>


<details>
  <summary>
    ✅ 15. Delete any scores less than 80 for all students
  </summary>

  💡Hint:  
  - Use for loop to go over the dictionary
  - For students that have scores, use list comprehension to create a new list of scores excluding anything less than 70
  - Assign that list back to the dictionary key 'scores'
</details>


<details>
  <summary>
    ✅ 16. Change department of all students
  </summary>
  
  - Change major values for all the students to uppercase
</details>


<details>
  <summary>
    ✅ 17. Change GPA of students
  </summary>
  
  - Add .05 to all the students' GPA
  - For example Henry's new GPA will be 3.80, James' should be 0.05, Mary's will be 3.91
</details>


<details>
  <summary>
    ✅ 22. Students taking CINS 3002 in Fall 2023
  </summary>
  
  - Display all the students' CWIDs and names (in a tabular format) who are taking cins 3002 in fall 2023
  - Do a case-insensitive search for term and course name
</details>


<details>
  <summary>
    ✅ 23. Drop course
  </summary>
  
  - Get user input for a course
  - If any student is taking that course in fall 2023, drop that course for that student
</details>

<details>
  <summary>
    ✅ 24. Copy code to Replit
  </summary>

  - Create a new App on replit, name it Exam2Prep
  - Copy code from main.py and part1.py
</details>
