# Website for the Undergraduate Psychology Research Journal at UCLA

url here...

## Setup Instructions

Hopefully you are on a Linux or OS/X platform. If so, you can use the terminal to use npm and Grunt (if you run into installation issues, use sudo):

* First, you need Node.js / npm: [http://nodejs.org/download/](http://nodejs.org/download/ "node.js / npm")

* And get Grunt: [http://gruntjs.com/getting-started](http://gruntjs.com/getting-started "Grunt")

(If you are on Windows :(, then you'll have figure out how to install and use Node.js and Grunt)

Now run the following command in the terminal, in this project's root directory:

    $ npm install

In order to build the site from the src/ folder (i.e. compile Handlebars files to HTML, minify CSS, etc.), run the following command (again, from the root directory of this project):

    $ grunt

If you are unfamiliar with Grunt, you can find more information in the documentation on the Grunt website, or examine the provided Gruntfile.js in this project.

## A Note to Future Maintainers:

To modify this project, it is entirely possible to simply edit the compiled HTML files, in the compiled build/ folder. However, I strongly recommend that you use the handlebars templates and grunt build tasks that are available. If you have any questions, feel free to reach me at [rhansby@gmail.com](rhansby@gmail.com).

