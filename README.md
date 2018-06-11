# Canvas Experiments

Just a little ways to pass the time.

## React Boilerplate

Created from the original Create React App. An extension of the tool that aims to bring the standards I feel are neccessary for development while still maintaining the ability to work as much as possible without needing to eject the project.

All documentation from the original project follows below.

The project structure is based on [How To Better Organize Your React Applications](https://medium.com/@alexmngn/how-to-better-organize-your-react-applications-2fd3ea1920f1).

### Added functionality

- ReactSVG - Library to handle SVG icons while keeping bloat to a minumum, paired with a custom SVG component.
- React Router - For navigation according to the React standard.
- Sass - For ease of use. Might go over to styled components. Add a .scss-file and it will automatically create a css file you can link to.
- Absolute path - With the currect intended structure of the app, we want to get rid of the trailing dot dot problem. Thus, an .env-file was added to set NODE_PATH=src/
- EsLint - Setup to match my personal preferences. Don't like it? Then change it. Bitch.

This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).

Below you will find some information on how to perform common tasks.<br>
You can find the most recent version of this guide [here](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md).
