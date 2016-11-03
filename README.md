# Intro to Webpack

I put this repository together to serve as a crash course for getting started with [Webpack](https://webpack.github.io/). It includes a [presentation](./presentation) and a number of small apps to demonstrate the basic and differentiating features of the module bundler.

Please [create an issue](https://github.com/jakepeyser/webpack-intro/issues/new) if you see any innacuracies in the content.

## Sample Apps

**[basics](./basics)** - Creates a simple bundle by taking a file from source and bundling it to a static content folder

**[module bundling](./module_bundling)** - Demonstrates how Webpack crawls the dependency graph and can bundle multiple JS files into a single target

**[task running](./task_running)** - Consists of a basic [React](https://facebook.github.io/react/) app where we use Webpack to transpile the jsx code, bundle all dependencies (3rd party and our own), and minify the code with plugins

**[code splitting](./code_splitting)** - Splits the app code into multiple output bundles by chunking the dependencies into separate app and vendor JS files

### Building and Running the Apps

Inside each app folder, run the following:

```sh
npm install
npm run build
```

After Webpack finishes building, open up the `public/index.html` file in a browser to see the console or rendered output.

## Presentation

The deck is broken down as follows:

- Benefits of task runners and bundlers
- Sample app walkthroughs
- Key takeaways for new React developers
- Helpful resources to explore Webpack
- Popular Webpack plugins and loaders

For a more detailed explanation of the content and flow of the talk, check out the presentation notes.