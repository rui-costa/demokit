# DemoKit for Team Kappa

## 🧰 How to Use

### I have a room code and password
If you are either a presenter or someone sharing the presentation, now that you have a `Room Code` and `Password`, just open the following files.
- For Sharing the Screen `index.html`
- For joining a presentation session `invite.html`

### I Don't have a room code and password
If you want to generate a `Room Code` and `Password` for your team: 
- open the invitation link `invite.html`
- accept the auto generated `Room Code` and `Password`, or add one of your own
- share the `Room Code` and `Password` with your team
If you are the one sharing your screen, you can now open the Screen Sharing link `index.html` and add the `Room Code` and `Password`.
If you forgot your `Room Code` or `Password`, just click on the `🔐` icon on the right top corner.

## For presentation

### 🌐 I need to run a Webserver
There may be the need to serve the `index.html` as a website and not as a file(`file:\\` ) in your computer.
For those cases, you can serve it using the lite webserver in node.js. 
Follow the steps:
- Make sure you have node installed `node --version`. If you don't, go to the official [website](https://nodejs.org/en/) and follow the instructions.
- run `npm install`
- run `npm start`
- if the webpage doesn't open, go to `http://localhost:1337`

### 🖼 I want a Frameless Chrome window
If you want to run a frameless window in chrome, use the `presenter.sh` script