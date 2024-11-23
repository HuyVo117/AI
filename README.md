It seems that the repository description and primary language are not available. However, I will proceed with the information you provided and draft the README file based on the installation and usage instructions you shared.

Here is a draft of the README file:

---

# AI-generate-Song

## Installation and Usage Guide

### 1. Installation

Clone the repository to your local machine:
```sh
git clone https://github.com/HuyVo117/AI-genarate-Song
cd AI-genarate-Song
```

Install the dependencies:
```sh
npm install
# or
yarn install
```

Copy the `.env.example` file to `.env` and add your API key for the AI model you want to use (only one model is needed):
```sh
cp .env.example .env
```
Add your API key to the `.env` file:
```sh
OPENAI_API_KEY=sk-xxx
# or
ANTHROPIC_API_KEY=sk-ant-xxx
# or
GOOGLE_API_KEY=xxx
```

You can obtain API Keys from the following sources:
- Google (Free): [https://aistudio.google.com/u/1/apikey](https://aistudio.google.com/u/1/apikey)
- OpenAI: [https://platform.openai.com/api-keys](https://platform.openai.com/api-keys)
- Anthropic: [https://console.anthropic.com/settings/keys](https://console.anthropic.com/settings/keys)

### 2. Running the Development Server

Start the development server:
```sh
npm run dev
# or
yarn dev
```

---

Feel free to review and make any necessary adjustments. If there are specific details about the repository's functionality or additional information you'd like to include, please let me know!
