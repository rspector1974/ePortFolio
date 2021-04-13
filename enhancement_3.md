**Enhancement Three: Databases**

The artifact I have included for the Database(s) portion of my ePortfolio comes from CS-340, Client Server development. I created this example in the Spring of 2021. This program is written in Python and uses Plotly Dash to facilitate the UX and allow for call backs in a web browser. The database used in this project is mongo DB a NoSQL database. The program uses the pymongo library to access and authenticate with the mongo database that holds records for an animal rescue organization based in Texas. The data from the database is loaded using a read method coded in a separate method file. Once the data is loaded it is displayed in a sortable data table along with a pie graph of different breeds and a geographical location of the animal displayed on a map.

I have included this artifact in my ePortfolio as it shows my understanding of database CRUD methods and my ability to program in Python. This example is also demonstrating using different libraries helping to facilitate a pleasant, efficient, and useful user experience. The web-based dynamic of the application also fits well with today&#39;s trends.

From a database perspective I am showing my ability to use advanced queries such as projections and wild card searches of the mongo database. This application allows the user to query the database based on specific record types to better help organize the requested output.

I am also showing how security can be built into a database and its access. In this case the user&#39;s credentials are hard coded into the software. In future modifications I would use the Cryptography Library available to Python to prompt, store and pass encrypted credentials into the pymongo database library.

I have enhanced and improved the original projects code to include a way to filter the data table based on search results. In the original program the data table was filtered by selecting a radio button. For example, selecting the &quot;Water Rescue&quot; button filtered out all animals that did not meet the criteria of a &quot;Water Rescue&quot; animal. In the enhanced version the user can select a &quot;search category&quot; and input a string that is wild card searched against that selected category. This allows the user to filter the data table results in a much more granular fashion and is a feature that is expected in today&#39;s database utilities.

The second enhancement I have included is that of a drop-down menu to choose what values the pie chart feature should graph on. For example, a user could see a pie chart on breed breakdown, name, animal type, or age depending on the drop-down selection. I have also included a way to hide the pie chart if graphical representation is not desired. Including these enhancements shows my ability to use several different Dash components including dcc.input,dcc.button,dcc.radio.items,datatable, and dcc.dropdown. Demonstrating that I can not only use Plotly, Python and Mongo, but also learn new features and integrations in a specific API, or library.

The course objectives that I defined in Module One for this enhancement have been met, I have also added additional enhancements. I have extended the code to allow a user to keyword search different BSON categories (Mongo Format). Additionally, I employed different types of menu displays, as well as actions to make the software more usable. I have stuck to my pseudocode and am very pleased with the outcome of the project.

I do not have any updates to my outcome-coverage plans that have not been identified in this narrative. To summarize, I have added additional menus and radio buttons to the code that were not strictly defined in my initial proposal. All of which helped to extend the user experience while showing my depth of knowledge in Python, mongo and Plotly Dash.

The process for this enhancement was straight forward. Studying the syntax changes between SQL and mongo did take some time. Learning the NoSql replacement for Like (something I have been using for years) was the game changer on this project. Also studying the Plotly functionality and how it connects with call backs was something I needed to brush up on to extend the functionality of my software. Just reciting the original code is not enough to truly enhance the project, understand how call backs work, how to reference multiple inputs and outputs, and how those effect the updating of the data base queries was required to produce the software to my initial outlined scope.

The biggest challenged I faced in this project was the differences in the Plotly, php and python libraries that had occurred between the versions used in the original class and the newest versions I used to create my development environment. For this project I used Jupyter for the IDE, and the newest version of that coupled with the PHP and Python library changes presented challenges at first. Some of the methods and functions taught in CS-340 had been since depreciated requiring more research and updated methods.

With a firm foundation in coding and database work, the understanding of certain concepts made this project straight forward. The syntax and testing, requiring a Python IDE , local mongo server, and the data was where the majority of the learning took place. Sometimes you do not know what you do not know until you get started. After completing this project, I am confident in my ability to setup a full stack programming environment and create software that is both easy to use, secure and efficient.
<br>
[Databases Enhancement Three Code](https://github.com/rspector1974/databases)
## ePortfolio Navigation
- [Home](index.md)
- [Enhancement One Software Design and Engineering Example](enhancement_1.md)
- [Enhancement Two Algorithms and Data Structures Example](enhancement_2.md)
- [Web Development Examples](web_dev.md)
- [Code Review](code_review.md)
