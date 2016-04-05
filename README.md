# Fabricator Starter ###################################################################################################

A starter project for your Fabricator based toolkit. Use to start from, or as an example on how to build your toolkit.

# IN DEVELOPMENT! ######################################################################################################

## Using this Toolkit ##################################################################################################

**You only need to consider this section if you just want to use this toolkit into your project.**

- This toolkit has all it's files generated into the folder: `dist/**/toolkit/`.
- When making this a npm module, your project can easily include the toolkit files through gulp.

------------------------------------------------------------------------------------------------------------------------

## Tools ###############################################################################################################

- [Fabricator Builder](https://github.com/dietergeerts/fabricator) - used for building the Toolkit.

## Getting Started - Developing ########################################################################################

The Toolkit requires [node.js](http://nodejs.org). Make sure you have `v0.12` or higher installed before proceeding.

**Start the local development environment:** `$ npm start`

------------------------------------------------------------------------------------------------------------------------

## Build/Release Process ###############################################################################################

1. **Testing** this toolkit on all relevant browsers.
2. **Update** the **version** number in package.json.
3. **Commit** all your changes!
4. **Build** for production release: `$ npm run build`  
    *This will build both a static documentation site and all toolkit files, outputted into the `dist` directory.*  
5. **Publish** your package for easier use in your projects.
6. **Deploy** the documentation site for easy access for developers.      
