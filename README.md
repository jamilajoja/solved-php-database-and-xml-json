Download Link: https://assignmentchef.com/product/solved-php-database-and-xml-json
<br>
<h3>Introduction</h3>

<strong>You are required to develop a web application to process XML and JSON data. The application will use PHP, Database, XML, and JSON.</strong>

<h3>Preparation</h3>

<ol>

 <li>Create a XML file which contains data of students (say, students.xml). The elements should be:

  <ul>

   <li>student_id; attribute email</li>

   <li>lastname</li>

   <li>firstname</li>

   <li>address</li>

  </ul></li>

 <li>You will need a database table which contains data used to validate users before they are able to log into the website. Create a <em>login</em>table in Oracle (student)database with the appropriate fields. Once a user is logged in, they should have different views depending on their privilege. A “normal” user may only lookup data in <em>xml</em>; an “administrator” should be able to insert student data into <em>students.xml</em>.</li>

 <li>Populate <em>xml</em>and the <em>login</em> table with some data.</li>

 <li>Download the JSON file called <em>json</em>from: university link(I have downloaded it, details are following) This file contains environmental data captured from environmental sensors. Users will be able to lookup data in <em>sensor.json</em>.</li>

</ol>

{“sensorreadinglist”:[

{

“xbeeid”:”B3D982A49F”,

“moteid”:”crest001″,

“motelocation”:”Canteen, ground floor”,

“hubname”:”hubone”,

“temperature”:”33.66″,

“airpressure”:”1011.40″,

“humidity”:”55.23″,

“light”:”180.50″,

“altitude”:”28493.84″,

“mic”:”392.38″,

“gas”:”0135.32″

},

{

“xbeeid”:”B3D982358A”,

“moteid”:”crest002″,

“motelocation”:”Classroom Hallway, second floor”,

“hubname”:”hubone”,

“temperature”:”32.34″,

“airpressure”:”1010.30″,

“humidity”:”56.98″,

“light”:”240.50″,

“altitude”:”28503.84″,

“mic”:”292.38″,

“gas”:”0085.32″

},

{

“xbeeid”:”B3D989A2DD9″,

“moteid”:”crest003″,

“motelocation”:”Football Field, ground floor”,

“hubname”:”hubone”,

“temperature”:”34.09″,

“airpressure”:”1011.22″,

“humidity”:”58.30″,

“light”:”280.30″,

“altitude”:”28504.33″,

“mic”:”085.38″,

“gas”:”0038.93″

}

]}







<h3>Requirements</h3>

<ol>

 <li><strong>Login page </strong><strong>(3 marks)</strong>Create a Login page which accepts a username and password. Create two username/password for testing :

  <ul>

   <li>admin/SIT780 (grant the user <em>administrator</em>privilege)</li>

   <li>guest/SIT780 (grant the user <em>normal</em>privilege)</li>

  </ul></li>

</ol>

Prepared statements reduce the risk of SQL injection. Hence, prepared statements need to be used to implement the login functionality.Captcha needs to be used in the login page to ensure that a human-being is attempting to login.

<ol start="2">

 <li><strong>Welcome page </strong><strong>(1 mark)</strong>After successful validation, a welcome page should be displayed. The welcome page should display a welcome message and also clearly state the privilege assigned to the user (<em>normal</em> or <em>administrator</em>). Create a menu to navigate to the options in #3, #4, #5 and #6 below.</li>

 <li><strong>Display data from sensor.json </strong><strong>(3 marks)</strong><em>json</em> contains environmental data captured from sensors placed around a school. Parse <em>sensor.json</em> and display data in a HTML table. Assign background color to HTML table data to highlight high/low values of temperature and humidity.</li>

 <li><strong>Display student data </strong><strong>(3 marks)</strong>Parse<em>xml</em> and display data in a HTML table.</li>

 <li><strong>Search student data </strong><strong>(4 marks)</strong>Provide an interface to search <em>xml</em> by <em>firstname</em> or <em>lastname</em>. Appropriate results should be displayed.</li>

 <li><strong>Insert student data </strong><strong>(3 marks)</strong>Only an <em>administrator</em> should have access to this option. Provide an interface to accept values for student_id, email, lastname, firstname and address. The data should be appended to <em>xml</em></li>

 <li><strong>Visualisation of address information in Google earth </strong><strong>(3 marks)</strong>Enhance the requirement #4 and #5 so that each student record has a hyperlink to visualize the location information in Google Maps. Refer to the example:</li>

</ol>

which is a modification of sample code from <a href="https://developers.google.com/maps/">Google Maps</a>.

<h3>Submission</h3>

You need to submit:

<ol>

 <li>The <em>URL </em>of the ‘home page’ of your system on university server; for example, if your username is Bhagya and you have put your assignment in the folder /public_html/, you would submit something like this: http://www.university.edu.au/~bhagya/index.html</li>

 <li>An assignment cover sheet. It can be submitted as an attachment or as a page on your website.</li>

 <li>Submit all your source files as a zipped (.zip or .rar) file.</li>

</ol>




<strong> </strong>

<strong> </strong>