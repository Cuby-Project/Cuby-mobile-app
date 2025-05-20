# 📱 Cuby Mobile App

<div align="center">

[![GitHub stars](https://img.shields.io/github/stars/Cuby-Project/Cuby-mobile-app.svg)](https://github.com/Cuby-Project/Cuby-mobile-app/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/Cuby-Project/Cuby-mobile-app.svg)](https://github.com/Cuby-Project/Cuby-mobile-app/network)
[![GitHub issues](https://img.shields.io/github/issues/Cuby-Project/Cuby-mobile-app.svg)](https://github.com/Cuby-Project/Cuby-mobile-app/issues)
[![GitHub last commit](https://img.shields.io/github/last-commit/Cuby-Project/Cuby-mobile-app.svg)](https://github.com/Cuby-Project/Cuby-mobile-app/commits/main)

</div>

## 📝 Description

Cuby Mobile App is the mobile version of the Cuby ecosystem, built with React, TypeScript, and Vite. This application brings the power of Cuby to mobile devices, offering a seamless experience for Rubik's Cube enthusiasts on the go.

## 🔗 Related Projects

- [Cuby Client](https://github.com/Cuby-Project/Cuby-Client) - Main desktop application
- [Cuby Recognition API](https://github.com/Cuby-Project/Cuby-recognition-API) - Color detection API
- [Cuby Solve API](https://github.com/Cuby-Project/Cuby-solve-API) - Cube solving algorithm API
- [Cuby Capture API](https://github.com/Cuby-Project/Cuby-capture-API) - Cube state capture API
- [Cuby Capture Website](https://github.com/Cuby-Project/Cuby-capture-website) - Web interface

## ✨ Features

- 📱 Mobile-first design
- ⏱️ Timer functionality
- 🔄 Scramble generator
- 📊 Statistics tracking
- 🎯 Multiple cube support
- 🤖 Auto-solve feature (coming soon)

## 🚀 Getting Started

### 🔧 Prerequisites

- Node.js 16+
- npm or yarn
- React Native development environment

### 🛠️ Installation

1. Clone the repository:

```bash
git clone https://github.com/Cuby-Project/Cuby-mobile-app.git
```

2. Install dependencies:

```bash
npm install
# or
yarn install
```

3. Start the development server:

```bash
npm run dev
# or
yarn dev
```

## 🛠️ Development

### ESLint Configuration

```js
// eslint.config.js
import react from 'eslint-plugin-react'

export default tseslint.config({
  settings: { react: { version: '18.3' } },
  plugins: {
    react,
  },
  rules: {
    ...react.configs.recommended.rules,
    ...react.configs['jsx-runtime'].rules,
  },
})
```

## 🤝 Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Support

- [Report a bug](https://github.com/Cuby-Project/Cuby-mobile-app/issues/new/choose)
- [Request a feature](https://github.com/Cuby-Project/Cuby-mobile-app/issues/new/choose)
