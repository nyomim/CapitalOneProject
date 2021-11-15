# CapitalOneProject
To complete this challenge, build a web application that can do the following:  Let visitors search from a list of activities to do at different National Parks Visitors can click an activity and have the web app display all the National Parks tied to a specific activity After selecting a specific park, the app should pull up an informational page so the visitor can learn more about the park. Have a feature on the web app where visitors can:  Retrieve data from park web cams based on which National Park(s) the user selects. Specifically, this feature should be able to display the non-streaming images collected from park web cams so a visitor can view them with ease. REQUIRED: In your submission, you will need to link to a live deployed website (e.g., Heroku, Github pages, etc.) and a link to your repository with code.  Submissions will be graded on the following criteria: Meets Deliverables Code Quality &amp; Clarity Creativity / Aesthetics (think UI/UX)
<!doctype html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Capital One Project</title>
</head>
<style>
    body {
        font-family: 'Trebuchet MS', sans-serif;
    }
    .topnav input[type=text] {
        float: right;
        padding: 6px;
        margin-top: 8px;
        margin-right: 16px;
        border: none;
        font-size: 17px;
    }
    @media screen and (max-width: 600px) {
        .topnav a, .topnav input[type=text] {
            float: none;
            display: block;
            text-align: left;
            width: 100%;
            margin: 0;
            padding: 14px;
        }
        .topnav input[type=text] {
            border: 1px solid #ccc;  
        }
    }
    section,h1 {
        padding: 0 1em;
    }
    .grid{
        display: grid;
        grid-template-columns: repeat(3,290px);  /* 3 columns */
        grid-template-rows: repeat(3,270px); /* 3 rows  */
        grid-gap:50px 30px; /* 50 pixels of space added between rows and 30 pixels added between columns  */
    }
    .grid-item{
        border:thin gray solid;
        padding:10px;
    }
    img {
        width: 100%;
        height: 100%;
    }
</style>
<body style="background-color: #d3e1eb;">
    <div class="topnav">
        <input type="text" placeholder="Search..">
    </div>
    <h1><center>NATIONAL PARK ACTIVITIES</center></h1>
    <section>
        <div class="grid">
            <div class="grid-item"><img src="nationalParkOne.jpg" class="center"></div>
            <div class="grid-item"><img src="nationalParkTwo.jpg" class="center"></div>
            <div class="grid-item"><img src="nationalParkFive.jpg" class="center"></div>
            <div class="grid-item"><img src="nationalParkThree.jpg" class="center"></div>
            <div class="grid-item"><img src="nationalParkFour.jpg" class="center"></div>
            <div class="grid-item"><img src="nationalParkSix.jpg" class="center"></div>
        </div>
    </section>
    <script>
        file:///Users/nyomimunson/Desktop/web%20design/index.html&api_key=NJ5jaTpVlPWB1IHatI7cvja7RGj9HOpXHqg1xrjU
    </script>
</body>
</html>
