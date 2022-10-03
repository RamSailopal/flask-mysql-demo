# flask-mysql-demo

A simple demo of the Python Flask framework using mysql as a backend

Creates a simple api for adding users to a mysql table


![Alt text](flask.JPG?raw=true "view")


# Provisioning

    git clone https://github.com/RamSailopal/flask-mysql-demo.git
    cd flask-mysql-demo
    docker-compose up
    
# Backend
    
    
On completion of the provisioning of the environment, navigate to http://serveraddress:5000/user to GET and POST data

# Mysql view

     mysql> select * from Users;
     +----+------+-----+-----+
     | id | name | age | sex |
     +----+------+-----+-----+
     |  1 | Ram  | 21  | M   |
     |  2 | Bob  | 52  | M   |
     +----+------+-----+-----+
     2 rows in set (0.00 sec)
     

# Front-end

A crude front-end to demonstate the use of Jinja templates has been added.

To view the front-end, navigate to:

http://serveraddress:5001



