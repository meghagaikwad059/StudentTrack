# StudentTrack -  PHP Complete CRUD Application
StudentTrack : Utilizing CRUD (Create, Read, Update, Delete) operations, This project serves as an excellent example for understanding CRUD operations and their implementation in a real-world application.

# PHP Complete CRUD Application

### ****Creating the Database Table****

Create a table named *student* inside your MySQL database using the following code.

```sql
CREATE TABLE `student` (
  `id` int(255) NOT NULL AUTO_INCREMENT,
  `first_name` varchar(255) NOT NULL,
  `last_name` varchar(255) NOT NULL,
  `email` varchar(255) NOT NULL,
  `gender` varchar(255) NOT NULL,
  PRIMARY KEY (`id`)
)
```

### ****Copy files to htdocs folder****

Download the above files. Create a folder named *student* inside *htdocs* folder in *xampp* directory. Finally, copy the *student* folder inside *htdocs* folder. Now, visit [localhost/student](http://localhost/php-crud-yt-main/index.php) in your browser and you should see the application.

