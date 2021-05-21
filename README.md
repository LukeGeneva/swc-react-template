# SWC React Template

A template for quickly getting a React project up and running using the SWC compiler.

## Installing

Please refer to the [installation](https://swc-project.github.io/docs/installation) section of the SWC project [website](https://swc-project.github.io). It contains appropriate installation instructions based on the operating system you are using.

## Getting Started

Start by cloning this repository.

```bash
git clone https://github.com/LukeGeneva/swc-react-template.git <your-project-path>
cd <your-project-path>
```

Remove the `.git` directory and then initialize your own.

```bash
rm -rf .git
git init
```

You can alter the `package.json` file to suit your needs. This may be as simple as running:

```bash
npm init
```

Install packages

```bash
npm install
```

The template uses [webpack](https://webpack.js.org/) and comes packaged with `webpack-dev-server`. You can start the dev server by running:

```bash
npm start
```

## Contributing

PRs welcome! :smiley:

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
