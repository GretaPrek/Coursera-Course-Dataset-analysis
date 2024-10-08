Objective:

Perform exploratory data analysis (EDA) on a given dataset.
Utilize Pandas for data manipulation and cleaning.
Visualize data using Matplotlib and Seaborn.

Dataset:

Coursera Course Kaggle dataset, https://www.kaggle.com/datasets/siddharthm1698/coursera-course-dataset 
This dataset contains mainly 6 columns and 890 course data. The detailed description:
course_title : Contains the course title.
course_organization : It tells which organization is conducting the courses.
course_Certificate_type : It has details about what are the different certifications available in courses.
course_rating : It has the ratings associated with each course.
course_difficulty : It tells about how difficult or what is the level of the course.
course_students_enrolled : It has the number of students that are enrolled in the course.

Data Preparation:

Data loading process using Pandas.
Handling of missing values and duplicates. No duplicates, outliers was not removed from the data.

Exploratory Data Analysis (EDA):

3 course Certificate types, and only 12 courses for professional serticifate.
Course counts drops as course difficulty increases. For example Beginner level has 487 courses and advanced only 19.
No correlations between ratings and enrolled students amount.

Data Modification:

Data types object, numeric and categorical. Two columns converted from object to categorical data types.
Langdetect library was used for title analysis. 13 different languages in the courses was found.
Enrolled students amount value was replaced taken out k and m indicating thousands and millions accordingly.

Summary and Conclusions:
Insights
1. Data set has 6 features and 891 rows.
2. Data set contains numerical, categorical and object data value types.
3. Most courses are providing University of Pensilvania. 59 courses in total.
4. Most amount of students 3.2 million are enrolled in course 'Machine Learning' By Standorf University.
5. Two highest rated courses has lowest amount of enlisted students.
6. Course amount decrease with increasing course difficulty.
7. Courses have 13 different languages.
8. Two numerical features course_rating and course_students_enllisted do not have linear relations. Correlations are close to zero.
9. There are only 12 professional sertificate courses out of 891.
10. Dataset covers more than 80 millions students enrolled. Although it's not clear how many stydents have more than 1 course.


Suggestions for improvements
1. Bigger data sample. More features to explore.
2. Research trends with foreign languages, foreign universities.
3. Include graphical materials for visualisation world wide coursera courses data. Example, spanish speaking reagions compare with amount of french language enlisted students.


Visualizations:

Types of visualizations used histograms, scatter plots, box plots.


Dependencies:

Required Python libraries pandas, numpy, matplotlib, seaborn, scipy, langdetect. Requirements.txt file added.
