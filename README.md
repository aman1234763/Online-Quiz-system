# CS Quiz Application

A modern web application built with React and TypeScript for conducting Computer Science Engineering quizzes. The application features a timed quiz system with instant results and question randomization.


## Features

- 🕒 20-minute timed quizzes
- 🔄 Random selection of 15 questions per quiz
- 📊 Instant result display with detailed feedback
- 🏷️ Questions categorized by CS topics:
  - Algorithms
  - Data Structures
  - Programming
  - Database
  - Networking
  - Operating Systems
  - Software Design
  - Security
- 💫 Beautiful, responsive UI with Tailwind CSS
- 🎯 Progress tracking during quiz
- ⏪ Navigation between questions

## Tech Stack

- React 18
- TypeScript
- Tailwind CSS
- React Router
- Lucide React Icons
- Vite

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```

## Project Structure

```
src/
├── components/         # React components
│   ├── CategoryBadge.tsx
│   ├── Home.tsx
│   ├── Layout.tsx
│   └── Quiz.tsx
├── data/              # Quiz questions and types
│   └── questions.ts
├── App.tsx           # Main application component
└── main.tsx         # Application entry point
```

## Quiz Features

- **Timer**: Each quiz has a 20-minute time limit
- **Question Navigation**: Users can move between questions freely
- **Progress Tracking**: Visual indicator for answered/unanswered questions
- **Categories**: Questions are tagged with relevant CS topics
- **Instant Feedback**: Detailed results showing correct/incorrect answers
- **Responsive Design**: Works on desktop and mobile devices

## Contributing

Feel free to submit issues and enhancement requests!

## License

MIT License
