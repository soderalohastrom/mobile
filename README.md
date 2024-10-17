# AI Chat Assistant

This is an AI chat assistant project built with Next.js, the Vercel AI SDK, and assistant-ui components.

## Getting Started

First, add your OpenAI API key to `.env.local` file:

```
OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
```

Then, install the dependencies:

```bash
npm install
```

Run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Deploying to Vercel

You can deploy this app to Vercel using either the command line or by connecting a GitHub repository.

### Option 1: Command Line Deployment

1. Install the Vercel CLI:
   ```
   npm install -g vercel
   ```

2. Log in to your Vercel account:
   ```
   vercel login
   ```

3. Deploy the app:
   ```
   vercel
   ```

4. Follow the prompts to configure your project. When asked about environment variables, make sure to add your `OPENAI_API_KEY`.

5. Once deployed, Vercel will provide you with a URL for your live app.

### Option 2: GitHub Repository Deployment

1. Push your code to a GitHub repository.

2. Go to [Vercel](https://vercel.com) and sign up or log in.

3. Click on "New Project" and select your GitHub repository.

4. In the "Configure Project" step:
   - Set the Framework Preset to Next.js
   - Add your `OPENAI_API_KEY` as an environment variable
   - Click "Deploy"

5. Wait for the deployment to complete. Vercel will provide you with a URL for your live app.

With either method, any future pushes to your GitHub repository (if connected) will trigger automatic deployments.

## Learn More

To learn more about Next.js, Vercel AI SDK, and assistant-ui, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs)
- [Vercel AI SDK Documentation](https://sdk.vercel.ai/docs)
- [assistant-ui Documentation](https://www.assistant-ui.com/docs)
- [OpenAI API Documentation](https://platform.openai.com/docs/api-reference)
