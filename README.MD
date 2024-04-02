# Project Name

   **Real Time Chat Application using NodeJs, ReactJs, and ChatEngine.io**

     ## Glimpse of the Application: 

![](frontend\public\Home.png)
![](frontend\public\ChatBox.png)



## Description

A brief description of your project.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository.
    ```bash
    npm clone https://github.com/iamnkr67/NodeJs_Realtime-Chat_Application.git
    ```

2. Install the dependencies by running the following command:

   ```bash
   npm install
   ```
   
3. Connecting Node JS to ChatEngine.io
**ChatEngine.io** provides full-stack chat tools - which makes adding chat into Node apps easy.

To leverage this tool, we’ll create a Chat Engine project, and store our users in this project. All users in our Chat Engine project can chat with one another through their APIs / platform.

Let’s create a Chat Engine project for our users and connect our Node JS server to it!

Go to ChatEngine.io, sign up, and create your first project. Once this is done, you’ll see a *Project ID* and a *Private Key*.

4. Configure frontend/env.local as: 
    ```bash
    VITE_CHAT_ENGINE_PROJECT_ID="Your-Project-ID"  
    ```


## Usage

1. Start the backend by running the following command:

   ```bash
   npm start
   ```

2. Start the frontend by running the following command:
    ```bash 
      npm run dev
    ```

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your forked repository.
5. Submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
