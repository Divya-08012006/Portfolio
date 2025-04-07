<!DOCTYPE html>

<html>

<head>

    <title>Portfolio</title>

    <style>

        body {

            font-family: Monaco, monospace;

            margin: 0;

            padding: 0;

            background-color:  #333333;

        }



        header {

            background-color: #87CEEB;

            color: #fff;

            text-align: center;

            padding: 4rem 0;

            position: relative; /* Add this */

        }



        .header-content h1 {

            font-size: 2.5rem;

        }



        /* Add styles for the round profile picture */

        .profile-picture {

            width: 200px; /* Adjust the size as needed */

            height: 200px;

            border-radius: 75%; /* Create a circular shape */

            object-fit: cover; /* To ensure the image fills the circular area */

            position: absolute; /* Add this */

            top: 75px; /* Adjust top position as needed */

            left: 75px; /* Adjust left position as needed */

        }



        nav {

            background-color: #333;

            color: #fff;

            text-align: center;

        }



        nav ul {

            list-style-type: none;

            padding: 0;

        }



        nav ul li {

            display: inline;

            margin: 0 20px;

        }



        nav ul li a {

            text-decoration: none;

            color: #fff;

        }



        .section-content {

            background-color: #fff;

            padding: 2rem;

            margin: 1rem;

            border-radius: 20px;

            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);

            text-align: justify;

        }



        .download-button {

            background-color: #333;

            color: #fff;

            padding: 0.5rem 1rem;

            text-decoration: none;

            border-radius: 20px;

            display: inline-block;

            margin-top: 10px;

            align-self: center;

        }



        .download-button:hover {

            background-color: #555;

        }



        footer {

            text-align: center;

            padding: 1rem 0;

            background-color: #333;

            color: #fff;

        }



        ul {

            list-style-type: disc;

            padding-left: 20px;

        }

    </style>

</head>

<body>

    <header>

        <div class="header-content">

            <!-- Add your profile picture here -->

            <img src="divya.jpg" alt="Your Profile Picture" class="profile-picture">

            <h1>DIVYA R</h1>

            <p></p>

        </div>

    </header>



    <nav>

        <ul>

            <li><a href="#ABOUT">ABOUT</a></li>

            <li><a href="#EDUCATION">EDUCATION</a></li>

            <li><a href="#SKILLS">SKILLS</a></li>

            <li><a href="#CONTACT">CONTACT</a></li>

            <li><a href="#RESUME">RESUME</a></li>

           

        </ul>

    </nav>



    <section id="about">

        <div class="section-content">

            <h2>ABOUT ME</h2>

            <p>I'm a <b>web development</b> expert who is passionate about creating dynamic and user-friendly websites. 

                I'm driven by the desire to craft high-performance web applications that enhance user experience and provide

                 seamless digital solutions.</p>



        </div>

    </section>



    <section id="EDUCATION">

        <div class="section-content">

            <h2>EDUCATION</h2>

            <p>Currently Pursuing Bachelor of Computer Science in Bharathiyar University</p>

            

            

        </div>

    </section>



    <section id="SKILLS">

        <div class="section-content">

            <h2>SKILLS</h2>

            <ul>

                <li>Python</li>

                <li>C,C++,Java(Basics)</li>

                <li>DBMS</li>

		<li>Critical Thinking</li>

		<li>Desicion Making</li>

		<li>Management Skills</li>

		<li>Leadership</li>

            </ul>

        </div>

    </section>



    <section id="CONTACT">

        <div class="section-content">

            <h2>CONTACT</h2>

            <ul>

                <li>Phone:<a href="#Phone">9043725530 </a></li><br>

                <li>e-mail:<a href="#e-mail">divyardivya072@gmail.com</a></li><br>

                <li>Location :<a href="#Location">Tamil Nadu</a></li> <br>

                <!-- Add more Contact links here -->

            </ul>

        </div>

    </section>



    <section id="RESUME">

    

        <div class="section-content">

            <center>

            <h2>RESUME</h2>

            <a href="Divya.pdf" target="_blank" class="download-button">Download CV</a>

        </center>

        </div>

        

    </section>



    <footer>

        <p>&copy; 2025 Divya R</p>

    </footer>



    <script>

        // Smooth scrolling to section when clicking on navigation links

        document.querySelectorAll('a[href^="#"]').forEach(anchor => {

            anchor.addEventListener('click', function(e) {

                e.preventDefault();



                const targetId = this.getAttribute('href').substring(1);

                const targetElement = document.getElementById(targetId);



                if (targetElement) {

                    window.scrollTo({

                        top: targetElement.offsetTop,

                        behavior: 'smooth'

                    });

                }

            });

        });

    </script>

</body>

</html>
