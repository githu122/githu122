<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your HTML Title</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css"> <!-- Include Font Awesome for icons -->
    <style>
        body {
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: white ; 
            ;
            color: black ;
            flex-direction: column; /* Center content vertically */
            font-family: Arial, sans-serif; /* Change font family for the whole document */
        }

        .center-image {
            display: block;
            margin: 0 auto; /* Center the image horizontally */
            width: 150px;
            height: auto;
            border-radius: 50%;
            overflow: hidden;
        }

        .content {
            text-align: center; /* Center text horizontally */
            margin-top: 10px; /* Add space between image and content */
        }

        h1 {
            font-size: 25px; /* Set font size of heading */
            margin-bottom: 0px; /* Add space below heading */
            color:black; /* Change heading color */
            font-family: "Times New Roman", Times, serif; /* Change font family for heading */
        }

        p {
            font-size: 14px; /* Set font size of paragraph */
        }

        .button-container {
            display: flex;
            flex-direction: column; /* Stack buttons vertically */
            align-items: center; /* Center buttons horizontally */
        }

        .styled-button {
            width: 200px; /* Set width of buttons */
            height: 50px; /* Set height of buttons */
            padding: 10px;
            background-color: rgb(109, 233, 109)

            ; /* Change background color */
            border: none;
            border-radius: 5px;
            color: black;
            font-size: 16px;
            font-weight: bold; /* Make button text bold */
            cursor: pointer;
            outline: none;
            margin-bottom: 15px; /* Decrease space between buttons */
            transition: background-color 0.3s; /* Smooth transition for hover effect */
            box-sizing: border-box; /* Ensure padding and border are included in width and height */
            display: flex;
            align-items: center; /* Center icon and text vertically */
            justify-content: flex-start; /* Align text to the left */
            text-align: center; /* Center text horizontally */
        }

        .styled-button i {
            margin-right: 10px; /* Add space between icon and text */
            margin-left: 10px; /* Add space on the left side of the button */
            color: rgb(2, 2, 2); /* Change icon color */
        }

        .styled-button:hover {
            background-color: rgb(86, 224, 86) ; /* Change background color on hover */
        }

        /* Style anchor tags to remove underline */
        a {
            text-decoration: none;
            color: inherit; /* Inherit color from parent */
        }
    </style>
</head>
<body>
    <div class="background"></div>
    <img src="imag.png" alt="Your Image" class="center-image">
    
    <div class="content">
        <h1>FATIMA</h1>
        <p>  </p>
        <div class="buttons">
            <div class="button-container">
                <button class="styled-button"><i class="fas fa-file-alt"></i> <a href="https://www.example.com/resume">Resume</a></button>
                <button class="styled-button"><i class="fas fa-chart-bar"></i> <a href=" https://public.tableau.com/app/profile/fatima.aman/vizzes ">Tableau Portfolio</a></button>
                <button class="styled-button"><i class="fab fa-linkedin"></i> <a href="https://www.linkedin.com/in/fatima-amanullah-a3202329a/">LinkedIn</a></button>
                <button class="styled-button"><i class="fab fa-github"></i> <a href="https://github.com/">GitHub</a></button>
                <button class="styled-button"><i class="far fa-envelope"></i> <a href="mailto:fatimaanalysts@gmail.com">Email</a></button>
            </div>
        </div>
    </div>
</body>
</html>
