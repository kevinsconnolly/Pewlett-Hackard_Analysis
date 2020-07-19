# Pewlett-Hackard-Analysis

The large corporation, Pewlett-Hackard requisitioned us to find relevant information concerning the upcoming "gray wave" which represents an aging workforce and a potentially destructive retirement wave which could disrupt the firm's overall producivity, training/mentorship and overall profitability. For the following task, we built upon five excel files to build multiple tables to ultimately come to representative and accurate numbers to help present the numbers gap between what the firm needs to know in order to be prepared for the upcoming and inevitable "Gray Retirment Wave."
First requirement is to solve the amount of employees who are retiring and this amounts to 41,380 employees. 
Second requirement is the individuals available for mentorships and this amounts to 1,549 employees. 
The code below shows how we came to the number
Select_Count(emp_no) from deliverable _two

The deliverable one and deliverable two with the partition's in them middle helped to set up the data with the appropriate primary key which helped set the data on a unique key ie employee number and after used the establishment of certain columns to help create tables for the total 5 csv's. I ran into a number of issues which were not only frustrating but ultimately enlightening. Learning about the key and foreign keys really confused me in the beginning. Only going through the module and understanding how to pivot off of tables and columns ie retirement_info table, you write which column used for example emp_no, you write ti.emp_no. Going through these iterations through the challenege really helped me understand how SQL works and functions. I'm very happy to have learned with other class mates and struggled together.


After reviewing the data, it looks like the firm needs to implement two policies. Due to a large amount of retirees upcoming versus the new employess/mentorships open or incoming, Pewlett_Hackard will need to step up hiring and also include technology to help bridge the potential gap of not enough workers to cover for the previous generation ie retiree's leaving. The data should focus on skills in their information, which is lacking, to ensure we can detail the skills game and technology gap which ultimately will lead to performance expectations being met. For further information, I would recommend a slotting into which roles are inadequatley filled in order to ensure there isn't any missed opportunity to train the next generation. This could be solved by having a column with the role of the individual, count that total and compare versus and age group that is not retiring. This could visualize the wave and how to fill the gap in a potential brain drain and help avoid it.



First ERD is the ERD Map for keys. 
