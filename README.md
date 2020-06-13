# esbuild react starter

Simple react starter using [estrella](https://github.com/rsms/estrella). A few points if you're coming from create-react-app:

- Directly importing CSS files isn't yet supported by esbuild (instead you would have to add it to your `public/index.html` file)
- create-react-app inlines images for you if you import them, here you would have to add your images to the `public` directory & then link them accordingly from your js
- Your production build & dev server both use the public directory (you can change this by changing the values in the `build.js` file)
