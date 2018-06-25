# base64-font-conversion

Simple harness for generating the base64 version of font files for web use.

## Getting Started

- run the npm install command in the terminal to install the project dependacies

```bash
$ npm install
```

## How to Use

- copy font files into ```src``` folder
- update the ```src/font.scss``` file with the font rules ensuring that the fonts being referenced exist in the folder.
- run the build command in the terminal

```bash
$ npm run build
```

- retrieve the updated css output in ```output/font-converted-to-base64.css```
