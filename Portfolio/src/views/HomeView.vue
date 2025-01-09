<script setup>
</script>

<template>
<body>
    <header>Welcome to My Portfolio</header>

    <nav>
        <a href="#about-me">About Me</a>
        <a href="#work-showcase">My Work</a>
        <a href="#contact-me">Contact Me</a>
    </nav>

    <section id="about-me" class="about-me">
        <h2>About Me</h2>
        <p>Hello! I'm Tasha</p>
    </section>

    <section id="work-showcase" class="work-showcase">
        <h2>My Work</h2>
        <div class="work-item">
            <h3>Tararua All Breeds</h3>
            <p>Brief description of the project.</p>
            <a href="#" target="_blank">See Live</a>
        </div>
        <div class="work-item">
            <h3>Cafe Emineem</h3>
            <p>Brief description of the project.</p>
            <a href="#" target="_blank">See Live</a>
        </div>
    </section>

    <section id="contact-me" class="contact-me">
        <h2>Contact Me</h2>
        <p>If you'd like to get in touch, feel free to reach out at:</p>
        <ul>
            <li>Email: <a href="mailto:your.email@example.com">your.email@example.com</a></li>
            <li>Phone: (123) 456-7890</li>
            <li>Social Media: <a href="#" target="_blank">LinkedIn</a></li>
            <li>Github: <a href="#" target="_blank">Github</a></li>
        </ul>
    </section>

    <footer>
        &copy; 2025 [Your Name]. All rights reserved.
    </footer>
</body>


</template>



<style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ffe4e1;
            color: #333;
        }

        header {
            background-color: #ffcccb;
            padding: 20px;
            text-align: center;
            font-size: 2em;
            color: #fff;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #ffb6c1;
            padding: 10px;
        }

        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #fff;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        section {
            padding: 20px;
        }

        .about-me, .contact-me, .work-showcase {
            margin: 20px auto;
            max-width: 800px;
            background: #fff;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            padding: 20px;
        }

        h2 {
            color: #ff69b4;
        }

        .work-item {
            margin-bottom: 15px;
        }

        .work-item h3 {
            margin: 0;
        }

        .work-item a {
            display: inline-block;
            margin-top: 5px;
            padding: 5px 10px;
            background-color: #ff69b4;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
        }

        .work-item a:hover {
            background-color: #ff1493;
        }

        footer {
            text-align: center;
            padding: 10px;
            background-color: #ffb6c1;
            color: #fff;
            margin-top: 20px;
        }
    </style>