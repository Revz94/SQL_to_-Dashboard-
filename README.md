# SQL to Interactive Dashboard 
![Screenshot 2023-08-02 101724](https://github.com/Revz94/SQL_to_-Dashboard-/assets/74944663/33e847d2-34b3-4943-8955-969029ca8bd1)


### Pizza Resturant Database to Interactive Dashboard

###### Scenario:
          •Design and build a tailor-made bespoke relational database for a newly opened pizza restaurant business that will allow capturing and storage of all the important information and data that the business generates. This will turn help to monitor business performance in dashboards.

###### Approach:
          Designing database and the tables in it is to spec out all of the field for the data we want to collect.Then Normalizing the data by adding more related tables and defining the table relationship 

###### Database Features
           1. Main Area of focus:
                  *Orders
                  *Stock Control
                  *Staff
           2.  Orders Data Required:
                   *Order ID
                   *item name
                   *item Price
                   *quantity
                   *coustomer name
                   *delivery address
           3. Stock Control Reqirements
                  1.When its time to order new stock
                  2.What ingredients go into each pizza and their quantity based on the size of the pizza
                  3. existing stock level
                  4. we will assume the lead time for delivery by suppliers is the same for all ingredients 
           4. Staff Data Requirements
                  1.which staff members are working and when
                  2.Based on the staff salaray information,howmuch each pizza costs
###### Dashboard Features
           1.Dashboard -1  Order Activity
                     *Total Orders
                     *Total Sales
                     *Total items
                     *Average order value
                     *Sales by category
                     *top selling items
                     *order by hour
                     *sales by hour
                     *sales by address
                     *orders by address
                     *orders by delivery/pickup
           2.Dashboard -2 Inventory Management 
                     *total quantity by ingredient 
                     *total cost of ingredient
                     *calculated cost of pizza
                     *percentage stock remaining by ingredient
                     *list of ingredients to reorder based on remaining inventory 
           3.Dashboard -3 Staff Activity
                      *total staff cost
                      *total hours worked
                      *hours worked by staff member
                      *cost per staff member

###### Technology Used
           1.Design and Model Database: Use MySQL Workbench to design and model MySQL database schema. Create tables, define relationships, and populate the database with relevant data.
           2.Connect Looker Studio to MySQL Database: In Looker Studio, set up a connection to  MySQL database using the necessary connection details (host, port, username, password). This connection will allow Looker to access the data in  MySQL database.
           3.Define Data Models in Looker: In Looker Studio, create data models that map to the tables and views in your MySQL database. Looker provides a modeling layer that allows you to transform and aggregate data for analysis.
           4.Build Dashboards and Reports: With the data models defined,  use Looker Studio's drag-and-drop interface to build interactive dashboards and reports.Visualizations can be created based on the data models you defined. 
                      
