# verifypunkMVC
# Mini PHP framework

Mini PHP framework created by [Brad Traversy](https://github.com/bradtraversy) through his udemy course. Customized by me and used as base for integrating and testing new technologies.

### Disclaimer

It's not advisable to use this for live projects as this is still an alpha project I'm using to learn and exercise.
If you are inclined to help with bugs corrections and developing new features you are free to do so.

## Getting Started

Copy the project in your folder and install the database dump in your PhpMyAdmin.
Follow the instructions to complete the installation.

### Prerequisites

* Apache Server
* PHP 5.6+
* Node.js
* Mysql Database


Install [XAMPP](https://www.apachefriends.org/it/index.html) for an easy quickstart


### Config File

Modify the app/config/config.php file according to your needs. You can use example.config.php file inside the same folder as an example based on my local settings.

```
//Database Configuration
define('DB_HOST', 'localhost');
define('DB_USER', '_YOUR_USER');
define('DB_PASS', '_YOUR_PASS');
define('DB_NAME', '_YOUR_DBNAME');
```


### htaccess file

Modify che .htaccess file inside the public folder to match the name of your installation folder

### Install the Database

Create a database of your choice in PhpMyAdmin.


## Built With

* PHP


## Authors

* **Brad Traversy** - *Initial work* - [Brad Traversy](https://github.com/bradtraversy)


## License

This project is licensed under the MIT License

