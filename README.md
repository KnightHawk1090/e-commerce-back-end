# e-commerce-back-end

## User Story

```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
```

### GitHub Repository
https://github.com/KnightHawk1090/e-commerce-back-end

### Link to Video Demonstration

https://drive.google.com/file/d/194YTjqTJ7EyNbRzgot1U7HKD9oOoGILS/view

### Image Preview

![Screenshot (42)](https://user-images.githubusercontent.com/121210332/236982157-0263bea2-6eb4-457a-920b-c12fce211fc8.png)


### DISCLAIMER
```
Before running appliction, add proper password to access personal SQL db in the .env file. 
DB_NAME='ecommerce_db'
DB_USER='root'
DB_PW='xxxxx'
```
