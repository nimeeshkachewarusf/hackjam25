# hackjam2025usf
**Bullish Builders** was created during the 12 hr hackathon HackJam 2025 organized by SHPE USF. It won the best hack in USF track.
It creates a conflict free schedule of classes for your upcoming semester and reduces the common registration load on students. 
You no longer have to spend time bothering your friends about prof recommendations, scroll through Rate My Prof, etc. Bullish Builders selects the class of the Prof who has the highest GPA in previous semesters. It utilizes the data in USF Infocenter which contains GPA wise data for each professor and course. 
Initial plan was to assign 50% weight to Infocenter GPA average and 50% weight to RMP ratings. However, RMP's robots.txt doesnt support web scrapping. To respect this, 100% of the weight is assigned to Infocenter GPA average. 

-> The user list the courses in order of priority, 
-> The program finds the professors teaching the course
-> It looks up Infocenter for GPA average
-> Selects best profs
-> Starts building your schedule
-> If there is a time clash with the best prof for course 1 with best prof for course 2
-> It will retain the best prof for course 1 and select the best non-time conflicting prof for course 2 and so on.
