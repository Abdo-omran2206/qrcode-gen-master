# QR Code Gen Master

A modern, responsive QR code generator built with Next.js and React. Create beautiful, customizable QR codes instantly with color customization and download options.

![QR Code Gen Master](https://img.shields.io/badge/QR%20Code%20Gen%20Master-v1.0.0-blue)
![Next.js](https://img.shields.io/badge/Next.js-14.0.0-black)
![React](https://img.shields.io/badge/React-18.0.0-blue)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0.0-blue)

## ✨ Features

- **🎨 Custom Colors**: Choose your own primary and background colors
- **📱 Responsive Design**: Works perfectly on desktop, tablet, and mobile
- **⚡ Instant Generation**: Real-time QR code updates as you type
- **💾 Download Support**: Click to download QR codes as PNG files
- **🎯 Modern UI**: Clean, dark theme with glassmorphism effects
- **⌨️ Keyboard Support**: Press Enter to generate QR codes
- **🔄 Loading States**: Visual feedback during generation

## 🚀 Live Demo

Visit the live application: [QR Code Gen Master](https://qrcode-gen-master.vercel.app)

## 🛠️ Technologies Used

- **Next.js 14** - React framework with App Router
- **React 18** - UI library with hooks
- **TypeScript** - Type-safe JavaScript
- **CSS Modules** - Scoped styling
- **QR Server API** - External QR code generation service

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/qrcode-gen-master.git
   cd qrcode-gen-master
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 🏗️ Project Structure

```
qrcode-gen-master/
├── app/
│   ├── componets/
│   │   ├── qrparm.tsx      # Form controls component
│   │   └── qrprev.tsx      # QR code preview component
│   ├── styles/
│   │   ├── qrparm.module.css
│   │   └── qrprev.module.css
│   ├── globals.css         # Global styles
│   ├── layout.tsx          # Root layout
│   └── page.tsx           # Main page component
├── public/                # Static assets
├── package.json
├── next.config.ts
├── tsconfig.json
└── README.md
```

## 🎯 How to Use

1. **Enter Text**: Type any text, URL, or data you want to encode
2. **Choose Colors**: 
   - Select primary color for the QR code
   - Select background color
3. **Generate**: Click "Generate QR Code" or press Enter
4. **Download**: Click on the generated QR code to download it

## 🔧 Configuration

### Environment Variables

No environment variables are required for basic functionality. The app uses the free QR Server API.

### Customization

You can customize the app by modifying:

- **Colors**: Update the color scheme in `globals.css`
- **Styling**: Modify component styles in the `styles/` directory
- **API**: Change the QR code generation service in `qrprev.tsx`

## 📱 Responsive Design

The app is fully responsive and optimized for:

- **Desktop**: Full layout with side-by-side components
- **Tablet**: Adaptive layout with proper spacing
- **Mobile**: Stacked layout for optimal mobile experience

## 🎨 Features Breakdown

### QR Code Generation
- Uses external QR Server API for reliable generation
- Supports any text, URL, or data format
- Real-time color customization
- High-quality PNG output

### User Interface
- Dark theme with glassmorphism effects
- Smooth animations and transitions
- Loading states and visual feedback
- Keyboard navigation support

### Download Functionality
- One-click download as PNG
- Unique filenames with timestamps
- Visual feedback on hover
- Cross-browser compatibility

## 🚀 Deployment

### Vercel (Recommended)

1. Push your code to GitHub
2. Connect your repository to Vercel
3. Deploy automatically

### Other Platforms

The app can be deployed to any platform that supports Next.js:

- **Netlify**: Use the Next.js build command
- **Railway**: Direct deployment from GitHub
- **AWS Amplify**: Full-stack deployment
- **Docker**: Containerized deployment

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Development Guidelines

- Follow TypeScript best practices
- Use CSS Modules for styling
- Maintain responsive design
- Add proper error handling
- Include loading states

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **QR Server API** - For reliable QR code generation
- **Next.js Team** - For the amazing framework
- **React Team** - For the powerful UI library
- **Inter Font** - For the beautiful typography

## 📞 Support

If you have any questions or need help:

- **Issues**: Create an issue on GitHub
- **Discussions**: Use GitHub Discussions
- **Email**: Contact the maintainer

## 🔄 Changelog

### v1.0.0
- Initial release
- QR code generation with color customization
- Download functionality
- Responsive design
- Modern UI with glassmorphism effects

---

**Made with ❤️ by [Your Name]**

[![GitHub stars](https://img.shields.io/github/stars/yourusername/qrcode-gen-master)](https://github.com/yourusername/qrcode-gen-master/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/yourusername/qrcode-gen-master)](https://github.com/yourusername/qrcode-gen-master/network)
[![GitHub issues](https://img.shields.io/github/issues/yourusername/qrcode-gen-master)](https://github.com/yourusername/qrcode-gen-master/issues)
