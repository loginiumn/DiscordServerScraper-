## **How to get your user token**


#### **1: Browser Developer Tools** 
- Open Discord in your browser
- Press `F12` to open Developer Tools
- Go to **Application** → **Local Storage** → `https://discord.com`
- Find the `token` key and copy its value (without quotes)

#### **2: Kiwi Browser Extension**
- Install Kiwi Browser (Android) or similar mobile browser
- Use Discord Web in the browser
- Install a Local Storage viewer extension
- Navigate to Discord.com and extract token from Local Storage

#### **3: JavaScript Console**
- Log into Discord in your browser
- Press `F12` and go to **Console** tab
- Paste and run this code:
```javascript
let m;webpackChunkdiscord_app.push([[Math.random()],{},e=>{for(let i in e.c){let x=e.c[i];if(x?.exports?.$8&&x.exports.LP&&x.exports.gK){m=x;break}}}]);m&&console.log("Token:",m.exports.LP());
