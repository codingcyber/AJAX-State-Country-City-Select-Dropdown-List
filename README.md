# AJAX-State-Country-City-Select-Dropdown-List
Ajax Country State City Select Dropdown List with PHP &amp; JavaScript

## Setup the Script
1. Download the Script & Download Database SQL file from <a href="https://github.com/hiiamrohit/Countries-States-Cities-database">here</a>
2. Extract it into web directory
3. Create a Database with the name of **ajax-country** & import the SQL file into the database
4. Configure the Database Credentials in **index.php**, **cities.php**, **states.php**. You will find this code from line numbers 2 to 9
```php	
$connection = mysqli_connect('localhost', 'root', '');
if(!$connection){
	die("Database Connection Failed" . mysqli_error($connection));
}
$selectdb = mysqli_select_db($connection, 'phpajax');
if(!$selectdb){
	die("Database Selection Failed" . mysqli_error($connection));
}
```

# For Complete text Article and Video Tutorials checkout these links
<a href="https://codingcyber.org/ajax-country-state-city-select-dropdown-list-7698/">Create Ajax Country State City Select Dropdown List</a>