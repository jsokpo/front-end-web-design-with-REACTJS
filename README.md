Sr. Front End Web Designer Crossover Project Evaluation
===

### About the project

This project tech trial aims to shows the integrations and dependences of CSS animation frameworks in a web page design.
The solution is built with a modern MVVM/MVP/MVCjs architecture implemented with a CSS framework of Compass. This tech 
trial was intended to be a test on developing enterprise software solution. The design is for a single list with elements
that can expand and contract, with only one element open at a time. Other notable libraries used in this project are:

- Twitter Bootstrap 3
    + It is used to facilitate the style of the page.
- ReactJS
    + Used to mockup the delivery of data through the network. Basically we call the `fetch()` on the `Data` module and it returns a streams of items which will be updated through time randomly. Only three of this items will be being run and it has a 2% chance of failing. If one of the items fails or succeeds the next one starts running. The process stop when all the items are finished.
- hjs-webpack
    + This is a very nice project developed by Henrik Joreteg that simplifies webpack's config. With it I setup my project to Hot-Reload the project on the fly, mantaining the app state, and Stylus as my CSS preprocessor. Also, I added `url-loader` to concatenate some assets.

### Run the Project Locally

1. Clone the repo

```
git clone https://github.com/jsokpo/front-end-web-design-with-REACTJS.git
```

2. Change directory to the `front-end-web-design-with-REACTJS` folder and run `npm install`
3. Run `npm start` to start the server.
4. Visit `http://localhost:3000` to see the site in display.
