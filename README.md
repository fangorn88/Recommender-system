# Recommender-system
Creating a recommender system framework from the DBLP Computer Science Bibliography dataset 

Connecting people with people is a central task in an important class of applications. Searching for mentors and matching mentors with mentees is a good example of such application. For this assignment, we'd like you to design and implement a prototype of a recommender system for mentor-mentee matching. Such a recommender system should match mentors with mentees by considering their attributes and preferences. For the mentors the system should store their inferred attributes from the data corpora, specifically their expertise on a particular topic. For the mentees the system should capture their preferences, which come from a certain ontology of the topics.
As an input data set to be used to retrieve the mentors, infer the topics and measure mentor's expertise level, please use one of the two datasets: 

- the Enron Email dataset available here: http://www.cs.cmu.edu/~./enron/enron_mail_20150507.tgz, where mentors will be the email senders and topics will be inferred from the email message body,

- the DBLP Computer Science Bibliography dataset, available here: http://dblp.uni-trier.de/xml/, where mentors will be the authors and topics will be inferred from the titles of their publications.


In the final presentation you'll have to justify and explain the following:
•	design choices behind the prototype of your recommender system
•	methods and libraries used for topic extraction
•	proposed metric used for measuring the level of expertise of a mentor
•	proposed recommendation method
You will need to also propose a method for quantifying the performance of your recommender system.

There are two codes that need to be run: 

1. wrapper.py - parses the xml file and extracts fieldFile.txt which contains the information about authors and the titles of their publications
2. end_to_end_recom_system.ipynb - this code contains data manipulation, topic extraction, scoring mechanism and the final recommendation for mentor-mentees
