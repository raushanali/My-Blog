# My-Blog


 My Blog – Simple Guide Step-by-Step
This is a fun little Blog website project built with Node.js.
It’s perfect for learning how to:

Make web pages that show different content

Let users write, edit, and delete blog posts

Make your site look nice with CSS

Use JavaScript for cool features in the browser

📁 (Folder & File Guide step-by-step)
File/Folder	What It Means

app.js	The main switch that turns your site on

package.json	A shopping list of things this app needs to work

public/css/style.css	The “clothes” for your website – controls colors, fonts, and design

public/js/main.js	The “actions” for your site – makes buttons and menus do stuff

public/images/	A photo album for your website pictures

views/index.ejs	The home page of your blog

views/create.ejs, edit.ejs	Pages to write or edit blog posts

views/partials/	Pieces of the page that are reused everywhere (like the header and footer)

routes/auth.js	The map that explains how people sign in, sign up, or log out

middleware/auth.js	The security guard that checks if you’re logged in before letting you in certain pages

models/User.js	A template for what information a user should have

🚦 How to Start This Project
Install Node.js from nodejs.org

Open your project folder in Terminal or Command Prompt

Run this command to set up needed software:


npm install
Start the app with:


node app.js
Open your browser and go to:


http://localhost:3000
🏗️ EJS, JS, and CSS?
EJS – A tool that lets you put live data (like someone’s name or posts) into web pages automatically.

JS (JavaScript) – The magic that makes things happen on the page (like showing messages, toggling menus).

CSS – The style and decoration for the site (colors, spacing, fonts).

💡 Main Ideas
Server – The brain that sends web pages to people when they visit.

Express – A handy toolkit for building sites faster in Node.js.

Routes – Street addresses for your website

Middleware – Secret helpers that protect pages or check rules before letting you in.

Model – A rough sketch of what something looks like in your database (like "a user has a name, email, and password").

View – A web page people actually see.

Static Files – Things like , styles, or scripts.

🚀 What This App Can Do
Write blog posts and edit or delete them anytime

Read other people’s posts

Protect each user’s posts so only the owner can edit/delete
