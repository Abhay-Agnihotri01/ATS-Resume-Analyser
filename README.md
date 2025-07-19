# Resumind - AI Resume Analyzer

![Resumind](./public/readme/hero.webp)

Resumind is an AI-powered resume analyzer that helps job seekers optimize their resumes for Applicant Tracking Systems (ATS) and improve their chances of landing interviews. The application provides detailed feedback on various aspects of your resume, including ATS compatibility, content quality, structure, tone, and skills alignment with job descriptions.

## Features

- **Resume Analysis**: Upload your resume and get comprehensive AI-powered feedback
- **ATS Compatibility Check**: Determine how well your resume will perform in Applicant Tracking Systems
- **Job-Specific Optimization**: Tailor your resume analysis to specific job descriptions
- **Detailed Scoring**: Get scores for overall resume quality, ATS compatibility, content, structure, tone & style, and skills
- **Actionable Feedback**: Receive specific tips and suggestions to improve your resume
- **Resume Tracking**: Save and track multiple resume versions and their scores
- **PDF Visualization**: View your resume as both PDF and image formats

## Tech Stack

- **Frontend**: React 19 with TypeScript
- **Routing**: React Router 7
- **State Management**: Zustand
- **Styling**: TailwindCSS 4
- **PDF Processing**: PDF.js
- **File Handling**: React Dropzone
- **Authentication & Storage**: Puter.js for user authentication and file storage
- **AI Integration**: Claude 3.7 Sonnet model for resume analysis

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ai-resume-analyzer.git
   cd ai-resume-analyzer
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn
   ```

3. Start the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. Open your browser and navigate to `http://localhost:3000`

### Building for Production

```bash
npm run build
# or
yarn build
```

To start the production server:

```bash
npm run start
# or
yarn start
```

## How It Works

1. **Sign In**: Create an account or sign in to access the application
2. **Upload Resume**: Upload your resume in PDF format
3. **Enter Job Details**: Provide the company name, job title, and job description
4. **Get Analysis**: The AI analyzes your resume against the job description
5. **Review Feedback**: Get detailed scores and actionable suggestions
6. **Track Progress**: Save multiple versions of your resume and track improvements

## Project Structure

```
ai-resume-analyzer/
├── app/
│   ├── components/       # UI components
│   ├── lib/              # Utility functions
│   ├── routes/           # Application routes
│   ├── app.css           # Global styles
│   ├── root.tsx          # Root component
│   └── routes.ts         # Route definitions
├── constants/            # Application constants
├── public/               # Static assets
├── types/                # TypeScript type definitions
└── ...                   # Configuration files
```

## Key Components

- **FileUploader**: Handles PDF resume uploads
- **ATS**: Displays ATS compatibility score and suggestions
- **Summary**: Shows overall resume scores
- **Details**: Provides detailed feedback on different resume aspects
- **ResumeCard**: Displays saved resumes on the dashboard

## Authentication and Storage

The application uses Puter.js for:
- User authentication
- File storage (resume PDFs and images)
- Key-value storage for user data
- AI integration for resume analysis

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- PDF.js for PDF processing
- Claude AI for resume analysis
- React Router for navigation
- TailwindCSS for styling