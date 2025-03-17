# Instructions

<details>
  <summary>
    Assignment Instructions
  </summary>

  - This is a sample exam format
  - Exam will have two parts - dictionary operations and classes
<details>
  <summary>
    Dictionary Operations:
  </summary>

  - This part will be 50 pts
  - You will be given ONE complex dictionary similar to the examples given below
  - You will be asked to perform only 10 operations
  - All dictionary operations will be performed in a function, inside part1.py
  - This function will be called in main.py inside main() function

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

  Download students.pkl https://github.com/suchialex/CINS3002-CW09/blob/main/students.pkl
</details>

<details>
  <summary>
    Employee Dictionary Structure:  
  </summary>

  - It is a complex dictionary with integral keys
  - (int) -> (dictionary)
    - "name" -> (string)
    - "dept" -> (string)
    - "projects" -> (list of strings)
    - "titles" -> (set of strings)
    - "certifications" -> (dictionary)
      - (string) certification code -> (string) date taken YYYY-MM-DD format

  Download employees.bin https://github.com/suchialex/CINS3002-Exam2Bonus7/blob/main/employees.bin
</details>

</details>

<details>
  <summary>
    Classes:
  </summary>

  - This part is worth 50 pts
  - You will define a class per instructions in classes.py
  - You will import that class in part2.py
  - Objects of that class will be created and manipulated in a function called class_ops() in part2.py
  - This function is called in main.py inside main() function
</details>
   
  - All exceptions must be handled
</details>


## Dictionary Operations

<details>
  <summary>
    Part 1: Dictionary Operations
  </summary>

### In student_ops() function, perform these operations


<details>
  <summary>
    ✅ 1. 
  </summary>
  Unpickle the dictionary stored in students.pkl
</details>


<details>
  <summary>
    ✅ 2. 
  </summary>
  Change student name whose cwid is 10010100 to Hank
</details>


<details>
  <summary>
    ✅ 3. 
  </summary>
  Register student with cwid 10010101 for ENGL 1001 for spring2024 
</details>


<details>
  <summary>
    ✅ 4. 
  </summary>
  Insert a score of 72 at the third position of student cwid 10010100
</details>


<details>
  <summary>
    ✅ 5. 
  </summary>
  Ask user to enter cwid, and register that student for ACCT 101 for spring2024
</details>


<details>
  <summary>
    ✅ 6. 
  </summary>
  Ask user to enter cwid, register that student for ENGL 1002 for fall2023
</details>


<details>
  <summary>
    ✅ 7. 
  </summary>
  Unenroll cwid 10010100 from all courses in spring2024
</details>


<details>
  <summary>
    ✅ 8. 
  </summary>
  Add the list of scores [89, 98, 99, 58] to student 10010102
</details>


<details>
  <summary>
    ✅ 9. 
  </summary>
  Add more scores stored in a tuple scores = (89, 88, 85, 89, 62) to student 10010101
</details>


<details>
  <summary>
    ✅ 10. 
  </summary>
  Ask user to enter cwid, and calculate the average score of that student
</details>


<details>
  <summary>
    ✅ 11. 
  </summary>
  Assign 3 integral scores (meaning, integers) 98.5, 99.3, 90.3 one at a time to student 10010103 (this will be three statements)
</details>


<details>
  <summary>
    ✅ 12. 
  </summary>
  Unenroll cwid 10010100 from HIST 1001 in fall2023
</details>


<details>
  <summary>
    ✅ 13. 
  </summary>
  Delete the score 100 from student 10010101
</details>


<details>
  <summary>
    ✅ 14. 
  </summary>
  Ask the user for a student ID and, delete the third score of that student (without raising any exceptions)
</details>


<details>
  <summary>
    ✅ 15. 
  </summary>
  Change major values for all the students to uppercase
</details>


<details>
  <summary>
    ✅ 16. 
  </summary>

  Delete any scores less than 80 for all students
  Hint:
  - Use for loop to go over the dictionary
  - Use list comprehension to create a new list of scores excluding anything less than 70
  - Assign that list back to the dictionary key 'scores'
