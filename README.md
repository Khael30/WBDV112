//CODESSSSSSS

//html noly
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration</title>
</head>
<body>
    <header>

        <nav>
            <div class="logo"><h1>Hello World</h1></div>
            <ul>
                <li>Home</li>
                <li>About Us</li>
                <li>Contact</li>
            </ul>
        </nav>
    </header>

    <div>
        <form action="Registraion.php" method="post">
            <h1>Register for Tutoring</h1>

            <label for="firstname"><b>First Name</b></label>
            <input type="text" name="firstname" required>

            <label for="lastname"><b>Last Name</b></label>
            <input type="text" name="lastname" required>

            <label for="username"><b>Username</b></label>
            <input type="text" name="username" required>

            <label for="password"><b>Password</b></label>
            <input type="password" name="password" required>

            <label for="email"><b>Email</b></label>
            <input type="email" name="email" required>

            <label for="phone"><b>Phone number:</b></label><br><br>
            <input type="tel" name="phone"required>

            <label for="subjects"><b>Preferred Subject: </b></label>
            <select name="subjects" required>
                <option value="" selected disabled>Select a Subject</option>
                <optgroup label="Programming Languages: ">
                    <option value="python">Python</option>
                    <option value="java">Java</option>
                    <option value="c++">C++</option>
                    <option value="javascript">JavaScript</option>
                    <option value="c#">C#</option>
                </optgroup>

                <optgroup label="Data Structures and Algorithms: ">
                    <option value="array">Arrays, Linked Lists</option>
                    <option value="stacks">Stacks, Queues</option>
                    <option value="tress">Trees, Graphs</option>
                    <option value="sorting">Sorting and Searching Algorithms</option>
                </optgroup>

                <optgroup label="Web Development: ">
                    <option value="frontend">Frontend Development (HTML, CSS, JavaScript)</option>
                    <option value="backend">Backend Development (Node.js, PHP, Ruby on Rails)</option>
                    <option value="frameworks">Web Frameworks (React, Angular, Vue.js)</option>
                    <option value="database">Database Integration (SQL, NoSQL)</option>
                </optgroup>
                
            </select>
            <label for="tutors"><b>Chosen Tutor:</b></label>
            <select name="tutors" required>
                <option value="" selected disabled>Select Tutor</option>
                <optgroup label="Available Teachers: ">
                    <option value="juan">Sir Juan dela Cruz</option>
                    <option value="maria">Ms. Maria Santos</option>
                    <option value="antonio">Sir Antonio Reyes</option>
                    <option value="carlos">Sir Carlos Fernandez</option>
                    <option value="liza">Ms. Liza Torres</option>
                </optgroup>

            </select>

            <input type="submit" name="submit" value="Register">
            
        </form>
    </div>
</body>
</html>
