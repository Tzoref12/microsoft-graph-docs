---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const chatMessage = {
  body: {
     content: 'Hello world'
  }
};

await client.api('/chats/19:2da4c29f6d7041eca70b638b43d45437@thread.v2/messages')
	.post(chatMessage);

```