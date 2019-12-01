# Big Data in Online Education  
## Introduction
Different parties need to use common rules to maintain the history of the blockchain. When parties are not in agreement, alternative chains may emerge and fork happens. [Forks](https://en.wikipedia.org/wiki/Fork_(blockchain)#Hard_fork) can be classified as accidental or intentional. Accidental fork happens when two or more miners find a block at nearly the same time. The fork is resolved when subsequent block(s) are added and one of the chains becomes longer than the alternative(s). Intentional forks that modify the rules of a blockchain can be classified as hardfork and softfork. Hardfork broadens the protocol and makes previously invalid events valid. Softfork tightens the protocol and makes previously valid transactions are invalid.
## Data of online education
### Classification of data
According to the source, the data can be divided into user information, course information, exercise information, video information, forum information, user behavior information and knowledge map. User information refers to the user's personal information, including the user's basic information, learning course performance information and understanding of knowledge points, etc.; course information refers to the course content and organizational structure; exercise information refers to the exercise content and related exercise prompt information; video information includes video, audio and subtitle; forum information includes the organization structure and post content of the Forum; user behavior information refers to the behavior records of users browsing web pages and playing videos; knowledge map is a collection of knowledge points, drawn by teachers at the initial stage, and maintained and updated automatically and manually at the later stage.
### Characters of the data
The data of online education has the general 4V characteristics, including large volume, high- velocity, variable and veracity. However, the data in this field has some special features. 

Firstly, the data are closely linked. The data sources in online education system are different, but there are countless links between them. For example, each student has the data such as courses, forum comments, scores directly related to them, knowledge points combine the knowledge maps and exercise databases together. At the same time, each student is linked with each knowledge point. We can see that the data in online education field are closely related and complex.

Secondly, the data storage should be heterogeneous. The video data is unstructured, and the data of the users such as the courses, scores and learning record is structured. the structure of forums and courses is stored in tree mode, and the basic information of users is stored in simple two-dimensional table structured form. Therefore, the storage forms in online education system should be diverse, thus forming a heterogeneous database, which puts forward higher requirements for data management
## Workflow
## Database
I want to choose MySQL as my database. The main reasons are below
### Features of the data
The data we need to store is directly related to the behavior of the users and the information such as the courses, scores, watch records and so on can be 
