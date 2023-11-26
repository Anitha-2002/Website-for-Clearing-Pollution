# Website-for-Clearing-Pollution
<h3>Project Overview</h3>
              <p>
                The Clean India Initiative Web Application is a platform designed to empower users to report and 
                address dirty areas in their vicinity by connecting with the local municipal corporation. 
                The application encourages civic responsibility and contributes to the Swach Bharath Mission. </p>
                <p>
                  Here is a summary of the key features and functionalities:
                </p>
                <h3>Front-End Implementation:</h3>
                
                <h4>Initial Page (start.php):</h4>
                <p>
                Warm welcome and information about the Swach Bharath Mission.
              
                <h4>Navigation options:</h4> 
                <p>
                  Home, Contact, Login.
              </p>
              
                <h4>SignUp Page:</h4>
                <p>
                User registration with input for Email ID and password.
                Automatic generation of a unique username.
                Confirmation password for security.
                SignUp button to create an account.</p>
                <h4>Login Page:</h4>
                <p>
                Username and password entry for registered users.
                Option to recover password if forgotten.
                Error page for incorrect credentials.
              </p>
                <h4>Index Page (After Login):</h4>
                <p>
                Welcomes the user after successful login.
                Provides options for reporting a dirty area.
              </p>
                <h4>Upload Image Page:</h4>
                <p>
                Allows users to upload images of polluted areas.
                Requests location access for automatic geotagging.
              </p>
                <h4>Location Detection Popup:</h4>
                <p>
                Asks for permission to access location for geotagging.
                Automatically captures latitude and longitude coordinates.
              </p>
                <h4>Upload Page (upload.php):</h4>
                <p>
                Prompts users to choose an image file for upload.
                Displays a sample image upload process.
                Thanks the user for contributing to the initiative.
              </p>
                <h4>Contact Us Page:</h4>
                <p>
                Provides contact information for inquiries or feedback.
              </p>
              <h4>Back-End Implementation:</h4>
               
                <h4>Database:</h4>
                <p>
                MySQL relational database management system is used
              </p>
                <h4>Tables:</h4> 
                <p>
                  'users' for storing user details (Email, Username, Password) and 'upload' for storing uploaded 
                  images, latitude, longitude, and the associated username.
                </p>
                <h4>User Authentication:</h4>
                <p>
                Secure user authentication with generated unique usernames.
              </p>
                <h4>Geotagging:</h4>
                <p>
                Captures and stores latitude and longitude coordinates for each uploaded image.
              </p>
                <h4>Image Storage:</h4>
                <p>
                Creates an 'upload' folder to store user-uploaded images.
              </p>
                <h4>Location Mapping:</h4>
                <p>
                Utilizes coordinates to pinpoint the exact location on maps.
              </p>
                <h4>Tools and Technologies Used:</h4>
                <h4>Front-End Languages:</h4>
                <p>
                 HTML5, CSS3, JavaScript, jQuery
                </p>
                 <h4>Back-End Languages:</h4> 
                 <p>PHP, JavaScript</p>
                 <h4>Database:</h4> 
                 <p>MySQL</p>
                 <h4>Development Environment:</h4> 
                 <p>Visual Studio Code (VS Code), XAMPP</p>
              
                <p>
                The Clean India Initiative Web Application encourages users to actively participate in maintaining
                 cleanliness and hygiene in their surroundings. By seamlessly integrating user-friendly features
                  and backend functionalities, the application bridges the gap between citizens and municipal 
                  corporations, fostering a sense of responsibility towards a cleaner and healthier environment.
              </p>


