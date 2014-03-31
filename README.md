mysql_query_class
This is an open source MySQL based query class. By means of that you can write your queries in more efficient way.
Lets start with connection to use this class:
CONNECTION DETAILS: INITIAL DATABASE CONFIGURATION
defined('DB_SERVER') ? null : define("DB_SERVER", "localhost"); defined('DB_USER') ? null : define("DB_USER" , "root"); defined('DB_PASS') ? null : define("DB_PASS" , ""); defined('DB_NAME') ? null : define("DB_NAME" , "database_name");
You will find this code at the begining of the class. Just put your database credentials here and include this class file in to your project.
To use this class you need to create an object of this class.
e.g.
$query = new QUERY();

