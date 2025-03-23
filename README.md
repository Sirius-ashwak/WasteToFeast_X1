# Waste to Feast

An AI-powered recipe generator that helps reduce food waste by suggesting recipes based on available ingredients.

## Local Setup

1. Clone the repository:
```bash
git clone https://github.com/Sirius-ashwak/WasteToFeast_X1.git
cd WasteToFeast_X1
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory and add your Gemini API key:
```
VITE_GEMINI_API_KEY=your_api_key_here
```

4. Start the development server:
```bash
npm run dev
```

## Deployment on Render (Static Site)

1. Fork this repository to your GitHub account

2. Create a new Static Site on Render:
   - Connect your GitHub repository
   - Select the main branch
   - Fill in the following settings:
     - Name: WasteToFeast_X1
     - Build Command: `npm install && npm run build`
     - Publish Directory: `dist`

3. Add Environment Variable:
   - Key: `VITE_GEMINI_API_KEY`
   - Value: Your Gemini API key

4. Click "Create Static Site"

## Technologies Used
- React
- TypeScript
- Vite
- Google Gemini AI
- Tailwind CSS
- Framer Motion

## Environment Variables
Make sure to set these environment variables:
- `VITE_GEMINI_API_KEY`: Your Google Gemini API key

## Scripts
- `npm run dev`: Start development server
- `npm run build`: Build for production
- `npm run preview`: Preview production build locally

## Build Output Directory
The production build outputs to the `dist` directory