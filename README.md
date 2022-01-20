# TechWorld
TechWorld, a technology training center, wants to allocate courses for instructors.
An instructor is identified by name, technology skills, experience and average feedback.
An instructor is allocated a course, if he/she satisfies the below two conditions:

eligibility criteria:
if experience is more than 3 years, average feedback should be 4.5 or more
if experience is 3 years or less, average feedback should be 4 or more
he/she should posses the technology skill for the course
Identify the class name and attributes from the list of options below to represent instructors.

check_eligibility()
avg_feedback
experience
instructor_name
allocate_course()
allocate_course(technolody)
__init__()
Instructor
calculate_avg_feedback()
technology_skill
Write a Python program to implement the class chosen with its attributes and methods.

Note:

Consider all instance variables to be private and methods to be public
An instructor may have multiple technology skills, so consider instance variable, technology_skill to be a list
check_eligibility(): Return true if eligibility criteria is satisfied by the instructor. Else, return false
allocate_course(technology): Return true if the course which requires the given technology can be allocated to the instructor. Else, return false
Perform case sensitive string comparison
Represent few objects of the class, initialize instance variables using setter methods, invoke appropriate methods and test your program.
