# squint-vite-react

Small experiment with squint + vite(st) + react

## Requirements
- [npm](https://www.npmjs.com/)
- [babashka](https://babashka.org/)

## Usage
To run this example, `run npm install` and then one of the following commands:

### Development server
```bash
bb dev
```
Will start squint watch and vite dev server, the files will be 
generated on `public/js`.

### Tests watch
```bash
bb test:watch
```
Will start squint watch on tests and vitest test watcher, the files will be 
generated on `public/test`.

### Build
```bash
bb build
```
Will generate an production ready build on `public/dist` and a bundle status 
report in the root of the project `./bundle-visualization.html`.

## License
This is free and unencumbered software released into the public domain.
For more information, please refer to <http://unlicense.org>
