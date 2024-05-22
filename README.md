# kurasa_sql
Kurasa Data Analyst Intern Interview Questions
Using the dataset attached on the email, (kurasa_exercise.sql) attempt exercise 1 and 2. Put 
your answers in a file your_name_exercise_1_2_may.sql on this thread.
EXERCISE 1.
In this exercise you will be working with Grade 2 Green(id:119) of school 16 as found on 
TABLE streams, TABLE cbc_assesments to see scores AND TABLE subjects to see subjects. 
Note that the column indicator_score in TABLE cbc_assesments is the score we are referring 
to.
Do an SQL query(s) that shows the distribution of scores for each subject taken Grade 2 
Green in whichever format.
you can give output in whichever format - below is a sample output on my side. For example 
I am showing that 9 students scored 2 and 28 students scored 3 in Literacy Activities.
Literacy Activities,15,"{""(2,9)"",""(3,28)""}" 
Environmental,13,"{""(1,1)"",""(2,9)"",""(3,25)""}" 
Music,11,"{""(1,1)"",""(2,13)"",""(3,22)""}"
Hygiene and Nutrition Activities,9,"{""(1,1)"",""(2,14)"",""(3,18)""}" 
Christian Religious Education ,6,"{""(2,13)"",""(3,23)""}" 
Mathematics,3,"{""(1,2)"",""(3,19)"",""(2,12)""}"
Kiswahili,1,"{""(3,22)"",""(2,14)""}" 
EXERCISE 2.
a)  Describe in a paragraph or two how you can fetch/show syllabus coverage for a 
mathematics teacher in Grade 2 Green using the data in context below
b)  Show the percentage of the syllabus coverage in (a) above and the query you have 
used to get to the answer.
Context
TABLE indicator_assessments
TABLE cbc_assesments
TABLE subjects
Topics and subtopics can be found in the respective tables 
TABLE ztbl_course_plan
TABLE ztbl_course_subtopics
