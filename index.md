---
title: Home
layout: default
---

<link rel="stylesheet" href="style.css">

<div class="container">
    <div class="left">
        <img src="avatar.png" alt="Teymarr's Profile Picture" class="profile-pic">

    
<h1 class="name">Teymarr</h1>
<h2 class="job-title">UI/UX Front-End Developer</h2>

        <div class="links">
            <a href="https://linkedin.com/in/teymarrpagedev" target="_blank">LinkedIn</a>
            <a href="mailto:teymarrpage@tuta.io">Email</a>
            <a href="resume.pdf" download>Download Resume</a>
        </div>
    </div>

 <div class="about-me">
    <h1>About Me</h1>
    <p>
        Hi there! I’m Teymarr (Tay-Mar), a UI/UX front-end developer. I’m always on the hunt for cool ways to make people’s lives better. Equity and inclusion are super important to me when I’m working on new projects. I love coding, designing, and doing research on user experience.

My personal style is super minimalist, like you can see on my portfolio. I prefer clean, simple interfaces that don’t have too much color or flashy stuff.

I can code with a bunch of languages, including PHP, MySQL, HTML5, Bash, Python, Swift, CSS, JavaScript, and Ruby. Feel free to check out my projects in bold at the bottom of the page to see some of my favorites!
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

