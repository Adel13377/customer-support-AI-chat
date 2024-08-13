# LinkedOut AI Customer Support Chatbot


This is an AI-powered customer support chatbot project built using [Next.js](https://nextjs.org/), [React](https://reactjs.org/), and the [GroqAI API](https://console.groq.com/docs/quickstart). The project was developed as part of the Headstarter AI Fellowship, where we aimed to create a responsive and intelligent chatbot capable of assisting users in real-time.

## Project Overview
The application was deployed using AWS EC2 servers  
Here is the [Live link](http://18.229.164.174/)

## Project Overview

The chatbot was designed to provide efficient customer support by handling queries intelligently. We achieved up to **3 Levels** of the project requirements, which included:

- **Level 1:** Creating a basic chatbot with hard-coded responses.
- **Level 2:** Integrating a Gen-AI model to respond intelligently to user inputs.
- **Level 3:** Deploying the web app to AWS EC2 servers for real-world application.

## Getting Started

To get started with the project locally, follow these steps:

### Prerequisites

Ensure you have Node.js installed on your machine. You can download it from [here](https://nodejs.org/).

### Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/customer-support-AI-chat.git
```

2. Navigate to the project directory:
```bash
cd customer-support-AI-chat
```
3. Install the dependencies:
```bash
npm install
```
4. Add your GROQ API key [see below](#environment-variables) <br><br>
5. Start the development server:
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

6. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.


### Environment Variables

To run this project, you will need to add your GROQ API key to a `.env` file in the root directory of the project.

#### Steps to Add Your API Key

1- Create a `.env` file in the root directory of your project:
2- Open the .env file and add your GROQ API key like this:
```bash
GROQ_API_KEY=your-api-key-here
```
Replace your-api-key-here with your actual GROQ API key.

3- Save the file.




## Features

- **Next.js & React:** Frontend framework and library for building the chatbot interface.
- **GroqAI API:** Integrated for generating intelligent responses.
- **AWS EC2:** Final deployment environment ensuring the app is accessible online.

## Team

This project was developed as a collaborative effort with the following team members:

- [**Bushrah Zulfiqar**](https://github.com/Bushrahhh)
- [**Brian Ho**](https://github.com/brianforwork)
- **Quang Le**

## Acknowledgments

Special thanks to Bill Zhang for his guidance and resources that helped steer this project to success.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
