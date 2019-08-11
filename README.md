<h1 align="center">Welcome to npm-package-scaffolding 👋</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-1.0.0-blue.svg?cacheSeconds=2592000" />
  <a href="https://github.com/h-4vok/npm-package-scaffolding#readme">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" target="_blank" />
  </a>
  <a href="https://github.com/h-4vok/npm-package-scaffolding/graphs/commit-activity">
    <img alt="Maintenance" src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" target="_blank" />
  </a>
  <a href="https://github.com/h-4vok/npm-package-scaffolding/blob/master/LICENSE">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" target="_blank" />
  </a>
</p>

> npm-package-scaffolding is simply an empty repository that you can download and use right away to start developing your npm package. This is obviously opinionated! Read further to understand the decisions made within this scaffolding.

### 🏠 [Homepage](https://github.com/h-4vok/npm-package-scaffolding#readme)

## Install

Simply download this repository as a ZIP instead of cloning. You don't want to use npm-package-scaffolding as a package it self, but rather to be your skeleton for your npm package!

- Remeber that you need to update the package.json metadata to reflect the metadata of your own project!
- Change this README.md of course! I recommend the great readme-md-generator tool (https://www.npmjs.com/package/readme-md-generator) by Franck Abgrall!
- You need to write "npm run all-checks" on the husky precommit hook if you want it to work properly.

Then make this project your own and have fun coding!

## About npm-package-scaffolding

It has only been recently that I started to develop npm package. I had a few incursions in NuGet which were exciting and fun, but at the same time felt like a lot of work for what I tried to do. When I started building my own node packages I could not believe how EASY it was to interface with npmjs. However, as everyone knows, setting up a project in C# is a couple of clicks while here it's more like a craft!

I decided that there was a set of tools, practices and things I always wanted to have by default, and then I would build on top of it. So I decided to create npm-package-scaffolding which you can download or fork from github at anytime!

This is a JavaScript based scaffolding with Babel as transpiler.

## My choices

- ESLint for linting is a must for me. ESLint allows you to build a DOCUMENT with rules which make up your coding standard. This is a coding standard you can EXECUTE. The best kind of documentation.
- JEST for unit testing. This is a no-brainer. I am a big fan of JEST and how easy it made unit testing on javascript. If you have another tool of choice, feel free to fork this repo and change it to your liking!
- Code Coverage with JEST at 100%. If I am building a package that will be hosted on npmjs for everyone to download then I want to make sure that it is tested at 100%. Exclusions can be made as long as it makes sense. Besides, unit testing drives design for me. While not a TDD practitioner in any way, I am a TDD enthusiast and try to apply it when possible.
- Prettier and Pretty-Quick. This is by far one of my favorite tools. By being so heavily opinionated you no longer require discussions on how to format code. Between Prettier and ESLint your coding standard and formatting is assured. Now focus on writing readable code.
- Babel. This is a JavaScript project scaffolding. For small projects like small npm packages plain JavaScript makes a whole sense to me. Other people might choose TS over JS. Guess we need another scaffolding github project for that :). I will build my own if I get to the point I want to build a package on TS.
- Husky for precommit hooks. I added husky to save myself whenever I commit code. We can be excellent professionals, but we are not excellent RAM memories.
- Prepublish checks. If you run npm publish then the prepublish script will run, saving you from yourself again.
- Finally, we got an .editorconfig file. Install editorconfig on your IDE and get the best from both EditorConfig and Prettier. I have configured them both and ESLint to ensure they work gracefully together.

## Author

👤 **Christian Guzmán**

- Github: [@h-4vok](https://github.com/h-4vok)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/h-4vok/npm-package-scaffolding/issues).

## Show your support

Give a ⭐️ if this project helped you!

## 📝 License

Copyright © 2019 [Christian Guzmán](https://github.com/h-4vok).<br />
This project is [MIT](https://github.com/h-4vok/npm-package-scaffolding/blob/master/LICENSE) licensed.

---

_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_
