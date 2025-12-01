# AI-Recruiter

## Overview

AI-Recruiter is an intelligent recruitment platform powered by artificial intelligence, designed for efficient candidate screening, matching, and recruitment workflow automation. The platform leverages advanced AI algorithms to streamline the hiring process and improve decision-making for HR teams.

## Features

- **AI-Powered Candidate Screening**: Automatically filter and rank candidates based on job requirements
- **Intelligent Matching**: Match candidates with suitable job positions using machine learning algorithms
- **Resume Analysis**: Extract key information from resumes and analyze candidate qualifications
- **Interview Insights**: Generate interview suggestions and candidate evaluation reports
- **Real-time Analytics**: Dashboard with recruitment metrics and performance insights
- **User-Friendly Interface**: Intuitive web application for seamless user experience

## Tech Stack

- **Frontend**: Next.js 14+, React, TypeScript, Tailwind CSS
- **Backend**: Node.js, Next.js API Routes
- **Database**: Firebase Firestore (or configurable)
- **AI/ML**: Integration with AI APIs for NLP and candidate analysis
- **Deployment**: Vercel for frontend, Firebase for backend services
- **Tools**: Gemini AI, Firebase Studio

## Project Structure

```
ai-recruiter/
├── app/                 # Next.js app directory
├── public/              # Static assets
├── components/          # Reusable React components
├── pages/              # API routes and pages
├── styles/             # CSS and styling
├── utils/              # Utility functions
├── package.json        # Project dependencies
├── next.config.ts      # Next.js configuration
├── tsconfig.json       # TypeScript configuration
└── README.md           # Project documentation
```

## Getting Started

### Prerequisites
- Node.js 18+ 
- npm or yarn
- Git
- Firebase account (for backend services)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/kunal2004-dotcom/ai-recruiter.git
   cd ai-recruiter
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env.local
   # Update .env.local with your Firebase credentials and API keys
   ```

4. **Run the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

5. **Open your browser**
   Navigate to `http://localhost:3000` to see the application

## Development

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint for code quality
- `npm run type-check` - Run TypeScript type checking

## Environment Variables

Create a `.env.local` file in the root directory with the following variables:

```
NEXT_PUBLIC_FIREBASE_API_KEY=your_api_key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_auth_domain
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_storage_bucket
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id
GEMINI_API_KEY=your_gemini_api_key
```

## Deployment

### Deploy to Vercel

1. Push your code to GitHub
2. Connect your GitHub repository to Vercel
3. Configure environment variables in Vercel dashboard
4. Deploy automatically on push to main branch

```bash
npm run build
npm start
```

## Usage

1. **Sign Up/Login**: Create an account or login to the platform
2. **Upload Job Descriptions**: Add open positions and requirements
3. **Upload Resumes**: Upload candidate resumes in PDF or Word format
4. **AI Screening**: Let the AI analyze and screen candidates
5. **Review Results**: View matched candidates and detailed reports
6. **Schedule Interviews**: Coordinate with candidates for interviews
7. **Track Progress**: Monitor recruitment pipeline and metrics

## API Endpoints

The application provides REST API endpoints for:
- Candidate management
- Job posting management
- Resume analysis
- Screening results
- User authentication

Refer to API documentation for detailed endpoint specifications.

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

## Performance Optimizations

- Image optimization using Next.js Image component
- Code splitting and lazy loading
- Database query optimization
- Caching strategies for API responses
- Production build optimizations

## Troubleshooting

### Issue: Firebase connection errors
- Ensure `.env.local` has correct Firebase credentials
- Check Firebase project settings and API key restrictions

### Issue: AI API failures
- Verify Gemini API key is valid and has sufficient quota
- Check API rate limits and usage

### Issue: Build errors
- Clear `.next` directory: `rm -rf .next`
- Reinstall dependencies: `rm -rf node_modules && npm install`

## License

MIT License - feel free to use this project for personal or commercial purposes.

## Contact & Support

- **Email**: kunalbagad2004@gmail.com
- **LinkedIn**: [Kunal Bagad](https://www.linkedin.com/in/kunal-bagad)
- **GitHub**: [kunal2004-dotcom](https://github.com/kunal2004-dotcom)

## Acknowledgments

- Built with Next.js, React, and TypeScript
- AI capabilities powered by Gemini API
- Hosted on Vercel and Firebase
- Firebase Studio for rapid development

---

**Last Updated**: December 2025
**Status**: Active Development
