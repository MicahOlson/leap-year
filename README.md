# Leap Year Detector

### See if any given year is a leap year.  
_by Micah Olson_

## Technologies Used
* HTML5
* CSS (extended by Bootstrap 4.5.3)
* JavaScript (extended by jQuery 3.5.1)

## Description
Input and submit any year to see if it is a leap year.

## Setup/Installation Requirements
* The web page can be viewed [here](https://micaholson.github.io/leap-year). To edit a local copy yourself, follow the instructions below:  

* Use git to clone the project into your local directory of choice ([how to install git](https://www.learnhowtoprogram.com/introduction-to-programming/getting-started-with-intro-to-programming/git-and-github)):  
  $ cd ~/\[directory-of-choice\]  
  $ git clone https[]()://github.com/MicahOlson/leap-year.git  

* Remove all remotes nicknamed 'origin' pointing to my repository:  
  To view-  
  $ git remote -v  

  To remove-  
  $ git remote rm origin  
* Add new remotes pointing to your repositories of choice:  
  $ git remote add \[location-nickname\] \[location\]  

* Open the files in your editor of choice and have fun!

## Tests
```
Describe: isLeapYear()  
  
Test: "It returns false for years that are not a leap year"    
Expect(isLeapYear(1993)).toEqual(false);
  
Test: "It returns true for years that are divisible by 4"
Expect(isLeapYear(2004)).toEqual(true);  
  
Test: "It returns false for years that are divisible by 100"
Expect(isLeapYear(2100)).toEqual(false);  
  
Test: "It returns true for years that are divisible by 400"  
Expect(isLeapYear(2000)).toEqual(true);
```

## Known Bugs
* No known bugs.
* This project will be under regular development. If you  
find a bug, please let me know at the email address below. 

## License
[GPL](https://choosealicense.com/licenses/gpl-3.0/)

## Contact Information
Micah L. Olson micah@fakemail.com