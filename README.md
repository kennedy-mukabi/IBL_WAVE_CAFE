# IBL_WAVE_CAFE
* SCCJ/01446/2019
* Kenneth Mukabi Ombatsa 
* github link: https://github.com/kennedy-mukabi/IBL_WAVE_CAFE
* email: kenkingmukabi@gmail.com
* project Title : cafe order collection system 

![alt text](https://github.com/kennedy-mukabi/IBL_WAVE_CAFE/blob/main/Screenshot%20at%202021-12-31%2018-44-47.png?raw=true)

# objective: 
To automate Order collection and delivery of drinks to minimize on human error resulting from staff collectiong the orders , and to fasten the process of order collection at the cafe

# project Description: 
The project was created using Php languange for the backend and HTML for frontend


# Functionalities :
* the website will register and log in new customers to the cafe
* the website will give a menu of available drinks in the cafe with their specific price tag
* the website will be used to collect orders from the cafe’s customers

## Installation on a local machine

install xampp

create database using Mysql

```bash
CREATE TABLE `users` (
  `id` int(11) NOT NULL AUTO_INCREMENT PRIMARY KEY,
  `username` varchar(100) NOT NULL,
  `email` varchar(100) NOT NULL,
  `user_type` varchar(100) NOT NULL,
  `password` varchar(100) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=latin1;
```

## Usage

Clone the repository
save files to htdocs under xampp files
open the browser 127.0.0.1 to view your database 
to get to a web page initiate the path with localhost/
