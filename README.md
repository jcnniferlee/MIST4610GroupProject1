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
Our data model represents the structure and operations of a large music conglomerate that owns multiple record labels. The **RecordLabel** entity is the core of the database and stores information about the individual record labels such as their name, founding year, and CEO. This has a one-to-many relationship with Contract as record labels can have many contracts with different artists. **Contract** defines the agreement between an artist and their corresponding record labels, specifying things like record revenue share and type.

<p align="center"> ────୨ৎ────

The **Artist** entity contains information about the artists, such as their name, date of birth, and debut year. Artists can have many contracts, which is shown by the one-to-many relationship between the two. Artists also has a one-to-many relationship with awards as they can win multiple awards that help them gain more industry recognition. The **Awards** entity contains information about various rewards such as their name, category, and year. A one-to-many relationship also exists between Artists and the **Royalty** entity, which contains the royalty percentage share and amount. This is the percentage of revenue an artist earns from streaming, album sales, and concert performances. 

<p align="center"> ────୨ৎ────

Our model also features an **Album** entity, which includes the title, release date, and genre. This has a one-to-many relationship with Artist as well as artists can release multiple albums. The **Song** entity contains information about songs, including their title, genre, and label. This has a one-to-many relationship with the Album entity as albums can contain multiple songs. The Song entity also has a one-to-many relationship with the StreamingData entity and Collaborations entity. The **StreamingData** entity contains information such as the strem revenue and platform while the **Collaborations** entity contains information such as the Collab ID and role. Songs generate revenue through multiple different streaming platforms and a single song can be available on multiple streaming services. Collaborations also shares a one-to-many relationship with Artist as artists can have many different collaborations with various artists. 

<p align="center"> ────୨ৎ────

Beyond recorded music, artists also earn revenue from live performances. The **Concert** entity contains information about artist's concerts, such as the concert date and tour name. This has a one-to-many relationship with Artist as artists can hold multiple concerts. The Concert entity also holds one-to-many relationships with the Venue entity and Ticket entity. The **Venue** entity contains information such as the venue name and city while the **Ticket** entity contains information such as the seat number and ticket price. Each concert takes place at a venue and a venue can hold multiple concerts while concerts can only be held at one venue at a time. Since each concert generates revenue through ticket sales, the Ticket entity shows that a concert can sell multiple tickets while a ticket can only be assigned to one concert at a time. 

<p align="center"> ────୨ৎ────

Overall, our database supports managing multiple record labels and their artists, tracking music releases and streaming performance, recording artist collaborations and contract details, monitoring concert events and ticket sales, calculating royalty distributions and revenue sources, and recognizing artists' achievements through various awards. It provides a comprehensive view of artist careers, music performance, and revenue tracking ensuring that the record labels under the conglomerate are able to make data-driven decisions to maximize profitability and artist success. 





# Data Dictionary




# Queries





# Database Info



