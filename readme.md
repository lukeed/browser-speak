# browser-speak [![Build Status](https://travis-ci.org/lukeed/browser-speak.svg?branch=master)](https://travis-ci.org/lukeed/browser-speak)

> Simple text-to-speech function in supported browsers

---
<p align="center"><b>:warning: Experimental Technology :warning:</b></p>
<p align="center">Very limited browser support. Please check the <a href="https://developer.mozilla.org/en-US/docs/Web/API/SpeechSynthesisUtterance" target="_blank">compatability table</a> for info.</p>
---

## Install

```
$ npm install --save browser-speak
```


## Usage

```js
const speak = require('browser-speak');

speak('unicorns');
//=> :speaker: "unicorns"

speak('another voice', 8);
//=> :speaker: "another voice"
```


## API

### speak(msg, idx)

#### msg

Type: `string`

The message to be said.

#### idx

Type: `integer`<br>
Default: `0`

The [voice index](https://developer.mozilla.org/en-US/docs/Web/API/SpeechSynthesis/getVoices) to speak with.


## License

MIT © [Luke Edwards](https://lukeed.com)
