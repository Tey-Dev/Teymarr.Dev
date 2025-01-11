---
title: Home
layout: default
---

<link rel="stylesheet" href="style.css">

<div class="container">
    <div class="left">
        <img src="avatar.png" alt="Teymarr's Profile Picture" class="profile-pic">

        <div class="links">
            <a href="https://linkedin.com/in/teymarrpagedev" target="_blank">LinkedIn</a>
            <a href="mailto:teymarrpage@tuta.io">Email</a>
            <a href="resume.pdf" download>Download Resume</a>
        </div>
    </div>

 <div class="about-me">
    <h1>About Me</h1>
    <p>
        Hello, my name is <strong>Teymarr</strong> (Tay-Mar), and I’m a UI/UX front-end developer. I’m always on the lookout for innovative ways to enhance people’s lives in various ways. Equity and inclusion are always at the forefront of my mind when I’m planning new projects. I genuinely enjoy coding, visual design, and UX research.
    </p>
    <p>
        My personal design style is super minimalist, like you can see on my portfolio. I prefer sleek, clean interfaces that don’t rely on a lot of color or flashy stuff.
    </p>
    <p>
        My proficiency encompasses the following areas:
    </p>
    <ul>
        <li>PHP</li>
        <li>MySQL</li>
        <li>HTML5</li>
        <li>Bash</li>
        <li>Python</li>
        <li>Swift</li>
        <li>CSS</li>
        <li>JavaScript</li>
        <li>Ruby</li>
    </ul>
</div>

<div class="projects">
    <h2>My Projects</h2>
    <ul class="project-list">
        {% for post in site.posts %}
            <li>
                <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
            </li>
        {% endfor %}
    </ul>
</div>
<footer>
    Designed with ❤️ by Teymarr.
    <a href="https://github.com/yourusername">GitHub</a>
</footer>

