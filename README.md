# Integrating-Power-Apps-to-Power-BI Via Azure SQL

![PowerApps Integration](https://github.com/user-attachments/assets/74f117cd-a4a2-4b01-af87-d1fa5429a460)

# Introduction

Integrating Power Apps with Power BI unlocks the full potential of data-driven automation, enabling businesses to streamline processes, enhance decision-making, and drive efficiency. By combining the interactive reporting capabilities of Power BI with the dynamic and customizable features of Power Apps, users can not only visualize data but also take immediate action within the same interface. Whether you're looking to fully automate workflows or implement semi-automated solutions, this integration empowers you to create end-to-end solutions that connect insights to actions, transforming how your organization operates and responds to data.

# Problem Statement
A key challenge faced in the real life industry is maintenance of data that is not in stored in the company's database. Few times we have information/data that comes to the analyst via email which requires constant update if this is integrated to a report that is used by stakeholders. To keep this report up to date with the latest data can be a challenge if not properly maintained.

# Methodology
- Creating a table in Azure SQL database
- Integrating the Azure SQL database with Power Apps
- Creating a form users will use in power apps
- Integrating the Azure SQL databse with Power BI
- Carrying out analysis with the data provided to Power BI

# Creating the Required Table in Azure SQL

The table was created used SQL as shown below:

![Creating Table on Azure](https://github.com/user-attachments/assets/d0174c6f-2707-472e-b884-a817c9317440)

The employee table created is an empty table with just the columns created. I ran a query to ensure the table was created successfully

![Testing the Azure Table](https://github.com/user-attachments/assets/898c34ac-06a9-4a53-95d8-c163780d8c69)

#  Integrating the Azure SQL database with Power Apps

Login to power apps and choose create. Then choose SQL server

![Click create and choose SQL](https://github.com/user-attachments/assets/398448c5-2e7d-4ee8-b4de-48762a80c7b2)

Choose  SQL Authentication and login with your credentials

![Choose SQL Authentication and connect to cloud](https://github.com/user-attachments/assets/4b8e6e7e-732a-446c-b187-71b713e4c3b5)

Choose the employee table created on Azure SQL database

![Choose the Employee table created on azure sql](https://github.com/user-attachments/assets/2a7f6e57-dc96-4410-b7e3-8a76e9d226a2)

# Creating a form users will use in power apps

Power Apps then uses the employee table chosen to automatically create a form for you as seen below.

![Power Apps Auto creates the form for you afetr connection](https://github.com/user-attachments/assets/1a066a00-80ad-456c-b15c-3bc18f944559)

Click on the play button to add records

![Click Play to add Data](https://github.com/user-attachments/assets/2cf0cc07-1893-4c09-a18e-0ef4dbf7bb12)
