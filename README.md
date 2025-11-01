The project demonstrates practical MongoDB (NoSQL) operations to manage academic data, including students, faculty, courses, and activities.
It covers querying, aggregation, updating, and joining collections—showing how NoSQL databases handle complex relationships and analytics without using SQL joins.


---

🧮 Key Sections & Highlights:

1. Complex Filters & Projections

Filters students with >85% attendance and skills in both MongoDB and Python.

Finds faculty teaching more than two courses using $size and $match.


2. Joins and Aggregations ($lookup)

Joins students, courses, and enrollments collections to show student-course relationships.

Uses $group and $lookup to find total students and average marks per course.


3. Grouping, Sorting, and Limiting

Finds top 3 students by average marks using $group, $sort, and $limit.

Determines the department with the highest number of students.


4. Update, Upsert, and Delete

Increases attendance to 100% for students who won Hackathons.

Deletes old activities (before 2022).

Upserts a course (“Data Structures” → “Advanced Data Structures”) to ensure up-to-date data.


5. Array & Operator Usage

Finds students with “Python” skill but not “C++”.

Identifies students participating in both Seminar and Hackathon using $addToSet and $all.


6. Subdocuments & Nested Conditions

Retrieves Computer Science students scoring >80 in Web Development.


7. Advanced Aggregation (Challenge Level)

Joins faculty, courses, enrollments, and students to display student performance per faculty.

Finds the most popular activity type by total participants.
