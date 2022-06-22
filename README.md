<img src="https://user-images.githubusercontent.com/59726149/175109651-aadef90c-edf7-4ad0-96ca-bdb4a743f5c1.png" width="50%" />
  
## A Template built for the [Replit Template Jam](https://blog.replit.com/template-jam), combining Pug, Sass and CoffeeScript, bundled with Parcel.

/ proʊ proʊ sɛs ər /<br>
*noun*<br>
Portmanteau of *professional preprocessor*. Trio of web preprocessors designed to make creating websites simple (and eliminate curly braces).

## Running
[![Run on Replit badge](https://replit.com/badge/github/malted/ProProcessor-Minimal)](https://replit.com/@malted/ProProcessor-Minimal)

Run `npm run start` to start the development server

### Templating
Website markup is written in [Pug](https://pugjs.org), which compiles down to vanilla HTML.

An example template can be found at `/src/components/index.pug`.
Additional components can be found in the `components` directory in the same parent directory.

### Styles
Website styling is written in [Sass](https://sass-lang.com), which compiles down to vanilla CSS.

An example stylesheet can be found at `/src/styles/style.sass`
Additional components can be found in the `components` directory in the same parent directory.



### Scripts
Website logic is written in [CoffeeScript](https://coffeescript.org), which compiles down to vanilla JavaScript.

An example script can be found at `/src/scripts/index.coffee`.

### Bundler
The website source is bundled with [Parcel](https://parceljs.org), which is the simplest bundler IMHO. It Just Works:tm:.
