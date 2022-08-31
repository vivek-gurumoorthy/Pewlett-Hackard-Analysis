# Pewlett-Hackard-Analysis

## Overview of the analysis: 

The purpose of this analysis is to gain insight into which employees at Pewlett Hackard are likely to retire in the coming years. Additionally, quantifying and categorizing these results assists in helping the company understand the areas from which it is going to lose employees in the future. This information can be used to inform hiring strategies as well as other internal initiatives such as mentoring programs for more junior employees.

## Results:

![image](https://user-images.githubusercontent.com/108832056/187738089-e1eb62c0-32ef-4f01-837f-e1ef7637ae69.png) 

- This count is derived from the number of rows in the retirement_titles.csv. This initially makes it seem as if 133,776 employees are retiring, which would be a completely staggering number. Then, once it has been noted that this includes multiple titles per employee, it makes it clear that this isn't an accurate depiction of the data.

![image](https://user-images.githubusercontent.com/108832056/187738326-1993f08e-ea21-4475-a1c2-1d300610842c.png)

- This count is the number of rows in the unique_titles.csv. This makes sure that each employee number in the table will be distinct, precluding the possibility of having an inaccurate count of the number of retiring employees. Now, we can see the most recent title for each employee due to having ordered by date descending. This displays the importance of cleaning the data, as the count now shows 72,458 employees instead of 133,776. This is still a large number, but at least it is accurate.

![image](https://user-images.githubusercontent.com/108832056/187740510-2a811191-cf74-42f8-878a-d09c1b56a55c.png)

- This is the information from the retiring_titles.csv. While the previous table helped inform stakeholders of how many total employees will need to be replaced and their titles, this table groups all titles from the last table into one easily viewable form. Clearly, both Senior Engineer and Senior Staff are titles from which a significant number of employees are being lost in the near future, while Assistant Engineer and Manager have many fewer vacancies that will open due to eventual retirements. Based on the titles that have higher counts in this table, those positions can be targeted more aggressively in hiring ventures.

![image](https://user-images.githubusercontent.com/108832056/187741454-530a6537-fdad-473a-96f3-0ca38f146f99.png)

- This counts the number of employees currently eligible for the mentorship program. This number 1,549, is significantly smaller than the number of soon-to-be retirees, 72,458. This may be a worrying sign.

## Summary: 
* How many roles will need to be filled as the "silver tsunami" begins to make an impact?

According to the count of the unique_titles.csv table, 72,458 roles will need to be filled as senior employees begin to retire.

* Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

While having 1,549 employees eligible for the mentorship program seems promising, the fact that they have to mentor nearly 72,458 new hires in total seems a bit daunting. It will be possible, but perhaps not as invidualized mentorship as originally envisioned. 

Other inquiries that would inform hiring and mentorship strategies include:

1. Categorizing all employees in unique_titles.csv by department. While it is useful to understand that a Senior Engineer or Senior Staff role may be needed, it would be additional informative to understand the department from which the largest number of these employees are retiring. 
2. Aggregating a list of all titles, present and previous, for those eligible for the mentorship initiative would provide a good idea of the specific roles on which these employees could provide mentorship. Especially for those with many previous roles, because of the dearth of eligible mentors, these employees will likely have to train many newer employees.
