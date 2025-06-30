# task-5

INNER JOIN-
SELECT students.name,marks.sub,marks.marks
FROM students
INNER JOIN marks ON
students.student_id=marks.student_id;

SELECT students.name,marks.sub,marks.marks
FROM students
LEFT JOIN marks ON
students.student_id=marks.student_id;

SELECT students.name,marks.sub,marks.marks
FROM students
RIGHT JOIN marks ON
students.student_id=marks.student_id;

SELECT students.name,marks.sub,marks.marks
FROM students
FULL OUTER JOIN marks ON
students.student_id=marks.student_id;

