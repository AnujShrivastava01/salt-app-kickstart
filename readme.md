# 🌟 Salt App Kickstart

![npm](https://img.shields.io/npm/v/salt-app-kickstart?style=flat-square) ![npm](https://img.shields.io/npm/dt/salt-app-kickstart?style=flat-square)

Create a new Salt Design System app quickly and easily.


## 🚀 Quick Start

To create a new Salt app, run:

```bash
npx salt-app-kickstart@latest
```
### What happens next:

- You’ll be prompted for a few details, such as the project name and template choice.
- The tool will automatically create the project structure tailored to your specifications.
- It will install all necessary dependencies for a smooth development experience.
- Finally, your app will launch on `localhost`, allowing you to start coding immediately!

## Video Demonstration
<div align="center">
<a href="https://drive.google.com/file/d/1JIBCPyL2K3Ta3AOMTqt7BuqHjlnxS7m3/view?usp=sharing" controls autoplay>
  <img src="/video-thumbnail.png" alt="Demonstration of the package" width="600"/>
</a>
</div>

## 🌟 Why Salt App Kickstart?

- **Automatic Setup**: Save time with pre-configured Salt Design System templates.
- **Flexible Templates**: Includes popular templates like AGGrid and Dashboard.
- **Local Development**: Automatically launches the app on `localhost` for immediate use.
- **GitHub Integration**: Easily push your app to a GitHub repository.

## 🛠 Project Structure

The generated project structure includes:

```plaintext
my-salt-app/
├── public/             # Static files (index.html, icons, etc.)
├── src/
│   ├── components/     # Reusable components like grids, dashboards
│   ├── pages/          # App pages (Home, Dashboard, etc.)
│   ├── styles/         # Global styles
│   ├── App.js          # Starting point of the app
│   └── index.js        # Main entry point (React)
├── .gitignore          # Files to ignore in Git
├── package.json        # Project scripts & dependencies
└── README.md           # Project information
```
- **Starting Point**: `src/index.js` bootstraps the app, initializing the React application and rendering the root component, which is typically `App.js`. This file is responsible for managing the application's routing and core functionality, ensuring a seamless user experience as users navigate through different views and components.

## 🔧 Features

- **📦 Pre-installed Salt Dependencies**: Save time with built-in support for Salt Design System components.
- **📊 AGGrid and Dashboard Templates**: Jumpstart your projects with ready-made grids and dashboards.
- **📱 Local Dev Environment**: The app automatically launches on `localhost` so you can start coding right away.
- **🔗 GitHub Integration**: Quickly push your project to a GitHub repository with built-in commands.

## 💻 Development Workflow

1. **Install dependencies**:

   ```bash
   npm install
   ```
2. **Run the app**:

   ```bash
   npm start
   ```
You can access your application by visiting [http://localhost:3000](http://localhost:3000) in your web browser. This will display your newly created app, allowing you to interact with it immediately.

3. **Build for production**:

   ```bash
   npm run build
   ```
This creates an optimized, production-ready build of your app inside the `build/` folder.

4. **Deploy your app** to hosting services like **GitHub Pages**, **Netlify**, or **Vercel**. Each platform provides simple guides for deploying your app:

   - **GitHub Pages**: Push your build folder to a GitHub repository and enable GitHub Pages in the settings.
   - **Netlify**: Drag and drop your `build/` folder to the Netlify dashboard for instant deployment.
   - **Vercel**: Connect your GitHub repository and follow the prompts to deploy.

## 🌐 Salt Design System Integration

The **Salt Design System** is pre-installed, offering reusable components and consistent UI elements for rapid development. With pre-styled components, you can focus on your app's logic and functionality while maintaining a cohesive design throughout your project.

## 🙌 Contributing

We welcome contributions! If you’d like to help improve this project, please check out our [Contributing Guide](CONTRIBUTING.md) for details on how to get involved.

## 📝 License

This project is licensed under the **MIT License**. For more details, check the [LICENSE](LICENSE) file in this repository.

## ❓ Questions?

If you have any questions or suggestions, feel free to [reach out](mailto:duddekuntadevamani@gmail.com). We’re here to help you build awesome apps with Salt!