</details>


<details>
  <summary>
    ✅ 17. 
  </summary>
  Change Mary's name to Mia
</details>


<details>
  <summary>
    ✅ 18. 
  </summary>
  To all the students, add a score 100 at the end (if they don't have any scores, this will be their first score)
</details>


<details>
  <summary>
    ✅ 19. 
  </summary>
  Add two courses for spring2024 for student 10010102 - MATH 1001, ENGL 1002
</details>


<details>
  <summary>
    ✅ 20. 
  </summary>
  Add two courses for spring2024 for student 10010103 - MATH 1001, ENGL 1002
</details>


<details>
  <summary>
    ✅ 21. 
  </summary>
  Add .05 to all the students' GPA, for example Henry's new GPA will be 3.80, James' should be 0.05, Mary's (or Mia's) will be 3.91
</details>


<details>
  <summary>
    ✅ 22. 
  </summary>
  Display all the students' names who are taking cins 3002 in fall 2023 (case-insensitive)
</details>


<details>
  <summary>
    ✅ 23. 
  </summary>
  Add two new terms worth of courses to ALL the students - the data is stored in two tuples ('fall2024', 'UNIV 3000') and ('spring2025', 'MATH 2003') ⏩ Refer to 9-2c

</details>


<details>
  <summary>
    ✅ 24. 
  </summary>
  Drop HIST 1001 for any student that is enrolled in fall 2023
</details>


### In employee_ops() function, perform these operations


<details>
  <summary>
    ✅ 1. 
  </summary>
  Unpickle the dictionary in employees.bin and store in a variable of your choice
</details>


<details>
  <summary>
    ✅ 2. 
  </summary>
  Change employee's name ID 04568 to Roger Stevens
</details>


<details>
  <summary>
    ✅ 3. 
  </summary>
  2. For emp ID 04567 add a new certification EVA-L2 taken on March 22, 2023
</details>


<details>
  <summary>
    ✅ 4. 
  </summary>
  Add a new title - SGA President - for Riva Malik (you don't know her emp ID)
</details>


<details>
  <summary>
    ✅ 5. 
  </summary>

  For all the programmers, give a salary **increment** of 5000
  - Must be case in-sensitive, i.e. you have to look for Programmer or PROGRAMMER or programmer as title 
  - Hint: you may have to use list comprehension to convert all the titles to lowercase
  - If the employee doesn't have any salary, set the salary at 30000
</details>


<details>
  <summary>
    ✅ 6. 
  </summary>
  Add a new certification OCPL1 for emp 04569 taken on March 10, 2023
</details>


<details>
  <summary>
    ✅ 7. 
  </summary>
  Assign the project Compete to Roger Stevens as his first project (you don't know the emp ID)
</details>


<details>
  <summary>
    ✅ 8. 
  </summary>
  For Riva Malik, remove the titles Student Intern and SGA President and add Part-Time Worker
</details>


<details>
  <summary>
    ✅ 9. 
  </summary>
  Mayfield Inc project is taken over by Roundpoint Inc, so change all occurences of that project with the new name
</details>


<details>
  <summary>
    ✅ 10. 
  </summary>
  For anyone who has a certification that starts with OCPL1, add a title called Oracle Developer
</details>


<details>
  <summary>
    ✅ 11. 
  </summary>
  Print the name and salaries of all the employees who are working on the project Spring Valley. Choose a nice format and alignment so they are displayed in a tabular fashion (name, left aligned over 20, salary right aligned over 8. If either name or salary not available, print -
</details>


<details>
  <summary>
    ✅ 12. 
  </summary>
  Check the dictionary for any employee who might be missing a name, and if missing, print their ID and ask the user to set a name. Make sure that name doesn't have any special characters except space and first letter of each word must be uppercase. (You may implement it in a function named validate_name, or just a while loop)
</details>


<details>
  <summary>
    ✅ 13.  
  </summary>
  Pickle this dictionary and save it in a file named employees2.bin
</details>

</details>


