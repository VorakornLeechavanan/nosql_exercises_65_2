## nosql_exercises_65_2

# Question 1
**Question: You're creating a database to contain a set of sensor measurements from a two-dimensional grid.
Each measurement is a time-sequence of readings, and each reading contains ten labeled values.
Should you use the relational model or MongoDB? Please justify your answer** <br />

# Question 2

**Question: For each of the following applications <br />
a. IoT <br />
b. E-commerce <br />
c. Gaming <br />
d. Finance <br />
Propose an appropriate Relational Model or MongoDB database schema. For each application,
clearly justify your choice of database.**

Answer: <br />

**- IoT** <br />
The MongoDB database schema will be more appropriate because it will consume less space and it is written more rapid than the Relational Model <br />

**- E-commerce** <br />
The Relational Model will be more appropriate because the system is complex, the relation between clients and dealer need to be provided clearly <br />

**- Gaming** <br />
The MongoDB database will be more appropriate because the video games need to collect player's information and other details, so it requires a large and flexible database <br />

**- Finance** <br />
The Relational Model will be more appropriate because the database needs to be able to collect an enormous size of accounts, customers and financial evidence. Furthermore, the transaction needs to be implemented accurately to ensure that no errors are happened <br />


# Question 3
**Question:** <br />
**Create MongoDB database with following information.** <br />


|                                                                      |
|----------------------------------------------------------------------|
| 1) ({"name":"Ramesh","subject":"maths","marks":87})                  |
| 2) ({"name":"Ramesh","subject":"english","marks":59})                | 
| 3) ({"name":"Ramesh","subject":"science","marks":77})                |
| 4) ({"name":"Rav","subject":"maths","marks":62})                     |
| 5) ({"name":"Rav","subject":"english","marks":83})                   |
| 6) ({"name":"Rav","subject":"science","marks":71})                   |
| 7) ({"name":"Alison","subject":"maths","marks":84})                  |
| 8) ({"name":"Alison","subject":"english","marks":82})                |
| 9) ({"name":"Alison","subject":"science","marks":86})                |
| 10) ({"name":"Steve","subject":"maths","marks":81})                  |
| 11) ({"name":"Steve","subject":"english","marks":89})                |
| 12) ({"name":"Steve","subject":"science","marks":77})                |
| 13) ({"name":"Jan","subject":"english","marks":0,"reason":"absent"}) |

**Give MongoDB statements (with results) for the following queries** <br />
• Find the total marks for each student across all subjects.
• Find the maximum marks scored in each subject.
• Find the minimum marks scored by each student.
• Find the top two subjects based on average marks.


**The result of creating the database "Grades"**

call InsertMany to add many records in a row <br />

![Image 29-3-2566 BE at 22 58](https://user-images.githubusercontent.com/92812914/228854854-60ee1c2f-c873-40e8-8dfe-063d343a943c.jpeg)

![Image 29-3-2566 BE at 22 57](https://user-images.githubusercontent.com/92812914/228854828-0b36bf66-a175-4e1d-a854-550be2f2889d.jpeg)



_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ <br />



**The result of all 4 statements**

![Image 29-3-2566 BE at 22 57](https://user-images.githubusercontent.com/92812914/228854784-5496062f-8dc9-49f0-bc84-0caa65f70e07.jpeg)


Find the total marks for each student across all subjects <br />

![IMG_4740](https://user-images.githubusercontent.com/92812914/228853988-cd0c0a47-d236-42c2-9e1c-c83b9eb9c08f.jpeg)


Find the maximum marks scored in each subject <br />

![IMG_4741](https://user-images.githubusercontent.com/92812914/228854007-3f69eecc-cbeb-42b9-acb3-722e048547b0.jpeg)


Find the minimum marks scored by each student <br />

![IMG_4742](https://user-images.githubusercontent.com/92812914/228854010-e7c1e399-69fe-43ef-819f-a5a6e28bfc84.jpeg)


Find the top two subjects based on average marks <br />

![IMG_4744](https://user-images.githubusercontent.com/92812914/228854014-bc9ef419-c4af-4f35-8761-f84abafeff28.jpeg)
