# Your own project

Build an app of your choice.

- You are free to use any technologies covered so far. You are welcome to try new technologies you find interesting.
- Keep it simple. Aim to get the core functionality working on day one. You can then extend it on days two and three.
- Use pen and paper to draw a diagram of the layout before starting to code.
- Think about how to organise your data in advance
- Make sure your app is responsive
- Keep it simple

## Technical notes

* Run `npm install` after cloning to download all dependencies
* Use `npm run dev -- --watch` to build React
* Use `node server.js` to run the Node server in another tab
* You can view the site at [http://localhost:8080](http://localhost:8080)
* If you would like to user `nodemon` to automatically rebuild your server, run `npm run server`

* The node server file is `/server.js`
* To avoid using `hbs` unnecessarily, we have placed `index.html` in the `/static` folder and are serving it as a static html file. The `static` route is configured to serve files from `/` path rather than `/static`.

* Place all static files such as images and CSS in the `static` folder.

## README

* Produce a README.md which explains
  * what the project does
  * what technologies it uses
  * how to build it and run it
  * any unresolved issues the user should be aware of
