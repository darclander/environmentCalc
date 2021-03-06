# DAT257/DIT257- Agile software project management - Team Phish
UN sustainability project for course in agile management.
The goal selected was [Goal 13](https://www.un.org/sustainabledevelopment/sustainable-development-goals/) Climate Action

# Team members
**Usernames  - Real name**\
[Pontare25](https://github.com/Pontare25)  
[Darclander](https://github.com/darclander)  
[adrianhak](https://github.com/adrianhak)  
[Cladnic](https://github.com/Cladnic)  
[munchgar](https://github.com/munchgar)  
[HersiZa](https://github.com/HersiZa)  

[Contributions / Member](https://github.com/munchgar/dat257phish/pulse)


# Scrum board
For [SCRUMBOARD](https://github.com/munchgar/dat257phish/projects/1) see Projects tab 

# Motivation
This project was created as part of a course (DAT257/DIT257- Agile software project management) taught at Chalmers University in collaboration with the University of Gothenburg. The primary motivateion behind the project was to learn to use Agile (and SCRUM) as a developer framework. 

# Installation
To run the application we recommend using IntelliJ. 
1. Clone the repository
2. Run the application using the Maven tab, scroll down to JavaFX and use the javaFX:run option (In IntelliJ the Maven tab is located at the top right). 

![Alt text](Documents/screenshots/mavenRun.png?raw=true "Maven run")

OBS! This is a Maven project using dependencies from JavaFX. Large portions of the program will run using the regular run button, but some dependencies require the maven support. 

# How to use
First follow the steps in Installation. Once you have run the application using the Maven tab the application will urge you to either sign in or register. 
- Register: Register by entering the prompts.
- Log in: Either log in using the credentials you entered in the register section or use the Demo credentials. Username: Demo, Password: pass. 
![Alt text](Documents/screenshots/login.png?raw=true "login")
- Once logged in you are greted with a homescreen with some information about the application and the UN goal 13
![Alt text](Documents/screenshots/Homescreen.png?raw=true "Homescreen")
- At the top you will find the global navigator where the main sectins are: Home, Calculator, Statistics, Vehicles, and All Emissions.
- In the Calculator section you will be able to log all the relevant activity data for your personal emissions, for example, food and personal transport
![Alt text](Documents/screenshots/food.png?raw=true "food calculator")
![Alt text](Documents/screenshots/PersonalTransport.png?raw=true "Personal Transport")
- From which you can add both vehicles and activities. You need to have registered a vehicle to add a transport activity. 
- At the bottom you will find the Results section which summarises the different emission activities and allows for filteering of categories and dates. 
![Alt text](Documents/screenshots/Results.png?raw=true "Results")
- For more in depth knowledge of the emissions we turn to the global navigator Statistics section
![Alt text](Documents/screenshots/statisticsTotal.png?raw=true "Statistics")
- Here we can more graphically break down exactly which activities are most responsible for the emissions.
![Alt text](Documents/screenshots/statisticsFood.png?raw=true "Food statistics")

# Documents contains our weekly reflections, both the individual and group reflections.
The individual reflections for week X can be located at **Documents\Individual reflections\weekX\***
The group documentation can be found directly in **Documents\** and is one text file, divided by headers. 

# API Reference
- This project was developed using java version 14.01. There have been some issues with using older versions so if there are issues with running we recommend using this version or later. These are set in the pom.xml file and the .iml file.
- Maven [4.0.0](http://maven.apache.org/maven-v4_0_0.xsd)
- [DateAxis](https://bitbucket.org/sco0ter/extfx/src/master/src/main/java/extfx/scene/chart/DateAxis.java)
## Below are a list of the external dependencies handled by Maven (see pom.xml file)
- Maven compiler version 3.8.0
- javafx-maven-plugin version 0.0.4
- For JavaFX we use org.openjfx version 14
- For SQLite Database we use version 3.32.3

# Frameworks used
- GUI: [JavaFX](https://openjfx.io/) (openjfx) 14
- Database: [SQLite](https://www.sqlite.org/index.html), SQLite dependency for [Maven](https://mvnrepository.com/artifact/org.xerial/sqlite-jdbc) 
- For managing dependencies [Maven](https://maven.apache.org/) has been used.

# Credits
- [DateAxis](https://bitbucket.org/sco0ter/extfx/src/master/src/main/java/extfx/scene/chart/DateAxis.java) for charts: Christian Schudt and Diego Cirujano
- Setting up JavaFX and Maven: ByteSmyth [Easiest JavaFX Setup, IntelliJ + Maven with Debugger (2020)](https://www.youtube.com/watch?v=4vd-RE0X5Lg&t=535s&ab_channel=ByteSmyth)
- Organising JavaFX windows: Software Development Tutorials [GUI Application Development using JavaFX with Scene Builder](https://www.youtube.com/watch?v=cfGTJVVcWvE&list=PLpFneQZCNR2ktqseX11XRBc5Kyzdg2fbo&ab_channel=SoftwareDevelopmentTutorials)
- UN Sustainability goal 13 [graphics](https://www.un.org/sustainabledevelopment/climate-change) 
