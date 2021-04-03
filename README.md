# Tari GSoC overview

- [x] `contentScript.js` listens for messages from `background.js`
- [ ] `contentScript.js` inside the listener function **creates a synthetic event** with message from background.
- [ ] `contentScript.js` emits the created event on `document`.
- [ ] React app listens for this event and receives the message from the background.
- [ ] `background` sends actual data we need to use.
- [ ] React through contentScripts event gets the message eventually and creats the elements from data.
