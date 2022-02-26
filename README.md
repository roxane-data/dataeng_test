# dataeng_test
Technical test from wild code school for data engineer course
It is based on sakila but the address table was modified in order to have real addresses to use geolocalisation API. It's from a mysql dump and mostly a SQL challenge with data manipulation. I use python to modify the data. 
First connect to the database in python with mysqlconnector
request Nominatim to get latitude and longitude from the address table
add this new data in the table
finally make some sql request
