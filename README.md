## download the rep and || `npm install` to install the depencies

## on production remeber to go to tailwiond.config.js file and change this to `true`

purge: {
    `enabled: false`,
    content: [
      "./src/**/*.html",
      "./src/**/*.js",
      "./src/*.js",
      "./src/**/*.jsx",
    ],
  },

this so you get a very small css file from tailwind , it's baisicly delete the unused styles 
