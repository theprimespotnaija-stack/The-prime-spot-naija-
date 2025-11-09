# The-prime-spot-naija-
```markdown The Prime Spot Naija
owned by Prince Osibote Fernandes Official website for The Prime Spot Nig event.  Pages - Home - About - Vote - Register - Contact  Features - Login popup - Mobile-friendly design - Built with HTML, CSS, and JavaScript  Contact - Phone: 09030405161 - WhatsApp: 08088473692 - Email: theprimespotnaija@gmail.com
*Pages:*
1. `index.html` (Home)  
2. `about.html`  
3. `vote.html`  
4. `contact.html`  
5. `register.html`  
+ `style.css`  
+ `script.js`  

I'll start with the *Home page* (`index.html`) layout including navbar, logo, and link to other pages.

1. `index.html`
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>The Prime Spot Nig - Home</title>
  <link rel="stylesheet" href="style.css"/>
</head>
<body>
  <header>
    <nav>
      <img src="logo.png" alt="The Prime Spot Logo" class="logo"/>
      <ul>
        <li><a href="index.html" class="active">Home</a></li>
        <li><a href="about.html">About Us</a></li>
        <li><a href="vote.html">Vote</a></li>
        <li><a href="register.html">Register</a></li>
        <li><a href="contact.html">Contact</a></li>
        <li><button onclick="openLogin()">Login</button></li>
      </ul>
    </nav>
  </header>

  <main>
    <section class="hero">
      <h1>Welcome to The Prime Spot Nig</h1>
      <p>Empowering the future. Join us in December 2025.</p>
    </section>
  </main>

  <!-- Login Modal -->
  <div id="loginModal" class="modal">
