The theme.js assets are based on the assets from v4.43.1

fieldflow js was replaced with the new fieldflow js from gcweb 18.3 [found in the gcweb](https://github.com/wet-boew/gcweb.git) (fieldflow.js) See install instructions for gcweb

For the rest of the code in theme.js , manually replaced deprecated jQuery3 calls with jQuery4 pure js , example $.isArray() .

#Instructions how to compile the theme.js into theme.min.js
`npx terser js/theme.js --compress -o js/theme.min.js`
