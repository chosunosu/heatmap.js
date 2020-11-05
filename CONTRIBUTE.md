# How to contribute to heatmap.js

1. [Prerequisites](#prerequisites)
2. [Coding Style](#coding-style)
3. [Contributing](#contributing)
4. [Reporting Bugs](#reporting-bugs)
5. [Testing](#testing)
6. [Documentation](#documentation)
7. [Code of Conduct](#code-of-conduct)

## Prerequisites

- npm
- grunt-cli
- Texteditor (recommended: Sublime)

## Coding Style

- Tabs or Spaces? Spaces! 2 spaces.
- You should follow the style and conventions of the prexisting codebase. 

## Contributing

A contribution to heatmap.js is not a plugin. If you want to contribute a plugin a similar workflow applies but you don't have to run the watcher (because it won't go into the build). You can also contribute to heatmap.js by [helping others on Stack Overflow](http://stackoverflow.com/questions/ask?tags=heatmap.js). Finally, spread the word about heatmap.js with your friends!

1. Checkout repository

2. Install - heatmap.js uses NodeJS. Run the following commands in the root of your heatmap.js files to install dependencies:

- `   npm install`

3. Create a new feature branch

4. Add new file to watcher

- If you're introducing a new file you'll have to add it to the [`package.json`](http://stackoverflow.com/questions/ask?tags=heatmap.js)'s buildFiles

5. Run watcher

- `   grunt`

6. Add your code
7. Add an example/tests
8. Create pull request

## Reporting Bugs

Report bugs on the project's issues page. Please search the preexisting issues for any similar cases. If a similar case exists, please add your bugs as comments to that issue.

## Testing

You can run tests from the command line with the following command:

-`npm test`

## Documentation

Documentation is currently located [here](https://www.patrick-wied.at/static/heatmapjs/?utm_source=gh). If you'd like to add to the documentation, please leave your contribution as an issue at [https://github.com/pa7/heatmap.js/issues](https://github.com/pa7/heatmap.js/issues).

## Code of Conduct

heatmap.js uses the Code of Conduct from [Contributor Covenant]('https://github.com/pa7/heatmap.js/issues'). This is one of the more widely used Code of Conducts that is specifically written to be reusable for FOSS projects. Please follow the code :)
