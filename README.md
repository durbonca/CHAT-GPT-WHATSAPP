# chat-gpt-whatsapp

<img src="https://upload.wikimedia.org/wikipedia/commons/1/13/WhatsApp.png"  width="100"><img src="https://upload.wikimedia.org/wikipedia/commons/f/fe/ChatGPT_logo.png"  width="55">

This project allows you to automate WhatsApp messaging using a headless Chrome browser instance. It uses the WhatsApp web interface to interact with the messaging service, allowing you to send and receive messages.

Integrating [ChatGPT](https://chat.openai.com) with [whatsapp-web.js](https://wwebjs.dev) would allow you to add an AI-powered chatbot to your WhatsApp automation. ChatGPT is a large language model trained on vast amounts of text data, and it can generate natural language responses to a wide range of user queries.

By combining these two tools, you could create a web app that enables users to interact with your business or organization via WhatsApp. For example, a customer service chatbot that uses ChatGPT could answer frequently asked questions, provide personalized recommendations, and help users troubleshoot issues. whatsapp-web.js would handle the actual messaging, while ChatGPT would provide the intelligent responses.

Overall, this integration has the potential to enhance your WhatsApp automation capabilities and provide a more engaging and helpful user experience for your customers.

## Installation

#### Frontend

```bash
$ cd frontend/
$ npm i
```

#### Backend

```bash
$ cd frontend/
$ npm i
```

*note: you will required to add .env OPENAI_API_KEY, you can get it from [here](https://platform.openai.com/)*

## Usage

[describe a simple use of the thingie that you are pitching. keep it short]

```js
const thingie = createThingie(config);
```

### Parameters

[describe what parameters your package/function takes]

| Parameter | Description                                |
| :-------- | :----------------------------------------- |
| `foo`     | A foo thingie (boolean). Default = `true`. |
| `bar`     | A bar thingie (string). Default = `bar`.   |

### Return

[describe what is returned]

| Key    | Description                                     |
| :----- | :---------------------------------------------- |
| `blah` | A boolean containing the current value of blah. |

## Example

[Write something here describing the sample code below. The example code SHOULD WORK!]

```jsx
import React from 'react';
import { createThingie } from 'chat-gpt-whatsapp-backend';

const Thingie = createThingie();

const MyThingie = () => {
  // Do some stuff

  return <Thingie>Return some JSX</Thingie>;
};

export default MyThingie;
```

## Live demo

You can view/edit the chat-gpt-whatsapp-backend demo app on CodeSandbox.

[![Edit demo app on CodeSandbox](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/s/github/donavon/use-step-multi-step-form-demo/tree/master/?module=%2Fsrc%2FDarkModeToggle.jsx)

## License

**[MIT](LICENSE)** Licensed

---

[creator contact](https://durbonca.com)
<span style="display: flex; align-items: center">
<a href="https://github.com/durbonca">
<img src="https://upload.wikimedia.org/wikipedia/commons/4/4a/GitHub_Mark.png" width="30">
</a><a href="https://twitter.com/durbonca">
<img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/Twitter_Logo_Blue.png" width="50">
</a>
</span>