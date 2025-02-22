# Web-Dev

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <title>Your Name - Biography</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1>Your Name</h1>
    <div class="job-title">Web Developer</div>
    <p>
        Hi, I'm Your Name! I'm a web developer with a passion for creating beautiful and functional websites. 
        I specialize in HTML, CSS, and JavaScript. When I'm not coding, I enjoy hiking, reading, and exploring new technologies.
    </p>

    <h2>Contact Information</h2>
    <ul>
        <li>Email: <a href="mailto:mustafa.mohd@dcmail.ca">mustafa.mohd@dcmail.ca</a></li>
        <li>Website: <a href="https://yourwebsite.com">https://yourwebsite.com</a></li>
        <li>Phone: <a href="tel:+1234567890">+123 456 7890</a></li>
    </ul>
</body>
</html>
/* General Styles */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 20px;
    padding: 0;
}

/* h1 Styles */
h1 {
    color: hotpink; /* Pink color */
    border-bottom: 10px dotted purple; /* Purple dotted border */
}

/* h2 Styles */
h2 {
    font-style: italic; /* Italic text */
}

/* Contact Details Styles */
ul {
    background-color: #eeeeee; /* Light gray background */
    border: 5px solid purple; /* Purple border */
    padding: 20px; /* Padding inside the box */
    list-style-type: none; /* Remove bullet points */
}

/* Link Styles */
a {
    color: #007BFF; /* Default link color */
    text-decoration: none; /* Remove underline */
}

a:hover {
    color: green; /* Green color on hover */
    text-decoration: underline; /* Underline on hover */
}

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <title>Cool Looking Box</title>
    <link rel="stylesheet" href="cool-box.css">
</head>
<body>
    <div class="cool-box">
        <h1>Cool Looking Box</h1>
        <p>This is a cool-looking box with a gradient background, rounded corners, and shadows.</p>
    </div>
</body>
</html>
/* Cool Box Styles */
.cool-box {
    width: 300px;
    height: 200px;
    margin: 50px auto; /* Center horizontally */
    padding: 20px;
    background-color: #f0f0f0; /* Light gray background */
    border: 1px solid #ccc; /* Border */
    border-radius: 15px; /* Rounded corners */
    box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.3), -5px -5px 10px rgba(255, 255, 255, 0.5); /* Multiple shadows */
    font-size: 1.2rem; /* Use rem units */
    background: linear-gradient(135deg, rgba(0, 0, 0, 0) 0%, rgba(0, 0, 0, 0.2) 30%, rgba(0, 0, 0, 0.2) 100%); /* Gradient */
}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <title>Typesetting Homepage</title>
    <link rel="stylesheet" href="typesetting.css">
</head>
<body>
    <header>
        <h1>Welcome to My Homepage</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <article>
            <h2>About Me</h2>
            <p>Hi, I'm Your Name! I love web development and design.</p>
        </article>
    </main>
    <footer>
        <p>&copy; 2023 Your Name</p>
    </footer>
</body>
</html>
/* Fonts */
@font-face {
    font-family: 'CustomFont1';
    src: url('font1.woff2') format('woff2');
}

@font-face {
    font-family: 'CustomFont2';
    src: url('font2.woff2') format('woff2');
}

/* General Styles */
body {
    font-family: 'CustomFont1', sans-serif;
    font-size: 1rem;
    line-height: 1.6;
    margin: 0;
    padding: 0;
}

h1, h2 {
    font-family: 'CustomFont2', serif;
}

/* Navigation Bar */
nav ul {
    list-style-type: none;
    padding: 0;
    display: flex;
    justify-content: center;
    background-color: #333;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

nav ul li a:hover {
    text-decoration: underline;
}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <title>Layout Comprehension</title>
    <link rel="stylesheet" href="layout.css">
</head>
<body>
    <header>
        <h1>Layout Comprehension</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <article>
            <h2>Article Title</h2>
            <p>This is the main content of the article.</p>
            <img src="image1.jpg" alt="Image 1">
        </article>
        <aside>
            <h2>Sidebar</h2>
            <p>This is the sidebar content.</p>
        </aside>
    </main>
    <footer>
        <p>&copy; 2023 Your Name</p>
    </footer>
</body>
</html>
/* General Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

/* Navigation Bar */
nav ul {
    list-style-type: none;
    padding: 0;
    display: flex;
    justify-content: center;
    background-color: #333;
    position: sticky;
    top: 0;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

/* Main Layout */
main {
    display: flex;
}

article {
    flex: 3;
    padding: 20px;
}

aside {
    flex: 1;
    padding: 20px;
    background-color: #f4f4f4;
}

/* Images */
img {
    float: left;
    margin: 0 15px 15px 0;
    width: 150px;
    height: auto;
}
