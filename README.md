
# AIBIZ - SMART Goals Helper App

## Hackathon info

1. Team name: AIBIZ
2. Project name: SMART Goals Helper App
3. https://smart-goals-assistant.vercel.app/
4. [Project presentation](./AIBIZ_SMART_Goals_Helper.pdf)
5. [Project DEMO video](https://disk.yandex.ru/d/YQ00d2Dyp5ZblA)
6. **All code development was provided by team during hackathon time**

# Documentation

## SMART Goals Helper Application

A web application that helps users transform their questions into SMART goals (Specific, Measurable, Achievable, Relevant, Time-bound).

[Try out our DEMO](https://smart-goals-assistant.vercel.app/)

## Features

- Converts user input into SMART goal format
- Provides top 5 SMART goal suggestions
- Analyzes missing SMART components in user's initial question
- Dark theme and mobile-first design
- Real-time chat interface

## Technology Stack

- Next.js 14
- TypeScript
- Redux Toolkit
- SCSS Modules
- OpenAI GPT-4o-mini
- Mobile-first responsive design

## Getting Started

**Install Node.js and npm**:

- Download and install Node.js from the [official website](https://nodejs.org/). npm is included with Node.js, so you will have both installed.
- To verify the installation, run the following commands in your terminal:
  ```bash
  node -v
  npm -v
  ```

1. Clone the repository

   ```bash
   git clone https://github.com/HGreender/AIBIZ.git
   ```

   Then move to `frontend` folder

   ```
   cd AIBIZ/frontend
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory and add your OpenAI API key:

   ```
   OPENAI_API_KEY=your_api_key_here
   ```

4. Run the development server:
   ```bash
   npm run dev
   ```
5. Open [http://localhost:3012](http://localhost:3012) in your browser

## Environment Variables

- `OPENAI_API_KEY`: Your OpenAI API key

## FAQ

> 403 error (or 400-499)

- Check your API key balance and date expired. Then enter full api key in input placeholder and click 'Save Key'. Don't forget to reload (`F5 or command+R`) the page <br>

If you run project locally, then stop it, check your `.env` and type valid API key. Then run the project again

```bash
 npm run dev
```

> 500 error (any 5xx)

- waiting while OpenAi team fix errors

<!-- upd env -->
