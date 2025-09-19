<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Sunnnydale School Information Hub</title>
  <style>
  footer {
      text-align: center;
      margin-top: 30px;
      padding: 15px;
      background: #1E90FF;
      color: white;
      border-radius: 8px;
    }
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: Arial, sans-serif;
      background-color: #c7eaec;
      color: #333;
      line-height: 1.8;
    }
     header {
      text-align: center;
      padding: 20px;
      background: #1E90FF;
      color: white;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }
    h1 {
      font-size: 24px;
      font-weight: bold;
      color: #1E90FF;
      text-align: center;
    }

    /* Body and General Styling */
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
      background-color: #f9f9f9;
    }

    h2 {
      margin-top: 20px;
    }
    h2.mission {
      color: #32CD32;
    }
    h2.events {
      color: #FFA07A;
    }
    h2.contact {
      color: #20B2AA;
    }

    #upcoming-events {
      background-color: #FFFFE0;
      padding: 10px;
      border-radius: 6px;
    }
    .outdoor {
      background-color: #AFEEEE;
      padding: 5px;
      border: 1px solid #B0E0E6;
      border-radius: 4px;
      margin: 4px 0;
    }
    .contact-box {
      background-color: #f8f3f3;
      padding: 10px;
      border-radius: 6px;
      margin-top: 10px;
    }
  </style>
</head>
<body>

  <h1>Welcome to Sunnydale School</h1>

  <h2 class="mission">Mission Statement</h2>
  <p>Our mission is to provide quality education and foster a supportive learning environment that helps students grow academically, socially, and emotionally.</p>

  <h2 class="events">Upcoming Events</h2>
  <ul id="upcoming-events">
    <li data-event-type="indoor" title="Event Type: Indoor">Science Fair - <span style="font-weight: bold; color: red;">June 10</span></li>
    <li data-event-type="outdoor" title="Event Type: Outdoor" class="outdoor">Sports Day - <span style="font-weight: bold; color: red;">June 20</span></li>
    <li data-event-type="indoor" title="Event Type: Indoor">Art Exhibition - <span style="font-weight: bold; color: red;">July 5</span></li>
    <li data-event-type="outdoor" title="Event Type: Outdoor" class="outdoor">Community Picnic - <span style="font-weight: bold; color: red;">July 15</span></li>
  </ul>

  <h2 class="contact">Contact Us</h2>
  <div class="contact-box">
    <p>Email: <a href="mailto:info@sunnydaleschool.edu" title="Click to copy email">info@sunnydaleschool.edu</a></p>
    <p>Phone: <a href="tel:+123456789" title="Click to copy email">+1 234 567 89</a></p>
  </div>
  <footer>
  <p>&copy; Sunnydale school | all rights preserved 2025</p>
  </footer>
</body>
</html>
