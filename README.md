# web



## Getting Started

This is a React application bootstrapped for the Stelm MVP platform.

### Development

```bash
npm install
npm start
```

The app will run on [http://localhost:3000](http://localhost:3000).

### Build

```bash
npm run build
```

Builds the app for production to the `build` folder.

### Docker

```bash
docker build -t imki-org/u-9004331b-stelm-livetest-saas-1778320828-prod-web .
docker run -p 3000:3000 imki-org/u-9004331b-stelm-livetest-saas-1778320828-prod-web
```

## Project Structure

```
src/
  ├── App.js          # Main application component
  ├── App.css         # Application styles
  ├── index.js        # Entry point
  └── index.css       # Global styles
public/
  └── index.html      # HTML template
```

## Learn More

- [React Documentation](https://reactjs.org/)
- [Create React App Documentation](https://create-react-app.dev/)
