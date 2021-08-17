This is a simple template to build applications with Rust + wasm to a JS bundle with Webpack.

To start the development server :
use 'npm run dev' for development server

To create your distribution (dist folder) ready to use :
use 'npm run build' for production mod


Use the src folder in the root to add your custom HTML and CSS. The 'script.js' file is used to contain all the js of your application. You just need to import your files in 'script.js' via an import ... from 'path/to/the/folder.js' (Webpack will build a bundle containing all your minified js). The static folder is at your disposal for all other assets like images or custom fonts.

PS: The pkg folder in the root can be ignored ! (if someone has a solution to block his generation I'm interested)