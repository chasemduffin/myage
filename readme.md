## myage

### time()

The time() function subtracts a date object representing your birthday from a date object representing the current time to produce the number of seconds you have been alive.

It then divides that value by the number of seconds in a year (times 1000 to account for default extra precision of Date objects), and updates a given html element by its id.

### refresh()

The refresh() function calls the time() function at a given interval.

The value assigned to _refresh_ is the refresh rate in milliseconds.

### span id='timer'

The html element on the page to be updated.