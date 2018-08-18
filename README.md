# contactform
This is a project on how to build a html5 contact using php
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css?family=Lato:300,400,700" rel="stylesheet">
    <title>Contact form php, Roxanne Reyes</title>
</head>
<body>
    <header>
<a href="#"><img class="header-image" src="waelogo.png"</a>

<ul>
    <li><a href="#">About Wae Tech</a></li>
    <li><a href="#">Our Products</a></li>
    <li><a href="#">Contact Us</a></li>
    
</ul>
</header>



    <main>
        
        <form id="contact-form" action="contactform.php" method="post">
            <h2>Tell me about it!</h2>

            <p class="intro">Do you have an idea for a new project? At Wae Tech, if you value web design as much as I do,
                then we can definitely talk. 
                Thank you!
            </p>
            <p class="input-field"><label for="Fullname">Full Name</label></p>
            <input type="text" id="name" name="name" placeholder="First and Last Name" required>

            <p class="input-mail"><label for="Email">Email</label></p>
            <input type="text" id="email" name="mail" placeholder="Your e-mail" required>

            <p class="input-subject"><label for="Subject">Subject</label></p>
            <input type="text" id="subject" name="subject" placeholder="What's this about?">

            <p class="input-message"><label for="message">Message</label></p>
            <textarea name="message" id="message" placeholder="Message"></textarea>

            <input type="submit" name="submit" id="submit" tabindex="5" value="submit">Send Mail</button>
        </form>
    </main>    
<footer> 
    <p class="footer">Copyright Wae Tech Solutions All rights reserved 2018</p>
</footer>
</body>
</html>
