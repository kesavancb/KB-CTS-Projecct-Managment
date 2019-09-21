# KB-CTS-Projecct-Managment
<h2>Associate Name: Kesavan Baskaran Cognizant ID:186301</h2>
<h2>Please refer to the "documents" folder which contain the following sub-folders</h2>
<ol>
	<li>MySQL Script : This contains table design and the DDL commands </li>
	<li>Load_Testing_Reports : This contains the screenshots of the jmeter execution on the rest end-point designed</li>
	<li>Jenkins : This contains the screenshots of the jenkins pipeline creation,execution and the build report</li>
</ol>
<h3>Following are the projects which comprise of the full-stack project:Project Manager</h3>
<ol>
   <li><h4>"projectmanager-server" - The spring boot project using Rest API,hibernate etc running in the back-end </h4></li>
   <li><h4>"projectmanager-web" - The angular project using HTML5,CS3,Bootstrap4 running in the front end</h4></li>
</ol>



<h3>Local Deployment Commands:</h3>
<ul>
<li>Spring boot in projectmanager-server folder: spring-boot:run</li>
<li>Angular ui in web folder of projectmanager-web: npm install -> npm start</li>
</ul>



<h3>Notes: </h3>
<ol>
<li>The free hosting public MySQL database jdbc:mysql://sql12.freemysqlhosting.net:3306/dbname is usedto access database layer when deployed in docker (instead of setting mysql in docker).</li>
<li>Please refer to the dockerfile, application screenshot document in the repo folder.</li>
<li>Please refer to the mysql script for the database DDL</li>
<li>Before the maven build, please change the port number in envioronment.prod.ts to change the port number in which the jar is gonna get deployed.</li>
</ol>
