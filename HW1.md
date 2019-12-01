# Big Data in Online Education  
## Introduction
E-learning generally refers to a kind of web-based Learning behavior, which is similar to the concept of network training. With the explosive development of information technology, online education shows more and more advantages: 1) Online education can break through the limitation of time and space, and improve the learning efficiency; 2) Online education can span the unequal distribution of educational resources caused by the regional and other aspects, make educational resources shared, and reduce the threshold of learning.
According to the survey in 2017, the online education market in China reached 194.12 billion yuan, with more than 110 million users. In the next few years, the online education market continues to grow rapidly.

Traditional E-learning is a simple modle of watching course video and testing. Users' learning evaluation depends on their own judgment and reflection, so it's hard to achieve the expected effect. At the same time, the learning path planning of the course is always same for students of different levels, so the efficency is not high.

The application of big data technology can enable students to have a personalized and diversified learning path. Using the big data on the online education platform, we can: 1) track the students' behavior files, record the students' mastery of knowledge points and the time spent on them in real time. According to these information, we can understand the students' learning situation more truly and provide personalized guidance; 2) assist teachers to optimize teaching methods, improve the course design and make more reasonable teaching Outline; 3) explore the learning law and predict the future development of students.
## Data of Online Education
### Classification of Data
According to the source, the data can be divided into user information, course information, exercise information, video information, forum information, user behavior information and knowledge map. User information refers to the user's personal information, including the user's basic information, learning course performance information and understanding of knowledge points, etc.; course information refers to the course content and organizational structure; exercise information refers to the exercise content and related exercise prompt information; video information includes video, audio and subtitle; forum information includes the organization structure and post content of the Forum; user behavior information refers to the behavior records of users browsing web pages and playing videos; knowledge map is a collection of knowledge points, drawn by teachers at the initial stage, and maintained and updated automatically and manually at the later stage.
### Characters of Data
The data of online education has the general 4V characteristics, including large volume, high- velocity, variable and veracity. However, the data in this field has some special features. 

Firstly, the data are closely linked. The data sources in online education system are different, but there are countless links between them. For example, each student has the data such as courses, forum comments, scores directly related to them, knowledge points combine the knowledge maps and exercise databases together. At the same time, each student is linked with each knowledge point. We can see that the data in online education field are closely related and complex.

Secondly, the data storage should be heterogeneous. The video data is unstructured, and the data of the users such as the courses, scores and learning record is structured. the structure of forums and courses is stored in tree mode, and the basic information of users is stored in simple two-dimensional table structured form. Therefore, the storage forms in online education system should be diverse, thus forming a heterogeneous database, which puts forward higher requirements for data management
## Workflow
## Database
I want to choose MySQL as my database. The main reasons are below
### Features of Data
The information we need to store is directly related to the behavior of the specific users. As a result, the information such as the courses, scores, watch records can be stored in a simple two-dimensional structured form and the structure of forums, courses and knowledge points can be stored in tree mode. Considering the features of our data, I think SQL database is well enough to meet our needs.
### Cost and Scalability
As for the specific database, I think MySQL is the best choice considering the cost and Scalability. MySQL is the most popular open source SQL database, which means low cost and excelent flexibility. Through the various plugins in the community we can build the database at low cost.
