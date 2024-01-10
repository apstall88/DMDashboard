DM Dashboard Spec
REQUIRED INSTALLATION:
1.	VS Community
2.	Sql Sever Management Studio
3.	Sql Sever – dev edition
4.	GIT
5.	Node.js
6.	Postman

PROJECT INTENT
1.	Create an all in one web application for use by a dungeon master to use while playing a roleplaying game to roll on random tables before or during play to generate a variety of random content on the spot. Expand to service other tasks a DM may want during gameplay such as viewable monster stat blocks, digital dice rolling or XP calculation.
2.	Project should allow veteran developers to explore technologies they do not have experience with to round out skillset, the project should also provide opportunities for veteran developers to mentor new developers and for new developers to provide insights from their more recent education.
TECH TO EXPLORE
1.	Web App Development
2.	Node.js, react, etc
3.	API creation
4.	API use
5.	Web App Deployment and management of deployed system

TECH STACK
ASP.NET core API with React front end
Github repository for source control
Azure deployment
T-SQL database – local to start but longterm use of azure hosting

PROCEDURE GOALS
1.	Do things the right way 
a.	We are not on a deadline, we have the time to ensure our designs are strong and wont create issues in the future
b.	Ensure designs are generic and extensible
c.	Keep design patterns and SOLID in mind when designing class structures
d.	Break behaviors into interfaces whenever possible
2.	All work should be done in GIT branches and Code Reviewed via Pull Request prior to merge to main
3.	Keep communication open, ask for help quickly when you hit a road block. Not only do we not want to waste our time on something we are squeezing in during our free time, but creating an environment for mentoring each other is one of our primary goals and we cannot do that if we don’t know what we are getting hung up on.
4.	Create Tasks/projects via github (or another project board service)
a.	Tasks should be small but deliverable/complete
b.	Main must retain functionality at all times – if a goal would require multiple tasks to complete all must be completed on a sub-branch and tested before merging to main
c.	No plans to “refine” projects as that would be a large demand on our time. Adam will likely create most tasks but if there are features any member believes would be beneficial feel free to create tasks to be prioritized
5.	No expectation of work/productivity from any member – this is a voluntary project and there is no participation requirement – however – if you begin a task that is holding up other tasks another dev may take over work on it if you do not have time to complete it. 

MINIMUM VIABLE PRODUCT
A single table may be viewed, added to and rolled on.
IMMEDIATE GOALS
Add multiple table types to roll on
-	Landmarks
-	Weather
-	Encounters
-	Treasure/Loot
Add ability to bulk load tables from
-	CSV
-	Excel
-	PDF
-	Image?
FUTURE GOALS
User login/personal settings for tables
Roll Filtering
Personalized Sub-Tables (i.e. Encounter table for a specific campaign)
Roll20 api integration
Dndbeyond integration (no public API but possibly can get some data from them)
Dungen integration
API use to pull creature stat blocks from public databases
Add functionality to read stat block images or pdfs and generate buttons to roll abilities
Store Maps which can be associated with biomes and randomly generated along with an encounter to provide an instant, appropriate battle map

