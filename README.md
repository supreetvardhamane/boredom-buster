# 🎯 Boredom Buster

A simple Node.js + Express web app that suggests random activities when you're bored.
Users can filter activities by **type** and **number of participants** using the Bored API.

Built while learning **APIs, Express, and server-side rendering with EJS**.


## 🚀 Features

* 🎲 Generate a **random activity**
* 🎯 Filter activities by **type**
* 👥 Filter by **number of participants**
* 🔁 Random selection from API results
* ⚠️ Graceful error handling if no activities match the criteria


## 🛠️ Tech Stack

* **Node.js**
* **Express.js**
* **Axios**
* **EJS (Embedded JavaScript Templates)**
* **HTML + CSS**

API used:

* https://bored-api.appbrewery.com

## 📂 Project Structure

```
boredom-buster
│
├── public/
│   └── styles/
│       └── main.css
│
├── views/
│   └── index.ejs
│
├── index.js
├── package.json
└── README.md
```

## ⚙️ Installation

Clone the repo:

```bash
git clone https://github.com/supreetvardhamane/boredom-buster.git
```

Install dependencies:

```bash
npm install
```

Run the server:

```bash
node index.js
```

Open in browser:

```
http://localhost:3000
```
## 🧠 What I Learned

Building this project helped me understand:

* How **Express servers work**
* Making **HTTP requests using Axios**
* Consuming **REST APIs**
* Using **EJS for server-side rendering**
* Handling **form data with body-parser**
* Working with **query parameters in APIs**
* Implementing **error handling for API failures**
* Structuring a simple **Node.js web application**
