# 21479_5_Admissions
This project was carried out with the goal of creating a database for Admissions Offices. Originally, the plan was to create a functional database for one admissions office, but with creating two extra entities this database has expanded into being useful for multiple universities trying to admit their potential first year students.

## Authors
-[@dra27013](https://github.com/dra27013)

## Data Model
<img width="871" alt="21479_5 Data Model" src="https://user-images.githubusercontent.com/128402168/229159171-61f6cfee-96fe-4dd1-b511-cab1bbc9be8b.png">

The admissions datamodel contains ten key entities. Admissions office is related to University with a one to one relationship. This siginifies that each University that uses this database will be associated with their own Admissions Office. The office itself has many employees. These Employees have many workers that report to a head of the Admissions office. From employee they conduct many reviews on applications and participate in many interviews part of the application process. These applications have many interviews that take place. This creates a many-to-many relationship between application and employees connecting the two entities. High schools from around the United States have many student who will be creating many applications to get into their University of choice. Each of these students have one transcript and one standardized test results connected to their information. Having all of these factors connected to eachother creates an interconnected data model that portrays the admissions process of student applications.
