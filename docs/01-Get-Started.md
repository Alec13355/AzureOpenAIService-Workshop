---
title: Get started
slug: /setup
---

:::info WORKSHOP PRE-REQUISITES
 - **Use your own laptop**. 
 - **Launch a modern browser**. (Use edge or chrome for the best experience)
:::

For this workshop you are using a custom playground build on-top of the Azure OpenAI Service. In this playground you will 
have the oppertunity to play with the prompts and learn how to interact with OpenAI Models.


## Authenticate

Your workshop instructor will provide you with an **event key** that you can use to get your personal **access key**

Setup is now a quick 3-step process. 

1. 📬 | **Get your access-key** - enter event key in [**this form**](https://black-tree-00bc45010.5.azurestaticapps.net/event/3214-b26c) to receive your access-key.
2. 💬 | **Use the access-key** - visit the [**AI Playground**](https://black-tree-00bc45010.5.azurestaticapps.net), enter access-key at top right, and click `Authorize`. 

![AI Tour Playground](./images/aitour-playground-chat.png) 


## Explore
On successful login, the playground application should update to show a `Logout` button at top-right, as shown below. To validate your setup, enter a query in the user prompt input box (region 2) and click `Send`. You should get a conversational response in the chat session are (region 3) as shown below.

Let's take a minute to familiarize ourselves with the different regions of this app.

![](./images/aitour-playground-regions.png)

- Region 1️⃣ | Once authorized, shows the event profile.
- Region 2️⃣ | User prompt - used to enter text questions for AI
- Region 3️⃣ | Conversation - interleaved user questions & assistant responses
- Region 4️⃣ | Configuration - tunable parameters, execution stats
- Region 5️⃣ | System message - sets assistant persona, base context
- Region 6️⃣ | Function calling - save custom functions to set context
- Region 7️⃣ | Image generation - access the DALL-E model playground 


## Tips

### 1. Clear Chat Sessions

The output of the model is influenced by the contents of the chat session. To ensure that the output of the model is not influenced by previous prompts, click the "Clear Chat" button **before entering each new prompt**.

### 2. Copy-Paste Snippets

In a prompt-based exercise, you will find the prompt input is  provided to you in a _code-fenced_ snippet as shown below. When viewing this page in a browser, _click_ within the code-fenced region below to see a `copy` icon appear at the right. Click it to copy the prompt into your clipboard - then paste using <kbd>Ctrl-V</kbd> (or equivalent) command into the text input region in Playground.

```text
This is the prompt text you need to enter into the chat prompt input field.
```