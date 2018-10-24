Neighborhood Map
======

This app was built using React as a project for Udacity's Front-End Web Developer Nanodegree program. The default map displays a handful of ice cream shops in Seattle, and allows for viewing data (the name and an image) associated with individual shops.

### Get Started

To launch the project:

**[View online](https://nataliecardot.com/react-neighborhood-map/)**

**View locally**
1. Clone the repository
2. Using a command line tool, navigate to the directory's location
3. Run `npm install`, which installs all modules listed as dependencies in package.json.
4. Run `npm start` to start the development server, opening the app in your default browser. (The command causes node to look for a scripts object in your package.json file, which in this case specifies "react-scripts start.")
5. Open the URL on the local server by navigating to `http://localhost:3000/` in your browser

### Service Worker

A service worker, for caching requests to the app's assets for offline use, is included in the production build. If you would like to use the app with the service worker enabled, launch the project from your computer, run `npm run build` then `serve -s build`, and visit `http://localhost:5000`.

### Dependencies

This project's code was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app), which installs the packages `react`, `react-dom`, and `react-scripts`. Additionally, `react-scripts` installs Babel, webpack, and `webpack-dev-server`, which provides auto-reload behavior, and provides a service worker.

I utilized the Google Maps API and the [react-google-maps](https://github.com/tomchentw/react-google-maps) component to integrate it into my app.

To display venue information for clicked markers, I used the [Foursquare Places API](https://developer.foursquare.com/places-api).

To deploy to GitHub Pages, I used the GH Pages [package](https://www.npmjs.com/package/gh-pages), with the help of [this tutorial](https://codeburst.io/deploy-react-to-github-pages-to-create-an-amazing-website-42d8b09cd4d).
