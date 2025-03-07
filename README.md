# Iris.ai

## Screenshots
![Screenshot 2025-03-07 082659](https://github.com/user-attachments/assets/ed226721-5350-49c6-a908-cc8445c8938f)


![Screenshot 2025-03-07 084526](https://github.com/user-attachments/assets/2c10d0b2-f5bd-494f-9e1d-0147fe44437b)


## Overview

IRIS is an intelligent meeting assistant that helps capture, analyze, and act on meetings. It provides automatic transcription, AI-powered analysis, and task management capabilities.

## Features

- Meeting Recording & Transcription
- AI-Powered Meeting Analysis
- Automated Task Extraction
- Meeting Insights & Summaries
- Task Management Integration
- Dark/Light Mode Support

## Tech Stack

- Next.js 14 (App Router)
- TypeScript
- Tailwind CSS
- Shadcn/ui Components
- Clerk Authentication
- Local Storage for Data Management
- OpenAI Whisper for Transcription
- Ollama (LLaMA 3.2) for AI Analysis

## Frameworks & Authentication

### Next.js
Next.js is a React-based framework that provides server-side rendering, static site generation, and optimized performance. It enables fast development with built-in API routes and seamless integration with modern frontend technologies.

### Clerk Authentication
Clerk is used for authentication, providing secure user management, multi-factor authentication, and session handling. It simplifies authentication flows and integrates with various identity providers.

## AI Model Integration

### Whisper (Speech Recognition)
Whisper is used for real-time and post-meeting transcription. It provides accurate speech-to-text conversion, supports multiple languages, and can distinguish between different speakers.

### Ollama (LLaMA 3.2 - AI Analysis)
Ollama runs LLaMA 3.2 locally on the computer, enabling fast and private AI processing without reliance on external servers. This model extracts key insights, generates summaries, and identifies action items from meeting transcripts.

To run LLaMA 3.2 locally, execute the following command in the terminal:

```bash
ollama run llama3.2
```

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/yourusername/iris.git
cd iris
```

2. Install dependencies:

```bash
npm install
```

3. Set up environment variables:

Create a `.env.local` file in the root directory and add:

```env
OPENAI_API_KEY=your_openai_api_key
NEXT_WHISPER_API_KEY=your_whisper_api_key
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
```

4. Run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to access the application.

## Environment Variables

The following environment variables are required:

- `OPENAI_API_KEY`: API key for OpenAI-based transcription and analysis
- `NEXT_WHISPER_API_KEY`: API key for Whisper speech-to-text processing
- `NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY`: Clerk publishable key
- `CLERK_SECRET_KEY`: Clerk secret key

## Contributing

Contributions are welcome. Please feel free to submit a pull request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Learn More

To learn more about Next.js, check out the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - Learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - Interactive Next.js tutorial.

You can also check out [the Next.js GitHub repository](https://github.com/vercel/next.js) for further contributions and feedback.

## Deploy on Vercel

The easiest way to deploy this Next.js application is via the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=cre
