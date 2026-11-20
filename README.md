<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:22d3ee&height=180&section=header&text=json-pointer-playground&fontSize=42&fontColor=ffffff&animation=fadeIn" alt="JSON Pointer Playground banner" width="100%"/>

<a href="https://github.com/CyberLoop-dev/json-pointer-playground">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1100&color=22d3ee&center=true&vCenter=true&width=720&lines=JSON%20Pointer%20Playground;Small+tools.+Clear+feedback.+Local+first." alt="Typing title"/>
</a>

<p><strong>Resolve RFC 6901 JSON Pointer expressions against sample JSON documents in a local browser tool.</strong></p>

[![License](https://img.shields.io/github/license/CyberLoop-dev/json-pointer-playground)](LICENSE)
[![Language](https://img.shields.io/github/languages/top/CyberLoop-dev/json-pointer-playground)](https://github.com/CyberLoop-dev/json-pointer-playground)
[![Stars](https://img.shields.io/github/stars/CyberLoop-dev/json-pointer-playground?style=flat)](https://github.com/CyberLoop-dev/json-pointer-playground/stargazers)
[![Last commit](https://img.shields.io/github/last-commit/CyberLoop-dev/json-pointer-playground)](https://github.com/CyberLoop-dev/json-pointer-playground/commits/main)

<img src="assets/overview.svg" alt="JSON Pointer Playground project illustration" width="100%"/>

</div>

## ✨ Overview

Resolve RFC 6901 JSON Pointer expressions against sample JSON documents in a local browser tool. **JSON Pointer Playground** is a small, focused Node.js and browser JavaScript project. It runs locally, keeps user data in the browser, and is designed to be easy to inspect and extend.

## 🚀 Features

- ✨ 🧭 Resolve pointers against JSON objects and arrays.
- ✨ 🔤 Decode the `~1` and `~0` escape sequences.
- ✨ 🛑 Report invalid escapes, missing keys, and invalid array indexes.
- ✨ 🔒 Keep the JSON document in the local browser tab.

## 🖥️ Demo

Run `npm start`, open `http://127.0.0.1:4173`, and use the controls in the page. Try `/user/roles/1` or `/a~1b/~0key` to test array access and escaped tokens.

## ⚡ Quick Start

```bash
npm start
```

No third-party npm packages are required.

## 🧰 Tech Stack

- **Runtime:** Node.js (built-in HTTP server)
- **Frontend:** HTML, CSS, browser JavaScript
- **Dependencies:** None

## 📁 Folder Structure

```text
json-pointer-playground/
├── assets/overview.svg
├── public/index.html
├── server.js
├── package.json
├── .gitignore
├── LICENSE
└── README.md
```

## 🗺️ Roadmap

- [ ] Add pointer generation from a selected JSON value.
- [ ] Add a small RFC 6901 conformance fixture set.

## 🤝 Contributing

Issues and pull requests are welcome. Keep changes focused, explain behavior changes, and include reproducible steps for reported bugs.

## 📄 License

Released under the [MIT License](LICENSE).

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:22d3ee,100:0f172a&height=110&section=footer" alt="Animated wave footer" width="100%"/>
</div>
