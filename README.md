# Course-Search-Engine
CS410 Text Information Systems Kumkum Yadav (kumkumy2@illinois.edu), Garima Garg(garimag2@illinois.edu, Paulami Ray(paulami2@illinois.edu

## INTRODUCTION
Registering for the right courses forms a very integral part in the academic life of the student. Our project aims at solving these hard decisions of the students as per their query and help them in making an informed decision about the courses they can take based on the query. This documentation hence gives the overview of the model and discusses the advantage of this model. It compares the existing model with the proposed model and discusses future enhancements that can be made.

## MOTIVATION
We are blessed with the college that provides us with enough flexibility to choose from a number of courses and learn from a wide range of topics, but this flexibility can also confuse a student and hence handicap him or her from taking an informed decision about the courses he or she wishes to take. The current course explorer of University of Illinois, Urbana Champaign specializes in term matching. It is equipped to give courses per term, per semester and also of a specific department. But it lacks the ability to rank searches based on the user’s input. It does not equip the user with the knowledge of which courses correspond to his or her query but gives all the courses that match the particular user’s input.The users are still confused about which courses they should take. Our model aims at solving this ambiguity by taking the input from the user and applying appropriate natural language processing techniques in the background to achieve the top 20 courses as per the user query thus giving the user a clear idea as to which course he or she should focus on and use that knowledge to register for the courses. The model is hence motivated by the fact of increasing courses and job titles per year. Minute differences between a data analyst and a data scientist which is hard to capture by the user can be easily spotted by the model and hence help the user to make an clear informed decision.

## DATASET
The dataset after scraping and applying data processing techniques consists of 5 columns namely Year , Term , Course_ID , Couse_Name and Course_Description . The dataset is of 795 lines.

## README FOR CODE IMPLEMENTATION
For executing this model one would need Jupyter 5.4.1 installed on their systems. The following steps should be followed to run the project from start to end:

1) Download the course_explorer.zip file to your desktop.
2) Unzip this file and save it on your systems.
3) This folder would consist of files final.ipynb, Scraping and Cleaning.ipynb, images folder, final_worked_new.csv, numbers.txt, README.txt.
4) Run the Scraping and Cleaning.ipynb to generate the scraped dataset.
5) Run the final.ipynb (Note : The final.ipynb uses final_worked_new.csv as manual cleaning was required in the dataset.)
6) Wait for the .ipynb to execute and for the GUI to appear.
7) Enter your query and press “Click Me!”.
8) See the results and plan your coursework!
