# Turkiye-Student-Evaluation-Analysis - Clustering
![why-study-in-turkey](https://github.com/Abhi2850/Turkiye-Student-Evaluation-Analysis---Clustering/assets/91343400/0ab8edab-62c9-411a-b03d-fcd9514febab)


Tools Used🛠: Python, Pandas, Machine Learning, Matplotlib, Scipy, Scikit-learn,Cluster

🔗dataset link --> https://www.kaggle.com/datasets/onsrajhi/turkiye-student-evaluation-analysis-clustering

# Objective
Discovering insights from Turkiye student evaluations using Python. This project covers clustering techniques to analyze and understand student feedback. By using Clustering algorithm, classified the Bad, Neutral and Good feedback given by students from Clusters formed.

## Attribute Information:
1. instr: Instructor's identifier; values taken from {1,2,3}
2. class: Course code (descriptor); values taken from {1-13}
3. repeat: Number of times the student is taking this course; 4.4.values are taken from {0,1,2,3,...}
4. attendance: Code of the level of attendance; values from {0, 1, 2, 3, 4}
5. difficulty: Level of difficulty of the course as perceived by the student; values taken from {1,2,3,4,5}
6. Q1: The semester course content, teaching method and evaluation system were provided at the start.
7. Q2: The course aims and objectives were clearly stated at the beginning of the period.
8. Q3: The course was worth the amount of credit assigned to it.
9. Q4: The course was taught according to the syllabus announced on the first day of class.
10. Q5: The class discussions, homework assignments, applications and studies were satisfactory.
11. Q6: The textbook and other courses resources were sufficient and up to date.
12. Q7: The course allowed fieldwork, applications, laboratory, discussion and other studies.
13. Q8: The quizzes, assignments, projects and exams contributed to help the learning.
14. Q9: I greatly enjoyed the class and was eager to actively participate during the lectures.
15. Q10: My initial expectations about the course were met at the end of the period or year.
16. Q11: The course was relevant and beneficial to my professional development.
17. Q12: The course helped me look at life and the world from a new perspective.
18. Q13: The Instructor's knowledge was relevant and up to date.
19. Q14: The Instructor came prepared for classes.
20. Q15: The Instructor taught in accordance with the announced lesson plan.
21. Q16: The Instructor was committed to the course and was understandable.
22. Q17: The Instructor arrived on time for classes.
23. Q18: The Instructor has a smooth and easy to follow delivery/speech.
24. Q19: The Instructor made effective use of class hours.
25. Q20: The Instructor explained the course and was eager to be helpful to students.
26. Q21: The Instructor demonstrated a positive approach to students.
27. Q22: The Instructor was open and respectful of the views of students about the course.
29. Q23: The Instructor encouraged participation in the course.
30. Q24: The Instructor gave relevant homework assignments/projects, and helped/guided students.
32. Q25: The Instructor responded to questions about the course inside and outside of the course.
33. Q26: The Instructor's evaluation system (midterm and final questions, projects, assignments, etc.) effectively measured the course objectives.
34. Q27: The Instructor provided solutions to exams and discussed them with students.
35. Q28: The Instructor treated all students in a right and objective manner.


Q1-Q28 are all Likert-type, meaning that the values are taken from {1,2,3,4,5}

## Steps
1. Imported necessary Python libraries and load the Dataset.
2. Preprocess the data and perform EDA.
3. Find the correlation between the variables.
4. Reducing the dimenssion using the Principal component analysis(PCA) for dimensionality reduction for better practice.
5. Initiated the clustering mechanism using Kmeans.
6. Plotted the Elbow plot for best Clusters.
7. separated the segments.

# Output

![km 1](https://github.com/Abhi2850/Turkiye-Student-Evaluation-Analysis---Clustering/assets/91343400/6117190a-0e3f-4edd-86fd-58e422ce8b0d)

