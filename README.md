# python-api-challenge

## removing spaces in cities with spaces in their names and replacing them with +
- City names often have spaces in their names. In order for the url to properly read the correct city name, I had to find a way to replace the spaces in the city names to "+". Documentation for that process is here:
- https://www.geeksforgeeks.org/python-remove-spaces-from-a-string/#

## Time stamp conversion to readable format
- apparently, the "dt" data in the city weather responses is in seconds since the "epoch" time, which is 1/1/1970.
- I found that a common way to convert this time stamp into a readable format is to use the "gmtime" method. 
- the result gives year, month, day, hour, minute, and second within a "time structure" datatype

-formatting struct_time to a readable format: https://stackoverflow.com/questions/19319370/how-do-you-convert-a-python-time-struct-time-object-into-a-iso-string

- gmtime documentation: https://www.tutorialspoint.com/python/time_gmtime.htm#:~:text=Pythom%20time%20method%20gmtime(),by%20time()%20is%20used.
- 

### converting time_struct outputs to YYYY-MM-DD HH:MM:SS
https://stackoverflow.com/questions/19319370/how-do-you-convert-a-python-time-struct-time-object-into-a-iso-string
