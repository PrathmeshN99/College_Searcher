# College_Searcher 

AIM: To develop a website displaying sorted college sorted and filtered by college preferences  and one’s percentile score.


For a science student aiming at engineering, at the time of counselling, it becomes difficult for one to select an engineering college and branch according to one’s percentile score in an exam like Joint Entrance Exam(JEE) or Maharashtra Common Entrance Test (MHT CET). 

A lot of time is consumed when we need to check every college website or search the college name in document containing percentile cutoffs of a round

This project intends to address this issue by searching and sorting data according to one’s percentile and college preference

This data was extracted to csv using regular expressions (regex) from a pdf of the State Common Entrance Test Cell's Cut Off List of All India Seats CAP Round I for the academic year 2021-22.

Technology used: 

Python libraries pdfplumber, re, pandas, namedtuple
Regular expressions (Regex)
Django python framework
Sqlite database 
HTML, CSS
Jupyter Notebook

![search_college1](https://user-images.githubusercontent.com/90515944/171365687-50d00edd-4b39-4bc6-8f22-d7a6bce7378e.png)

View all colleges 

![search_college3](https://user-images.githubusercontent.com/90515944/171365451-adf58ea2-725b-4557-9f5f-dace1ced05fb.png)

Search college by keyword 'Vishwakarma' and 95 percentile

![search_college2](https://user-images.githubusercontent.com/90515944/171365939-fb5638a2-4cb3-42be-a653-20409b46b7fc.png)


College Searcher is a website developed using Django, a python-based web framework.  The project offers a platform that makes it simple for students who have graduated from their 12th grade to choose an engineering college based on their preferences and percentile score. The percentile cutoffs issued by the test body for various universities are not easily navigable, and it is most surely difficult to maintain track of every record accessed. Through data searching and sorting based on percentile and college selection, this study attempts to address this problem. This data was extracted from a pdf of the State Common Entrance Test Cell's Cut Off List of All India Seats CAP Round I for the academic year 2021–22 and converted to a csv file using regular expressions (regex) in Python. This data was inserted into tables in the SQLite3 database which was then retreived by the website to display the results. With a user-friendly interface designed using HTML and CSS, the website provides the ability to search by percentile-cutoffs as well as colleges in a sorted manner. The current website is also getting new features, such the ability to filter colleges by region

One of the new techniques I utilised in this project was to extract data from PDF pages line by line using Python's Regular Expressions (regex). Additionally, creating adequate tables for the models' SQLite3 databases. It was a challenge to store the college data in the SQLite3 database because each column has its own value ranges and data types. When using relational databases, it's important to consider how the tables link to each other and to maintain database integrity, as doing otherwise could result in the application returning incorrect or garbage results for some invalid inputs. It was also novel to me to manage a large number of links (urls) and direct them to the appropriate output based on the input. This project was made worthwhile by using all the retrieved data to create a user-friendly interface using HTML and CSS, as well as to display and adjust it in accordance with the needs of a student. Overall, it was a terrific learning experience for me, even though I sometimes got stuck for a long when errors occurred. Eventually, the project was completed and is now functioning.
