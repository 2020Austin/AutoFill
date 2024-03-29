### Motivation

Our campus' temporary gym has a reservation-only system due to the pandemic and construction. 
The reservation request webform is very clunky and repetitive - lots of click inputs are needed to select info (like calendar dates) and it's the same information every time.
This python script uses Selenium and the Chrome webdriver to automate the process. When ran with command line, it will fetch a list of possible times for tomorrow:

Example possible time output (extracted from html):

```
|  -times-   |
--------------
|  7:00 am   |
|  8:00 am   |
|  9:00 am   |
|  10:00 am  |
|  11:00 am  |
|  12:00 pm  |
|  1:00 pm   |
|  2:00 pm   |
|  3:00 pm   |
|  4:00 pm   |
|  5:00 pm   |
|  6:00 pm   |
|  7:00 pm   |
```

I can then input a pre-saved name to fill out the rest of the data automatically, and make the reservation. With pre-saved names, I can reserve for friends as well
