# Team 4 MIST 4610 Group Project 1

# TEAM NAME
21482 Group 4 


# Team Members
- Jennifer Lee [@jcnniferlee](https://github.com/jcnniferlee/MIST4610GroupProject1.git)
- Connie Wang 
- Kevin Choi 
- Kayla Valentine
- Vivek Shah

# Scenario Description
The scenario at hand is to design and implement a relational database that enables a large music conglomerate to efficiently manage its multiple record labels. The primary entity in the system is the Record Label, as each label operates under the conglomerate by signing artists, managing music releases, overseeing concerts, and handling various revenue streams such as ticketing and royalties. Each record label functions as an independent entity within the conglomerate and these labels work hand in hand with streaming platforms, concert venues, and distribution networks to promote artsts and maximize revenue. By establishing a well structured database, the system allows stakeholders to track artist success, label performance, and financial efficiency in real-time. Our focus is to accurately represent these relationships within the database and populate the system with sample data, allowing us to perform functional queries that may provide us with valuable business insight about the conglomerate. 


# Data Model
![Database](Image.png)
Our data model represents the structure and operations of a large music conglomerate that owns multiple record labels. The RecordLabel entity is the core of the database and stores information about the individual record labels. This has a one-to-many relationship with Contract as record labels can have many contracts with different artists. Contracts stores information about the contract, such as the type and revenue share. 

The Artist entity contains information about the artists, such as their name, date of birth, and debut year. Artists can have many contracts, which is shown by the one-to-many relationship between the two. Artists also has a one-to-many relaionship with awards as they can win multiple awards. The Awards entity contains information about various rewards such as their name, category, and year. 





# Data Dictionary




# Queries





# Database Info



