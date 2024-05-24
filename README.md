# Electron Overlay Application

This is a simple Electron application that creates a full-screen overlay with adjustable transparency. The overlay can be hidden or shown with a keyboard shortcut, and the transparency can be adjusted incrementally.

## Features

- Full-screen overlay that covers the entire screen, including the macOS menu bar
- Adjustable transparency using keyboard shortcuts
- Hide/show overlay using a keyboard shortcut
- Quit the application using a unique keyboard shortcut

## Keyboard Shortcuts

- `Ctrl+Up Arrow` / `Cmd+Up Arrow`: Increase transparency
- `Ctrl+Down Arrow` / `Cmd+Down Arrow`: Decrease transparency
- `Ctrl+H` / `Cmd+H`: Hide/show overlay
- `Ctrl+Shift+Q` / `Cmd+Shift+Q`: Quit the application

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You need to have Node.js and npm installed on your machine. You can download them from [here](https://nodejs.org/).

### Installing

1. Clone the repository
    ```bash
    git clone https://github.com/agentcole/electron-overlay.git
    cd electron-overlay
    ```

2. Install the dependencies
    ```bash
    npm install
    ```

3. Start the application
    ```bash
    npm start
    ```

## Built With

- [Electron](https://electronjs.org/) - Framework for building cross-platform desktop apps with JavaScript, HTML, and CSS
- [TypeScript](https://www.typescriptlang.org/) - Typed JavaScript at Any Scale



## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on the code of conduct, and the process for submitting pull requests.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/agentcole/electron-overlay/tags).

## Authors

- **Agent Cole** - *Initial work* - [agentcole](https://github.com/agentcole)

See also the list of [contributors](https://github.com/agentcole/electron-overlay/contributors) who participated in this project.

## License

This project is licensed under the MIT License.

