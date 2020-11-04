gulp style
Error: Missing binding /var/www/public/web/node_modules/gulp-sass/node_modules/node-sass/vendor/linux-x64-83/binding.node
Node Sass could not find a binding for your current environment: Linux 64-bit with Node.js 14.x


RUN : 

Check "dependencies": {
        "autoprefixer": "^9.7.6",
        "browser-sync": "^2.26.7",
        "cssnano": "^4.1.10",
        "gulp-install": "^1.1.0",
        "gulp-postcss": "^8.0.0",
        "gulp-sourcemaps": "^2.6.5",
====>         "node": "^15.0.1"  MUST BE LESS THEN 15
    }

npm install node-sass@4.10.0
nodejs node_modules/node-sass/scripts/install.js
npm rebuild node-sass


