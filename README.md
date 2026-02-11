# FINSIGHT DA1

A modern financial analysis web application built with React and Firebase authentication.

## Features

- **User Authentication**: Secure Firebase-based authentication system
- **Financial Dashboard**: Comprehensive financial data visualization and analysis
- **Document Processing**: Upload and process financial documents
- **Interactive Charts**: Dynamic charts for financial ratios and accounting data
- **Responsive Design**: Modern UI built with Tailwind CSS and React

## Tech Stack

- **Frontend**: React 19, Vite
- **Styling**: Tailwind CSS
- **Authentication**: Firebase
- **Icons**: Lucide React, React Icons
- **Charts**: Recharts
- **Routing**: React Router DOM

## Getting Started

### Prerequisites

- Node.js 18+
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/310511/FINSIGHT_DA1.git
cd FINSIGHT_DA1
```

2. Install dependencies:
```bash
npm install
```

3. Set up Firebase:
   - Create a Firebase project at https://console.firebase.google.com
   - Enable Authentication
   - Get your Firebase configuration
   - Create a `.env` file in the root directory with your Firebase config

4. Start the development server:
```bash
npm run dev
```

### Environment Variables

Create a `.env` file in the root directory:

```
VITE_FIREBASE_API_KEY=your_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_storage_bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
VITE_FIREBASE_APP_ID=your_app_id
```

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run lint` - Run ESLint
- `npm run preview` - Preview production build

## Project Structure

```
src/
├── components/          # Reusable React components
│   ├── Charts/         # Financial chart components
│   ├── Dashboard/      # Dashboard-related components
│   ├── home/           # Homepage components
│   └── ui/             # UI components
├── firebase/           # Firebase configuration and auth
├── pages/              # Page components
├── services/           # API services
└── utils/              # Utility functions
```

## Deployment

This project is configured for deployment on Netlify. The build process creates a static site that can be deployed to any static hosting service.

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Commit and push the changes
5. Create a pull request

## License

This project is licensed under the MIT License.
