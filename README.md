# Movie Hub

Movie Hub is a React and Vite movie browser that displays popular movies and supports movie search using The Movie Database API.

## Tech Stack

- React
- TypeScript
- Vite
- React Router
- Bootstrap
- The Movie Database API

## Repository Status

The current repository contains the project as `React-app.zip`. To run or inspect the app, extract the ZIP first. A recommended cleanup pass is to commit the extracted source files directly and remove generated folders such as `node_modules`.

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/lampi12/Movie-hub.git
cd Movie-hub
```

2. Extract `React-app.zip`.

3. Enter the extracted app directory:

```bash
cd React-app
```

4. Install dependencies:

```bash
npm install
```

5. Start the development server:

```bash
npm run dev
```

6. Open the local Vite URL shown in the terminal.

## Available Scripts

```bash
npm run dev
npm run build
npm run lint
npm run preview
```

## Notes

The API service currently calls The Movie Database directly. For a production deployment, move API credentials into environment variables instead of keeping them in source code.
