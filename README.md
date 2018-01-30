[![npm](https://img.shields.io/npm/v/react-custom-loader.svg)](https://www.npmjs.com/package/react-custom-loader)
[![Maintainability](https://api.codeclimate.com/v1/badges/002dca73066acfcf20ec/maintainability)](https://codeclimate.com/github/dougllima/react-custom-loader/maintainability) [![Test Coverage](https://api.codeclimate.com/v1/badges/002dca73066acfcf20ec/test_coverage)](https://codeclimate.com/github/dougllima/react-custom-loader/test_coverage)
[![dependencies Status](https://david-dm.org/dougllima/react-custom-loader/dev-status.svg)](https://david-dm.org/dougllima/react-custom-loader#info=devDependencies) [![dependencies Status](https://david-dm.org/dougllima/react-custom-loader/status.svg)](https://david-dm.org/dougllima/react-custom-loader)

# React Custom Loader
A simple and customizable react loader.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.
- Fork/Clone this repo.
- Run `npm install`.
- Ready to go! ✅ 

### Seting up to contribute

Run the lint command
```
// Single command, repeat it on each change on files in lib/
npm run lint
// Or run the command above and it will watch for changes
npm run lint:watch
```
Run the build command
```
// Single command, repeat it on each change on files in lib/
npm run build
// Or run the command above and it will watch for changes
npm run build:watch
```
Add a symlink to the project
```
npm link
```
Link your project with the symlink
```
cd your-project-path
npm link react-custom-loader
```
You can now import the component
```
import { Loader } from 'react-custom-loader'
```

## Running the tests - TODO
Tell user how to run tests

### Break down into end to end tests - TODO
Explain what these tests test and why

### And coding style tests - TODO
Explain what these tests test and why
```
Give an example
```

## Deployment
Copy the content build folder and importe the component from the path `build\index.js` as above
```
import { Loader } from 'path-to-build/build/index.js'
```
Or you can install the last version
```
npm install react-custom-loader
```

## Versioning
We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/dougllima/react-custom-loader/tags). 

## Authors
- **Douglas Lima** - *Initial work* - [dougllima](https://github.com/dougllima/).
- **Ivan Cunha** - ***extendDeep** function and ideas* - [ivansantos1189](https://github.com/ivansantos1189/).

See also the list of [contributors](https://github.com/dougllima/react-custom-loader/graphs/contributors) who participated in this project.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments
Making based on
- [This awesome guid](https://hackernoon.com/building-a-react-component-library-part-1-d8a1e248fe6c) made by [alanbsmith](https://github.com/alanbsmith)
- [This greate article](https://www.javascriptjanuary.com/blog/the-open-sourcerers-magic-spell-book) written by [Sebastian Golasch](https://twitter.com/asciidisco) and edited by [Rodney Rehm](https://twitter.com/rodneyrehm).


