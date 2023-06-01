# Spring-Data-JPA-Relationships

teach stack : JAVA, spring boot, soring data jpa

Spring data JPA: is an abstraction of the JPA and hibernate
__________________________________________________________________________________________________________________
One to many:
One teacher can have many subjects
Post http://localhost:8080/teachers
Put http://localhost:8080/subjects/1/teacher/1
Many to one- many subjects can have 1 teacher
Many to many
Many subjects can have many students
So create a table with both of their id’s and store it so when we use http://localhost:8080/subjects/1/students/1  put request to map students to subjects in the new table it will be stored
![image](https://github.com/shwethaj1104/Spring-Data-JPA-Relationships/assets/107784718/10bc5873-cc29-4c72-9e9e-dfd6412f1c5c)

![image](https://github.com/shwethaj1104/Spring-Data-JPA-Relationships/assets/107784718/d480176a-22c2-4642-9114-5f2642a0a265)

![image](https://github.com/shwethaj1104/Spring-Data-JPA-Relationships/assets/107784718/5cd84367-e6b7-44a7-be41-fb7a6cf6a9ef)

After assigning student 1 to subject 1  : list of subjects will be 
![image](https://github.com/shwethaj1104/Spring-Data-JPA-Relationships/assets/107784718/1e9a00e5-0cfc-4149-b728-173131ad8858)

assigning teacher 1 to subject 1
![image](https://github.com/shwethaj1104/Spring-Data-JPA-Relationships/assets/107784718/965263ed-f4cd-4808-a061-b7f3354afc47)

After assigning teacher 1 to subject 1
![image](https://github.com/shwethaj1104/Spring-Data-JPA-Relationships/assets/107784718/8f231d6e-6987-438e-9f61-e9f1f5c14e6d)

After assigning teacher 1 to subject 2
![image](https://github.com/shwethaj1104/Spring-Data-JPA-Relationships/assets/107784718/9e0a0528-a09c-4d0c-9ac1-d2951f078b52)

![image](https://github.com/shwethaj1104/Spring-Data-JPA-Relationships/assets/107784718/1ee03dab-b089-4c00-9cea-2e69063b4e97)

![image](https://github.com/shwethaj1104/Spring-Data-JPA-Relationships/assets/107784718/9e32d11c-0298-46df-b7a5-42c3d61d5c8c)

