# php-intern-test
This is a simple backend test using PHP to measure candidate's knowledge and improvement.

## Goal
The goal for this test is just to know how much a candidate can improve their skills during the test.

## Challenges
1. Learn GIT and use it
2. Fork this repository to your GitHub account
3. Make use of git along all development
3. Install Laravel framework
4. Create a basic table for Product Types on database (script bellow in the next section)
5. Create a basic Product's CRUD (Create, Read, Update and Delete), containing:
    1. Id
    2. Description
    3. Quantity
    4. Value
    5. Product Type
6. Commit all that you have done the way you want
7. There are some docker files in this repository. What they do? (This step is not necessary)

## Product Types Table Script
```sql
CREATE TABLE product_types(
    id int not null primary key auto_increment,
    name varchar(255) not null,
    created_at timestamp DEFAULT CURRENT_TIMESTAMP,
    updated_at timestamp DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP
);

INSERT INTO product_types (name) VALUES ('Food'), ('Clothing'), ('Personal Care'), ('Babe');
```
