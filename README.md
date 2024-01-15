This script generates a report that shows all patients in the UCC or ICU with a serum specimen recieved in lab that also have a Microbiology test in lab from 4:00 am the day the script is run to the current time the script is run. If it is run after 10:05 am the start time for the query will be 10 am of the current day.

Two sql statments query cerner. One for the serum test results and one for the Microbiology test results. An inner join is performed on these two data sets so that the data set produced shows all patients with a serum test that also have a microbiology test in lab.

This report will be used to enroll serum specimens in a microbiology research study and allow the microbiology research team to request serum specimens from chemistry in a timley manner.
