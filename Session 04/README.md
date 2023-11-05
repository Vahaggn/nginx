# Nginx Tutorial - Session 04: Serving Static Content
- Video of this Session: [Link](https://www.youtube.com/watch?v=I_Qul4thJMU&list=PL63NzugBawGe1nUhAveIBfYHtbiXvKKEb&index=4) 

Welcome to Session 04 of the Nginx Persian Tutorial, where we'll explore how to serve static content using Nginx.

- **Vahag Gragoosian**
  - DevOps Enthusiast
  - GitHub: [Vahag's GitHub](https://github.com/Vahaggn)
  - LinkedIn: [Vahag's LinkedIn](https://www.linkedin.com/in/vahag-gragosian/)
  - Youtube Channel: [Vahag's Youtube](https://www.youtube.com/@vahaggn) 

## Table of Contents

1. [Create a HTML File](#create-a-html-file)
2. [Host it via Nginx](#host-it-via-nginx)

## Create a HTML File

In this section, we'll create a simple HTML file that we want to serve using Nginx. You can use any text editor to create your HTML file. Here's a basic example:

# HTML File Example
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple HTML Page</title>
</head>
<body>
    <header>
        <h1>Welcome to My Simple HTML Page</h1>
    </header>

    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>

    <main>
        <h2>About Us</h2>
        <p>This is a simple HTML page created for demonstration purposes.</p>
    </main>

    <footer>
        <p>&copy; 2023 My Simple Page</p>
    </footer>
</body>
</html>
```
# Nginx Config File Example
```nginx
server {
   listen 80 default_server;
   server_name vahag.pizza;


   location / {
      root /etc/nginx/conf.d;
      index index.html;
   }
}
```