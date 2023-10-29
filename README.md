<!DOCTYPE html>
<html>
<head>
    <title>Danny McCombs</title>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to Danny McCombs' Page</h1>
    </header>
    <nav>
        <ul>
            <li>
                <a href="https://youtube.com/@sherneon?si=MRJYo3fKTyUw30n7">
                    <img src="youtube.png" alt="YouTube" class="social-image">
                </a>
            </li>
            <li>
                <a href="https://soundcloud.com/sherneon" class="social-link">
                    <img src="soundcloud.png" alt="SoundCloud" class="social-image">
                </a>
            </li>
        </ul>
    </nav>
    <section>
        <p>Hello, I'm Danny McCombs. Welcome to my GitHub Pages website.</p>
        <p>Feel free to explore my content on <a href="https://www.youtube.com/user/Sherneon" target="_blank">YouTube</a> and <a href="https://soundcloud.com/sherneon" target="_blank">SoundCloud</a>.</p>
    </section>
</body>
</html>
/* Add 3D effect to the images on hover */
.social-link:hover .social-image {
    transform: scale(1.1); /* Enlarge the image on hover */
    transition: transform 0.3s; /* Add a smooth transition effect */
}

.social-image {
    width: 100px; /* Adjust the width to your preferred size */
    height: auto;
}

/* You can customize the styling further as needed */
