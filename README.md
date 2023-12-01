# Understanding Typescript - Drag and Drop Project

`ut_drag_and_drop_project` is a front end application that allows you to add projects and change their status from active to finished by dragging and dropping project cards from field to field.

The project was implemented during the **Understanding Typescript** course on Udemy by Maximilian Schwarzmüller.

## Requirements

To run the installation script, `Node` and `TypeScript`must be installed.

## Installation

Clone the repository from GitHub. You can use SSH:
```
git clone git@github.com:jerzy-jarczynski/ut_drag_and_drop_project.git
```

Open a terminal in the project directory and install needed dependencies with `npm` packet manager:
```
npm install
```
After successful installation, you can run the start script:
```
npm run start
```
Then open a separate terminal tab and compile TypeScript file into JS. You can make it by running TypeScript in watch mode:
```
tsc -w
```
## Used technologies

`HTML`, `CSS`, `ES6`, `TypeScript`

> An interesting element of the HTML code is the use of template elements to render the view. The project is based on OOP concepts (classes, inheritance, abstraction).
The TypeScript code uses features such as decorators, interfaces, enums, generic types and constraints, unions.
This is the first application in which I successfully implemented the drag and drop feature.

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)

## Demo

You can see living demo without cloning or downloading the repository on Codepen:

https://codepen.io/jerzyjarczynski/pen/qBgJBrR

## Used Versions

Node: v21.2.0
TypeScript: 5.2.2
JavaScript: ES6