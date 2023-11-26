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
                <h3>Initial Page (start.php):</h3>
                <p>
                Warm welcome and information about the Swach Bharath Mission.</p>
                <h3>Navigation options:</h3> 
                <p>Home, Contact, Login.</p>
                <h3>SignUp Page:</h3>
                <p>
                User registration with input for Email ID and password.
                Automatic generation of a unique username.
                Confirmation password for security.
                SignUp button to create an account.</p>
                <h3>Login Page:</h3>
                <p>
                Username and password entry for registered users.
                Option to recover password if forgotten.
                Error page for incorrect credentials.
              </p>
                <h3>Index Page (After Login):</h3>
                <p>
                Welcomes the user after successful login.
                Provides options for reporting a dirty area.
              </p>
                <h3>Upload Image Page:</h3>
                <p>
                Allows users to upload images of polluted areas.
                Requests location access for automatic geotagging.
              </p>
                <h3>Location Detection Popup:</h3>
                <p>
                Asks for permission to access location for geotagging.
                Automatically captures latitude and longitude coordinates.
              </p>
                <h3>Upload Page (upload.php):</h3>
                <p>
                Prompts users to choose an image file for upload.
                Displays a sample image upload process.
                Thanks the user for contributing to the initiative.
              </p>
                <h3>Contact Us Page:</h3>
                <p>
                Provides contact information for inquiries or feedback.
              </p>
              <h3>Back-End Implementation:</h3>
                <h3>Database:</h3>
                <p>
                MySQL relational database management system is used
              </p>
                <h3>Tables:</h3> 
                <p>
                  'users' for storing user details (Email, Username, Password) and 'upload' for storing uploaded 
                  images, latitude, longitude, and the associated username.
                </p>
                <h3>User Authentication:</h3>
                <p>
                Secure user authentication with generated unique usernames.
              </p>
                <h3>Geotagging:</h3>
                <p>
                Captures and stores latitude and longitude coordinates for each uploaded image.
              </p>
                <h3>Image Storage:</h3>
                <p>
                Creates an 'upload' folder to store user-uploaded images.
              </p>
                <h3>Location Mapping:</h3>
                <p>
                Utilizes coordinates to pinpoint the exact location on maps.
              </p>
                <h3>Tools and Technologies Used:</h3>
                <h3>Front-End Languages:</h3>
                <p>
                 HTML5, CSS3, JavaScript, jQuery
                </p>
                 <h3>Back-End Languages:</h3> 
                 <p>PHP, JavaScript</p>
                 <h3>Database:</h3> 
                 <p>MySQL</p>
                 <h3>Development Environment:</h3> 
                 <p>Visual Studio Code (VS Code), XAMPP</p>
                <p>
                The Clean India Initiative Web Application encourages users to actively participate in maintaining
                 cleanliness and hygiene in their surroundings. By seamlessly integrating user-friendly features
                  and backend functionalities, the application bridges the gap between citizens and municipal 
                  corporations, fostering a sense of responsibility towards a cleaner and healthier environment.
              </p>




