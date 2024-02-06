# Employee-Project-Management-System
**Project Overview:**
The Employee Project Management System aims to streamline project management tasks by organizing employee data, project details, and seniority levels into a cohesive system. It involves data preprocessing, manipulation, and analysis using Python's pandas library.
**Project Components:**
1. **Data Preprocessing:** Initial data is provided in three separate CSV files: Employee, Seniority Level, and Project. These files are loaded into pandas DataFrames for further processing.
2. **Missing Values Handling (Task 2):** The missing values in the 'Cost' column of the Project DataFrame are replaced with the running average computed using a for loop.
3. **Data Transformation (Task 3):** The 'Name' column in the Employee DataFrame is split into 'First Name' and 'Last Name', and the original 'Name' column is dropped.
4. **Data Integration (Task 4):** All three DataFrames are merged into a single DataFrame called 'Final', combining employee details, seniority levels, and project information.
5. **Bonus Calculation (Task 5):** A new 'Bonus' column is added to the 'Final' DataFrame, providing a 5% bonus to employees who have completed projects.
6. **Designation Level Adjustment (Task 6):** Designation levels are demoted by 1 for employees with failed projects, and records of employees with designation levels above 4 are deleted.
7. **Data Transformation (Task 7):** Prefixes ('Mr.' or 'Mrs.') are added to the 'First Name' column based on gender, and the 'Gender' column is dropped.
8. **Designation Level Promotion (Task 8):** Designation levels are promoted by 1 for employees above 29 years of age.
9. **Total Project Cost Calculation (Task 9):** The total project cost for each employee is computed by grouping the data by 'ID' and 'First Name' and summing the 'Cost' column.
10. **Data Filtering (Task 10):** Employees whose city name contains the letter 'o' are filtered from the DataFrame.
**Performance Evaluation:**
All tasks are completed using pandas functions and methods, demonstrating proficiency in data manipulation, transformation, and analysis. The project showcases skills in data preprocessing, handling missing values, merging datasets, and deriving meaningful insights from the data.
**Conclusion:**
The Employee Project Management System provides a comprehensive solution for managing employee data and project details efficiently. By automating repetitive tasks and providing insights into employee performance, it enhances decision-making and improves project management processes.
