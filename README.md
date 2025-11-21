# My-portfolio
# I am from 1st year and I am going to upload my first portfolio.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nitin Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <div class="container">
            <img src="image.png" class="profile" alt="profile photo">
            <h1>Nitin Kumar Sksena</h1>
            <p>Front-End Developer | Computer Science Student</p>
        </div>
    </header>

    <section class="about">
        <h2>About Me</h2>
        <p>
            I’m a CSE student currently learning web development. 
            I enjoy creating simple and clean interfaces using HTML and CSS. 
            I’m also learning JavaScript to build interactive pages.
        </p>
    </section>

    <section class="skills">
        <h2>Skills</h2>

        <div class="skill-item">
            <span>HTML</span>
            <div class="bar"><span style="width: 90%"></span></div>
        </div>

        <div class="skill-item">
            <span>CSS</span>
            <div class="bar"><span style="width: 80%"></span></div>
        </div>

        <div class="skill-item">
            <span>JavaScript</span>
            <div class="bar"><span style="width: 60%"></span></div>
        </div>

        <div class="skill-item">
            <span>Responsive Design</span>
            <div class="bar"><span style="width: 75%"></span></div>
        </div>

    </section>

    <section class="contact">
        <h2>Contact Me</h2>

        <form onsubmit="return validateForm()">
            <input type="Nitin Kumar Sksena" id="Nitin Kumar Sksena" placeholder="Nitin Kumar Sksena">
            <input type="nitinsksena1234@gmail.com" id="nitinsksena1234@gmail.com" placeholder="nitinsksena1234@gmail.com">
            <textarea id="“Hey, I’m Nitin! I’m a CSE student who likes to create websites and learn cool things on the internet. Right now I’m working with HTML and CSS, and I’m slowly stepping into JavaScript. Always learning and trying to get better.”" placeholder="“Hey, I’m Nitin! I’m a CSE student who likes to create websites and learn cool things on the internet. Right now I’m working with HTML and CSS, and I’m slowly stepping into JavaScript. Always learning and trying to get better.”"></textarea>
            <button type="submit">Send</button>
            <p id="status"></p>
        </form>

    </section>

    <script src="script.js"></script>
</body>
</html>
