# Website-for-Clearing-Pollution
IMPLEMENTATION:
• Project Front-End Langauges: HTML5, CSS3, JS, JQUERY
Project Back-End Languages: PHP, Javascript, MYSQL
• Platform Used : Visual Studio Code(VS Code), xampp
The website contains:
▪ An initial page (start.php) which appears to the user before SignUp/Login,
▪ a SignUp page, 
▪ a Login page, 
▪ an index page which appears after user logs into the website, 
▪ a page where user can upload the image of a dirty area to get it cleaned up by a local 
municipal corporation
i) This is the initial page of the website named start.php starting with a formal greet to the users and some gathered 
information about Swach Bharath Mission with options like Home, Contact, Login. 
ii) This is the login page designed :
iii) This is the SignUp page asking for the user input for Email ID , a password and another field for Confirm Password
and a SignUp Button:
iv) On clicking the SignUp Option automatically a unique Username is generated and now the user can login using 
this username and the password set:
The Error Page when user inputs wrong username or password:
v) After the user logged in, a page opens asking for the user to Upload the image of a polluted/dirty place to be 
cleaned by the Municipal Corporation:
vi) On clicking the upload button, a pop-up window opens asking for location access to find out the location (i.e., 
latitude and longitude co-ordinate values) automatically when user uploads the image .
vii) After that the uploading page(upload.php) opens asking the user to choose the file to upload
viii) Here a sample image is being uploaded:
ix) Then, a Thank you message is displayed to the user for uploading the image
x) The following is the contact Us page:
xi) Coming to the Backend, a database named ‘cleanIndia’ is created with two table ‘users’ for storing the user 
details like Email, Username generated, Password, and another table named ‘upload’ to store the pictures uploaded 
by the users along with the Latitude and Longitude Values to find out the location of the dirty area and the 
Username generated.
xii) Here, the Latitude and Longitude Co-ordinated are detected and stored:
xiii) The Uploaded images can be found in the upload folder created to store the images:
The exact location can be found using the co-ordinates with the help of maps
