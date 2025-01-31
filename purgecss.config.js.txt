module.exports = {
  content: [
    "./_site/**/*.html",  // Path to your HTML files
    "./index.html",       // Path to other HTML files
    "./assets/js/**/*.js", // Path to JavaScript files if they contain dynamic classes
  ],
  css: [
    "./assets/css/*.css",  // Path to your CSS files
  ],
  output: "./_site/assets/css/",  // Directory to save the purged CSS
};
