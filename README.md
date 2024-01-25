<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CollegePage</title>
    <link rel="stylesheet" href="register.html">

    <link rel="website icon" type=" icon" href="logo.jpg">
    <style>
        .headline marquee {
            font-size: 18px;
            position: relative;
            height: 5vh;
            width: 98%;
            left: 2%;
            color: gold;
            font-style: italic;
        }

        .headline:hover {
            font-size: 22px;
            background-color: black;
            color: white;
            font-weight: bold;
            font-style: italic;

        }

        * {
            margin: 0;
            padding: 0;
        }

        header {
            height: 6vh;
            display: flex;
            align-items: center;
            justify-content: center;
            background-color: red;



        }

        nav {
            display: flex;
            flex-wrap: wrap;
            flex-wrap: wrap;
            align-items: center;
            padding: 5%;
        }

        nav ul h4 {
            display: flex;
            flex-wrap: wrap;
            padding: 2px;

            height: 6vh;
            text-align: center;

            background-color: #D3EDD7;
        }

        nav ul a,
        .a {

            text-decoration: none;
            flex-wrap: wrap;

            border-left: 2px solid black;
        }

        .a {

            border-right: 2px solid black;
        }



        nav ul a li {
            display: flex;
            flex-wrap: wrap;

            list-style: none;
            color: black;
            padding: 20px;

        }

        img {


            position: relative;
            margin: 5%;
            height: 275px;
            width: 92%;


        }


        .container {
            font-family: Verdana, Arial;
            margin: 10px;
            position: absolute;
            display: grid;
            align-items: center;
            justify-content: center;

            left: 1%;

        }





        .nav {
            background-color: #034255;
            padding-top: 30px;
            height: fit-content;
            color: white;
            text-align: center;
        }

        .nav ul li {
            list-style: none;
            padding: 8px;

        }

        .fac {
            background-color: #032530;
            height: 40px;
            align-items: center;
            display: grid;
            position: relative;
            text-align: end;

        }

        .fac ul li {
            color: white;
            list-style: none;
            position: relative;
            right: 100px
        }

        .fac ul a li {
            text-decoration: none;
        }

        .detail {
            border: 2px solid black;
            padding-top: 1%;
            padding-left: 10%;
            padding-right: 10%;
            padding-bottom: 3%;

            position: relative;
            /* left: 10%; */
            display: inline-block;
            align-items: center;

        }

        a,
        .link {
            color: gold;
        }

        .college,
        .clg,
        .collegee {
            display: inline-block;

        }


        /* REGISTRATION */

        .container {
            position: relative;
            right: 200px;
        }

        label {
            display: block;
            margin-top: 10px;
            position: relative;
            right: 77px;
        }

        input[type="email"],
        input[type="password"],
        input[type="name"],
        input[type="text"],
        select {
            width: 100%;
            padding: 8px;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box;
            position: relative;
            right: 77px;
        }

        input[type="submit"],
        input[type="reset"] {
            width: 100%;
            position: relative;
            right: 77px;
            padding: 10px;
            background-color: #4CAF50;
            color: #fff;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }

        input[type="submit"],
        input[type="reset"]:hover {
            background-color: #45a049;
        }

        .f {
            position: relative;
            right: 77px;

        }

        @media only screen and (max-width: 768px) {
            nav ul {
                display: none;
                flex-direction: column;
                background-color: #D3EDD7;
                position: absolute;
                top: 50px;
                left: 0;
                width: 100%;
            }

            nav ul a {
                border-left: none;
                border-right: none;
            }

            nav ul.show {
                display: flex;
            }
        }

        .menu-icon {
            display: none;
            cursor: pointer;
            font-size: 24px;
            color: #333;
        }

        header {
            position: relative;
        }

        /* Your existing styles... */

        footer {
            background-color: #034255;
            padding-top: 4%;
            height: fit-content;
        }

        main {
            display: flex;
            padding: 2%;
            justify-content: space-around;
            flex-wrap: wrap;
            color: white;
        }

        .main-container {
            width: 100%;
        }

        .b {
            color: #FFF603;
            font-weight: bold;


        }

        .l,
        .k,
        .g,
        .h {
            width: 100%;

            border-right: 2px dashed white;
            text-align: center;
            margin-bottom: 20px;
        }

        .l ul,
        .k ul,
        .g ul,
        .h ul {
            padding: 0;
        }

        .l a,
        .k a,
        .g a,
        .h a {
            color: white;
            text-decoration: none;
        }

        .l a:hover,
        .k a:hover,
        .g a:hover,
        .h a:hover {
            color: #FFF603;
        }

        .dis {
            padding: 8px;
            line-height: 18px;
            font-family: Arial, Helvetica, sans-serif;
            color: #BFC8CB;
            font-size: 15px;
            text-align: center;
            background-color: #032530;
            width: 100%;
            border-radius: 20px;
            margin-top: 20px;
        }

        /* Responsive adjustments */
        @media only screen and (min-width: 768px) {
            main {
                justify-content: space-between;
            }

            .l,
            .k,
            .g,
            .h {

                border-bottom: 2px dashed white;
                width: 22%;
                text-align: left;
            }
        }

        @media only screen and (max-width: 767px) {
            .main-container {
                width: 90%;
                margin: 0 auto;
            }

            .l,
            .k,
            .g,
            .h {
                border-bottom: 2px dashed white;
                width: 100%;
            }
        }
    </style>
</head>

<body>
    <div class="fac">
        <ul>
            <a href="register.html">
                <li><b>Faculty Registration </b></li>
            </a>
        </ul>
    </div>
    <div class="nav">
        <div class="c">
            <ul>
                <li>
                    <h1><b>Govt. Ploytechnic College, Satna</b></h1>
                </li>
                <li>
                    Phone : ,9424654948,0767229344 Email : prinpoly.stn@mp.gov.in
                </li>
                <li>
                    <a href="register.html" class="link">https://www.polysatna.org</a>
                </li>
            </ul>
        </div>
    </div>
    <header>
        <nav>
            <ul>
                <h4>

                    <a title="Menu" href="#" class="menu-icon" onclick="toggleMenu()">☰</a>

                    <a title="Home" href="#">
                        <li>Home</li>
                    </a>

                    <a title="About Us"
                        href="https://mis.mptechedu.org/(S(dzp0wtyipmuszevwidcfhvew))/CollegePage/Frm_ContactUs.aspx">
                        <li>About Us</li>

                        <a title="Department & Cources"
                            href="https://mis.mptechedu.org/(S(dzp0wtyipmuszevwidcfhvew))/CollegePage/Frm_CourceDtls.aspx">
                            <li>Department & Cources</li>

                        </a><a title="Campus"
                            href="https://mis.mptechedu.org/(S(dzp0wtyipmuszevwidcfhvew))/CollegePage/Frm_HostelDtls.aspx">
                            <li>Campus</li>

                        </a><a title="Students"
                            href="https://mis.mptechedu.org/(S(0vgp3jpj4ntyiaxlqgudbvwz))/CollegePage/Frm_PlacementDtls.aspx">
                            <li>Students</li>
                        </a>

                        <a title="Facilities"
                            href="https://mis.mptechedu.org/(S(0vgp3jpj4ntyiaxlqgudbvwz))/CollegePage/Frm_FacultyDtls.aspx">
                            <li>Faculty</li>
                        </a>


                        <a title="New & Events"
                            href="https://mis.mptechedu.org/(S(0vgp3jpj4ntyiaxlqgudbvwz))/CollegePage/Frm_CollegeNews.aspx?Adv_Cat_Id=5">
                            <li>New & Events</li>
                        </a>


                        <a title="Other Activities" class="a"
                            href="https://mis.mptechedu.org/(S(0vgp3jpj4ntyiaxlqgudbvwz))/CollegePage/Frm_GovtProjectDtls.aspx">
                            <li>Other Activities</li>
                        </a>

                </h4>
            </ul>

        </nav>
    </header>

    <div class="detail">
        <section class="img">

            <img src="https://mis.mptechedu.org/(S(35j2atlqs550s0p0ykmcphro))/CollegePhoto/b1191010021335.jpg"
                alt="college image"></a>



        </section>

        <div class="headline">
            <marquee behavior="left" direction="right">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Fuga
                voluptas aut itaque est pariatur expedita, odio quae quas qui accusantium quibusdam iure suscipit
                doloremque optio doloribus voluptatibus accusamus harum vel!</marquee>
        </div>
        <div class="container">
            <h4 class="h4" style="background-color: #EEEEEE; color: #C6070F; border-bottom: 2px solid #032530
            ;"><b>About College
                </b></h4>
            <p class="p">Satna a district head quarter of Rewa commissionary in Vindhya Region is north east part of
                Madhya
                Pradesh,
                is located on the National highway no 7. It is 70 KM from Chitrakot. It is also well connected by train
                and
                is located on MumbaiKolkota via Jabalpur-Allahabad train route. Satna has its own importance on the map
                of
                Madhya Pradesh in historical, political and economical platform.Govt Polytechnic college, Satna was
                established in 1989 and affiliated to R.G.P.V. Bhopal. We are running four Diploma courses namely
                Diploma in
                Electrical Engg. Mechanical Engg., Computer Science & Engg. and Cement Technology with intake capacity
                of 60
                in each discipline. This institute is treated as pioneer institute in Technical Education in Vindhya
                region
                because this is the only Govt. institute in whole of Madhya Pradesh in which the three year Diploma
                course
                in Cement Technology is running.
            </p>
            <br>
            <h2 style="border-bottom: 2px solid #032530;">
                Last Three Year Innovation Details
            </h2>
            <div class="p2">Institution establish a Smart Class for improving the learning capacity of students.
                Institute
                now have uninterrupted internet facility through Leased line Radio System
            </div>
        </div>
    </div>
    <br>
    <footer>
        <main>
            <div class="l">
                <ul>
                    <li><a href="#"><b class="b">HOME:</b></a></li>
                    <li><a href="#">Department & Cources</a></li>
                    <li><a href="#">Faculty</a></li>
                    <li><a href="#">News & Event</a></li>
                    <li><a href="#">Photo Gallery</a></li>
                </ul>
            </div>
            <div class="k">
                <ul>
                    <li><a href="#"><b class="b">ABOUT US:</b></a></li>
                    <li><a href="#">Principle Desk</a></li>
                    <li><a href="#">Contact Us</a></li>
                    <li><a href="#">Department Directory</a></li>
                </ul>
            </div>

            <div class="g">
                <ul>
                    <li><a href="#"><b class="b">STUDENTS:</b></a></li>
                    <li><a href="#">Placement</a></li>
                    <li><a href="#">Result</a></li>
                </ul>
            </div>
            <div class="h">
                <ul>
                    <li><a href="#"><b class="b">CAMPUS:</b></a></li>
                    <li><a href="#">Hostel</a></li>
                    <li><a href="#">Games & Sports</a></li>
                    <li><a href="#">Library</a></li>
                    <li><a href="#">Infrastructure</a></li>
                    <li><a href="#">Laborarty & Workshop</a></li>
                </ul>
            </div>
            <div class="dis">
                <p class="p3">Disclaimer: This site is designed & developed by Prince Soni, Satna (MP). <br>
                    Best viewed in IE 6.0 and above with monitor resolution 1024x768
                </p>
            </div>

        </main>





    </footer>

    <script>
        function toggleMenu() {
            var navList = document.querySelector('nav ul');
            navList.classList.toggle('show');
        }
    </script>





</body>

</html>
