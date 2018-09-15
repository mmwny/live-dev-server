# Static-Live-Server

### A simple static development live server that compares npm scripts, gulp, and webpack doing the same job. Built for my learning and for you to use.

Static-Live-Server (SLS) is a project I created to learn and compare npm scripts, gulp, and webpack as task runner and build tools. SLS was created to optimize the creation of static sites, SLS will watch changes to you html, css, scss, js, and images and reload the browser. Using BrowserSync, SLS allows you to compile your site to a production build, test across multiple devices on your network, and test dependencies that require HTTPS. SLS will compile SASS to CSS, concatenate and minify CSS, concatenate and minify JS, compile ES6 to ES5, and minify images.

Clone the repo and run ```npm install``` from there you can remove my HTML, SASS, and Javascript files and insert your own. The server will compile, rebuild the dist folder, and reload the browser with your changes. The default configuration runs the browser over HTTPS and allows you to test your site across devices on your local network using BrowserSync.

#### Gulp and Webpack will be added shorty in 2.0/3.0