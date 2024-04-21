<!DOCTYPE html>
<html>

<head>
    <title>Crumbs & Co. | Order Now</title>
    <style>
        a {
            text-decoration: none;
        }

        body {
            margin: 0; /* Remove default body margin */
            padding: 0; /* Remove default body padding */
            font-family: fantasy, serif; /* Apply font-family */
            /* Remove font color */
        }

        .container {
            position: absolute; /* Position container */
            top: 0; /* Align container to top */
            left: 0; /* Align container to left */
            width: 100%; /* Set container width to full viewport width */
            text-align: center; /* Center-align content within container */
            padding: 20px; /* Add padding to container */
        }

        .next {
            font-size: 35px;
            margin-top: 10px; /* Increased top margin to raise the text */
            color: #F9DACC; /* Set text color to #F9DACC */
        }

        .images-container {
            position: absolute; /* Position images container */
            top: 1px; /* Align images container 10px from the top */
            left: 0; /* Align images container to left */
            padding: 20px; /* Add padding to images container */
            display: flex; /* Use flexbox for alignment */
            justify-content: center; /* Center content horizontally */
            align-items: center; /* Center content vertically */
        }

        .image {
            display: inline-block; /* Display images in a line */
            margin-right: 10px; /* Add right margin between images */
            vertical-align: top; /* Align images to the top */
            width: 54px; /* Set image width */
            height: auto; /* Maintain aspect ratio */
        }

        .company-name {
            position: absolute; /* Position company name */
            top: calc(15% - 50px); /* Position higher */
            left: 50%; /* Center company name horizontally */
            transform: translateX(-50%); /* Center company name horizontally */
            font-size: 100px; /* Increase font size */
            color: #9F332E; /* Set text color to #9F332E */
            text-shadow: 0 0 30px white; /* Set whiter shadow effect */
            opacity: 0; /* Initial opacity set to 0 */
            transition: opacity 1s ease-in-out; /* Add transition effect */
        }

        .company-name.visible {
            opacity: 1; /* Set opacity to 1 when visible class is added */
        }

        /* First section styles */
        .first-section {
            height: 100vh; /* Set height to full viewport height */
            background-image: url("webpage.png"); /* Set background image */
            background-size: cover; /* Ensure entire image covers the viewport */
            background-repeat: no-repeat; /* Disable background image repetition */
            background-position: center; /* Center the background image */
            display: flex; /* Use flexbox for alignment */
            justify-content: center; /* Center content horizontally */
            align-items: center; /* Center content vertically */
            color: white; /* Set text color to white */
            font-size: 30px; /* Set font size */
            text-align: center; /* Center-align text */
        }

        /* Second section styles */
        .second-section {
            height: 100vh; /* Set height to full viewport height */
            background-image: url("webpage.png"); /* Set background image */
            background-size: cover; /* Ensure entire image covers the viewport */
            background-repeat: no-repeat; /* Disable background image repetition */
            background-position: center; /* Center the background image */
            display: flex; /* Use flexbox for alignment */
            justify-content: center; /* Center content horizontally */
            align-items: center; /* Center content vertically */
            color: white; /* Set text color to white */
            font-size: 30px; /* Set font size */
            text-align: center; /* Center-align text */
        }
    </style>
</head>

<body>

    <div class="container">
        <a href="https://www.youtube.com/watch?v=hJxaVD6eAtc">
            <p class="next">HOME</p>
        </a>
    </div>

    <div class="images-container">
        <a href="https://www.facebook.com/profile.php?id=61558762826024">
            <img class="image" src="fb.png" alt="Facebook">
        </a>
        <a href="https://youtube.com/@CRUMBS.CO6?si=jkqFF_qKR7osuL9V">
            <img class="image" src="yt.png" alt="YouTube">
        </a>
        <a href="https://www.instagram.com/crumbsandco_buynow?utm_source=ig_web_button_share_sheet&igsh=ZDNlZDc0MzIxNw==">
            <img class="image" src="insta.png" alt="Instagram">
        </a>
        
    </div>
    <div class="content">
        <div>
         <center><button class="cn"><a href="#">SHOP NOW</a></button></center>
        </div>


    <script>
        // Add visible class to the company-name element after a delay
        setTimeout(function () {
            document.querySelector('.company-name').classList.add('visible');
        }, 1000); // 500 milliseconds delay
    </script>

    <!-- First section -->
    <section class="first-section">
  
    </section>

    <!-- Second section -->
    <section class="second-section">
        
    </section>

</body>

</html>
