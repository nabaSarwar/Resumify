# Resumify Resume Builder

Resumify is a web application that helps users create professional resumes with ease. Built using ReactJS, this tool allows you to input your details and see a real-time preview of your resume. The application features a two-pane layout with an editor on the left and a resume preview on the right, making it simple and intuitive to use.


## Screenshots

### Home Page
![Home Page](screenshots/home.png)


## Features

- **Real-time Editing**: See your resume update in real-time as you type.
- **Easy-to-use Interface**: A clean and intuitive interface designed for ease of use.
- **Responsive Design**: Works seamlessly on both desktop and mobile devices.
- **Customizable Sections**: Add, remove, and reorder sections of your resume as needed.
- **Download Resume**: Export your resume as a PDF.

## Technologies Used

- **ReactJS**: Frontend library for building user interfaces.
- **CSS**: Styling the application.
- **JavaScript**: Programming language for dynamic content.

## Getting Started

### Prerequisites

Make sure you have the following installed on your local machine:

- [Node.js](https://nodejs.org/) (v14 or higher)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/nabaSarwar/Resumify.git
    ```

2. Install dependencies:
    ```sh
    npm install
    # or
    yarn install
    ```

3. Start the development server:
    ```sh
    npm start
    # or
    yarn start
    ```

4. Open your browser and navigate to `http://localhost:3000` to see the application in action.

## Project Structure

```sh
resumify/
├── public/
│   ├── index.html
│   └── ...
├── src/
│   ├── components/
│   │   ├── Editor.js
│   │   ├── Resume.js
│   │   └── ...
│   ├── App.js
│   ├── index.js
│   └── ...
├── .gitignore
├── package.json
└── README.md
