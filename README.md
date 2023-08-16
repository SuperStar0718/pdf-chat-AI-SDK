# PDF-CHAT AI ✨🤖💻🗃️

An AI-powered PDF chat built with Next.js 13, Vercel's AI SDK, Langchain, and PineconeDB

## 👷🏾‍♂️ Want to Learn How to Build It?
Subscribe to my [YouTube Channel](https://www.youtube.com/channel/UCU2xH1a0ExxWXC4zk1VF_Eg) for an upcoming video tutorial!






https://github.com/rajeshdavidbabu/pdf-chat-ai-sdk/assets/15684795/6e97864c-ea2f-4a1b-991f-21e6c34f1214





## Architecture
<img width="1275" alt="Screenshot 2023-08-14 at 12 11 05" src="https://github.com/rajeshdavidbabu/pdf-chat-ai/assets/15684795/a2142d39-ec97-410f-89dc-907e25524fad">


## 👩‍🚀 Description

Built with:
- ✅ Next.js 13
- ✅ Shadcn-ui
- ✅ Langchain TypeScript integration
- ✅ PineconeDB as the knowledge store
- ✅ Dark Mode with persistent theme-switching

## 🗃️ Pre-requisites
- Create a free account and get an OPEN_AI key from platform.openai.com
- Create a free account and get access to PineconeDB
- And populate your `.env` file with the required information.

## 💬 Good to know
- The PineconeDB index creation happens when we run `npm run prepare:data`, but its better to create it manually if you dont want the command to fail.
- If the command fails, then give sometime for pinecone index to get initialized and try to run the command again, it should work eventually.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command               | Action                                          |
| :-------------------- | :-----------------------------------------------|
| `npm install`         | Installs dependencies                           |
| `npm run prepare:data`| Splits your PDF file under the /docs folder into chunks, embeds them, uploads them to Pinecone|
| `npm run dev`         | Starts the local dev server at `localhost:3000` |

## 🚸 Roadmap
- ✅ Add sources to the streamed chat bubble
- 🚧 Clean up and show proper error messages
- 🚧 Sanitize input and output source documents

## 👏🏽 Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.
