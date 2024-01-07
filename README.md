# Fork description

Fork of: https://github.com/vincelwt/chatgpt-mac - it wasn't supporting ChatGPT plus subscription, GPT4 and custom GPTs, 
this removes all the custom additions from original plugin and allows to use all ChatGPT plus features.

Not adding a `.dmg` installables, since i do not have apple developer account so i can't produce signed/notarized packages. To package it into app simply run:
```bash
npm install
npm run package
```
And then copy the appropriate `.app` version(can be found in `out` directory) to your `Applications` directory.

All credit goes to @vincelwt.

# Original README below

⭐ Building in AI? My new project is an [open-source toolkit for AI devs](https://github.com/llmonitor/llmonitor), a star would mean the world ⭐

---

# ChatGPT for desktop

This is a simple app that makes ChatGPT live in your menubar.

You can use Cmd+Shift+G (Mac) or Ctrl+Shift+G (Win) to quickly open it from anywhere.

Download:

- [Mac Arm64 .dmg](https://github.com/vincelwt/chatgpt-mac/releases/download/v0.0.5/ChatGPT-0.0.5-arm64.dmg)
- [Mac Intel .dmg](https://github.com/vincelwt/chatgpt-mac/releases/download/v0.0.5/ChatGPT-0.0.5-x64.dmg)

No Windows binaries currently offered. Clone the repo, npm install electron-forge and run.

<p align="center">
  <img src="./images/screenshot.jpeg" width="500">
</p>

## Credit

All credit and copyrights goes to OpenAI.

## Author

You can find me on Twitter [@vincelwt](https://twitter.com/vincelwt).
