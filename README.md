# passionfruit.github.com
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="../css/style.css">
    <title>Home Page</title>

    <style>


 
 #upcoming-events {
    margin: 20px;
    background-color: lightcyan;
    text-align: center; /* Center the content */
    margin-bottom: 20px;
    margin-top: 20px;
}

.event-container {
    display: flex;
    justify-content: center;
}

.event-card {
    background-color: white;
    border: 1px solid #ddd;
    border-radius: 5px;
    margin: 10px;
    padding: 15px;
    display: inline-block;
    width: 300px;
    text-align: center;
    margin: 0 auto; /* Center the event cards */
    margin-bottom: 20px;
}

.event-date 
{
    font-weight: bold;
    color: #0073e6;
}

.event-description {
    margin-top: 10px;
}

#announcements 
{
            background-color: darkorange;
            padding: 20px;
            margin: 20px;
}

#live-scores {
            background-color: #f5f5f5;
            padding: 20px;
            margin: 20px;
            border-radius: 10px;
        }

        #live-scores h2 {
            color: #0073e6;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }

        th, td {
            border: 1px solid #ddd;
            padding: 15px;
            text-align: center;
        }

        th {
            background-color: #0073e6;
            color: white;
        }

        #result-details {
            font-size: 16px;
            color: #555;
            margin-top: 10px;
        }

        .quote
        {
            background-color: rgb(110, 110, 255);
            font-family: Brush Script MT, Brush Script Std, cursive;
            padding-top: 10px;
            padding-bottom: 10px;
            text-align: center;
            margin: 20px;
            font-size: large;
            letter-spacing: 2px;
        }
        .footer
        {
            background: linear-gradient(to right, #3498db, #2c3e50);
            padding-top: 20px;
            padding-bottom: 35px;
            text-align: center;
            font-weight: bold;
            color: white;
            font-size: larger;
        }
    </style>
</head>

<body>
    <div id="navheader"></div>
    <script async src="../JS/nav.js"></script>

    <section class="content">

        <div style="color: white; background-color:rgb(115, 141, 246); text-align:center; padding-top:10px; padding-bottom:10px; margin:20px;">
          <h3> <marquee direction="right">  Your Hub for School Events and More! </marquee> </h3>
        </div>

        <div id="live-scores">
            <h2 style="text-align:center; font-family: Georgia, 'Times New Roman', Times, serif; color:black; font-weight: bold;">Live Scores</h2>
            <h2 style="text-align: center; background-color: #555; padding-top: 10px; padding-bottom: 10px; color:white;"> Pioneers VS Challengers Inter-House Seniors Football Finals </h2>
            <table>
                <thead>
                    <tr>
                        <th>Teams</th>
                        <th>Score</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td style="color: orange; font-weight: bold;">Pioneers</td>
                        <td style="color: green;">3</td>
                    </tr>
                    <tr>
                        <td style="color: maroon; font-weight: bold;">Challengers</td>
                        <td style="color: green;">2</td>
                    </tr>
                </tbody>
            </table>
            <div id="result-details">
                <h3 style="color:orange; text-align: center;">Pioneers win by 1 goal!</h3>
            </div>
        </div>
    

<div id="upcoming-events" style="padding-top:10px;">
    <h2>Upcoming Events</h2>

    <div class="event-container">

<div class="event-card" style="align:center;">
    <div class="event-date">Jan 5, 2024</div>
    <div class="event-description">Pioneers Football Selections</div>
</div>
<div class="event-card" style="align:center;">
    <div class="event-date">Jan 15, 2024</div>
    <div class="event-description">Interhouse Basketball Finals (Challengers vs Voyagers)</div>
</div>
</div>

</div>  

<div id="announcements" style="text-align:center;">
<h2>Announcements</h2>
<p>Stay Tuned for exciting updates!</p>
</div>

<div class="quote">
<h2><i>"Skills are Cheap, Passion is Priceless"</i></h2> 
<h4 style="font-family:Verdana, Geneva, Tahoma, sans-serif;"> -Unknown</h4> 
</div>
        </section>
        <footer>
<div class="footer">
  <address>  Contact us @passionfruitnps@gmail.com </address>
</div>
        </footer>
</body>

</html>
