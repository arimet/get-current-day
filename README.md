
# 📅 get-today

[![Daily Version Update](https://img.shields.io/badge/version-daily-blue.svg)](https://www.npmjs.com/package/get-today)

A completely useless NPM package that does just one thing: returns today's date.  
It gets a **new version every single day**, because... why not? 🤷‍♂️  

## 🚀 Installation

```sh
npm install get-today
```

or  

```sh
yarn add get-today
```

## 📌 Usage

```js
const today = require("get-today");

console.log(today()); // "YYYY-MM-DD"
```

That's it. Nothing more, nothing less.

## 🔄 Automatic Daily Updates

Every day, a GitHub Action updates the package version to match the current date (`YYYY.MM.DD`).  
If you want to stay up-to-date with **the latest version of today**, just keep updating the package daily:

```sh
npm update get-today
```

## 🎉 Why does this exist?
- Because we can.
- Because daily package updates are fun.
- Because **"what even is time?"**  

## 🤝 Contributing
Feel free to open an issue or a pull request... but honestly, there's nothing to improve here. 😆  

## 📝 License
MIT License. Use it however you like, but don't expect it to be useful.  

## 🧑‍💻 Author
- [Anthony RIMET](https://github.com/arimet)