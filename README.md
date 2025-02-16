# Basic Webpack Template

A simple webpack template for web projects, configured for both development and production environments.

## Features

- Webpack bundling
- Development server with hot reloading
- CSS processing
- Image handling
- Production optimization
- ESLint and Prettier ready

## Setup

1. Clone this template
```bash
git clone [your-repo-url]
```

2. Install dependencies
```bash
npm install
```

## Usage

For development:
```bash
npm run dev
```
- Starts development server
- Opens in your browser
- Hot reloading enabled

For production build:
```bash
npm run build
```
- Creates optimized build in `dist` folder
- Bundles and minifies code
- Adds content hash to filenames

## Project Structure

```
project-root/
├── src/
│   ├── template.html
│   ├── index.js
│   └── styles.css
├── webpack.common.js
├── webpack.dev.js
└── webpack.prod.js
```

## Dependencies

### Core Dependencies
- webpack
- webpack-cli
- webpack-dev-server
- webpack-merge

### Loaders and Plugins
- css-loader
- style-loader
- html-webpack-plugin

### Code Quality
- eslint
- prettier

## Configuration Files

- `webpack.common.js` - Shared webpack configuration
- `webpack.dev.js` - Development-specific settings
- `webpack.prod.js` - Production optimization settings

## License

[MIT](https://choosealicense.com/licenses/mit/)