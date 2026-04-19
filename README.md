# MyTML 

This is a project I'm building while learning HTML (I understand some of CSS and I am slowly getting into JavaScript)

Live Website: https://mytml.pages.dev

---

## About

I'm using this project to practice how websites are actually built — not just following tutorials, but trying things myself and improving over time.
It’s not meant to be perfect. It’s where I test ideas, make mistakes, and figure things out.

---

## Tech

* HTML5
* CSS3
* JavaScript

---

## Progress

* Basic structure is done
* Working on layout and styling
* Planning to make it responsive next

---

## What's next
* Clean up the design
* Improve spacing and layout
* Add more pages
* Make it work better on different screen sizes
* Fourth page (currently under construction)

---

## Code
Body tag of home page:
```
<body>

<header>
  <nav>
    <a href="/home-page">Home</a>
    <a href="/about">About</a>
    <a href="/projects">Projects</a>
    <a href="/contact">Contact</a>
  </nav>
</header>

<div class="box">
  <h2>Projects</h2>
   <p>This web page: <strong>Portfolio Website</strong></p>
   <p>Project 2 is <strong>coming soon</strong>. A <em>landing page</em>.</p>
<br>
<br>
  <a class="button-style" href="/second-page">View Second Page</a>
  <p>Nothing to see here...</p>
</div>
</body>
```
JavaScript of third page:
```
<script>
    function changeText() {
        var el = document.getElementById("changeTEXT");
        el.innerHTML = "Hello, World!";
        el.style.fontFamily = "'Space Mono', monospace";
    }
</script>
```
File ```index.html``` redirecting to ```home-page.html```:
```
<!DOCTYPE html>
<html>
<head>
    /* I want the home page to be home-page.html but, Cloudflare defaults index.html as the main page, which is why I did this. */
    <link rel="icon" type="image/x-icon" href="favicons/desktopfavicon.ico">
    <link rel="icon" type="image/png" href="favicons/mobilefavicon.png">
    <link rel="apple-touch-icon" href="favicons/mobilefavicon.png">
<meta http-equiv="refresh" content="0; url=/home-page">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="google-site-verification" content="KNfNIOGvpxUJlNMBeT9MOtkKelI-1A1UyOVs1yXMJDI" />
    <title>Rabid | Portfolio - MyTML</title>
     <meta property="og:title" content="MyTML - Portfolio" />
     <meta property="og:description" content="A portfolio made by me, Rabid." />
     <meta name="theme-color" content="#7289da">
<script type="text/javascript">
</script>
</head>
</html>
```
## Notes
This is a learning project, so things will change a lot. Some parts might break, get removed, or be completely redone that’s part of the process.
