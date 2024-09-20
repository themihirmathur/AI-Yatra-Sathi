# AI-Yatra-Sathi | AI Trip Planner

Welcome to **AI-Yatra-Sathi**, an advanced tour and travel planning application designed using **ReactJS**, **Tailwind CSS**, and **Vite.js**. This project provides users with an intuitive interface to plan trips efficiently, featuring a modern, responsive design. The application leverages cutting-edge web technologies to offer a seamless user experience across multiple devices, ensuring that users can access their trip plans from anywhere.

![Screenshot 2024-09-20 at 11 25 04 PM](https://github.com/user-attachments/assets/1a80a208-e57a-4644-b3a4-b378089f42bb)

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
- [License](#license)

## Features
- **Modern Multi-Route Setup**: Allows the creation of a sophisticated multi-page web application with dynamic routing.
- **Responsive Design**: Built with Tailwind CSS, the application is fully responsive, providing an optimized experience on all devices.
- **Seamless User Interface**: A user-friendly interface for planning trips, managing itineraries, and browsing travel recommendations.
- **Fast Development with Vite.js**: Utilizes Vite.js for an enhanced development experience with faster builds and optimized performance.
- **Easy Deployment**: Ready-to-deploy with seamless hosting capabilities to take the project live with minimal configuration.

![Screenshot 2024-09-20 at 11 25 36 PM](https://github.com/user-attachments/assets/a7e3a889-163d-4151-bf7a-599d5cdc7c38)

## Technologies Used
- **ReactJS**: For building the core structure and dynamic features of the web application.
- **Tailwind CSS**: For crafting a sleek, responsive design with utility-first CSS.
- **Vite.js**: For optimized build performance, fast local development, and hot module replacement (HMR).
- **React Router**: For multi-route navigation within the application.
- **Axios**: For handling HTTP requests to interact with external APIs for data integration.
- **Node.js**: For managing dependencies and running the local development environment.

## Getting Started
To get started with this project, follow the steps below to set up and run it on your local machine.

### Prerequisites
Ensure that you have the following installed:
- **Node.js** (v14 or higher)
- **npm** (v6 or higher)

You can download the latest versions of Node.js and npm from [Node.js official site](https://nodejs.org).

### Installation
Follow these steps to install the project:

1. Clone the repository:
    ```bash
    git clone https://github.com/themihirmathur/AI-Yatra-Sathi.git
    ```

2. Navigate into the project directory:
    ```bash
    cd AI-Yatra-Sathi
    ```

3. Install the necessary dependencies:
    ```bash
    npm install
    ```

### Usage
After completing the installation, you can run the project locally using Vite.js with the following command:
```bash
npm run dev
```
This will start the development server, and the application will be available at `http://localhost:3000`.

For production builds, you can run:
```bash
npm run build
```

### Folder Structure
Here is an overview of the project structure:

```bash
AI-Yatra-Sathi/
├── public/
│   ├── index.html
├── src/
│   ├── components/
│   │   ├── Header.js
│   │   ├── Footer.js
│   │   ├── TripPlanner.js
│   ├── pages/
│   │   ├── Home.js
│   │   ├── About.js
│   │   ├── Contact.js
│   ├── App.js
│   ├── index.js
├── package.json
├── tailwind.config.js
├── postcss.config.js
├── vite.config.js
├── README.md
```
- **components/**: Contains reusable UI components such as the header, footer, and trip planning functionality.
- **pages/**: Contains page components like Home, About, and Contact.
- **App.js**: The main component that integrates routing and renders other components.
- **tailwind.config.js**: Configuration file for Tailwind CSS.
- **vite.config.js**: Configuration file for Vite.js.
- **package.json**: Includes project metadata and dependencies.

## Contributing
Contributions are welcome! If you'd like to improve the project, feel free to fork the repository and submit a pull request.

1. Fork the Project
2. Create your feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a pull request

![Screenshot 2024-09-20 at 11 25 17 PM](https://github.com/user-attachments/assets/579b2f5b-d2b1-44fd-8916-1f402f85c5e1)

## License
This project is licensed under the MIT License. You are free to use, modify, and distribute the project in both personal and commercial projects. See the [LICENSE](LICENSE) file for more details.

---

This project serves as an excellent learning resource for developers aiming to create modern, responsive web applications using React, Tailwind CSS, and Vite.js. Whether you're looking to expand your knowledge of front-end frameworks or seeking to deploy a full-fledged application, AI-Yatra-Sathi provides a practical foundation for enhancing your web development skills.
