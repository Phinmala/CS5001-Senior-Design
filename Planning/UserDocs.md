# User Documentation for HACKADEMIA

Welcome to the user documentation for HACKADEMIA. This guide will help you set up the application, configure the database, run the app, and address frequently asked questions.

## Setting up the Application

To set up the application, you will need to have a basic setup ready. This includes having a modern operating system capable of running batch files (e.g., Windows) and an internet connection. Currently our application setup does not support MAC. Please follow the steps below to get started:

1. **Download the Project**: Start by downloading the project folder from [Project Download Link](https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/connolrc/Hackademia-dev). Save the folder to a location of your choice on your computer.

2. **Run the Setup Script**: Inside the main project folder, you will find a batch file named `SetupScript.bat`. This script is designed to automate the setup process for your front-end React application, along with downloading necessary dependencies such as npm and node-gyp. Note: the batch file only works on Windows operating systems.

    - Right-click on `SetupScript.bat` and select "Run as administrator". This is necessary to ensure the script has the permissions it needs to perform installations.
    - The script will execute several commands in the command prompt. This process may take a few minutes, depending on your internet speed and computer's performance. You will see messages indicating the progress of the setup.
    - Once completed, you should see a message indicating that the setup was successful.

3. **Verify the Installation**: After the script finishes running, it's a good idea to verify that everything was installed correctly. You can do this by checking the respective folders, frontend-dev and backend-dev, for the `node_modules` directory, indicating that npm packages have been installed successfully.

## Setting up the Database with PostgreSQL

Before you can run the application, you'll need to set up a PostgreSQL database on your PC. Follow these steps to install PostgreSQL and prepare your database:

### Prerequisites

1. **Operating System**: Ensure your operating system supports the version of PostgreSQL you intend to install. PostgreSQL is compatible with Windows, macOS, and Linux.
2. **System Permissions**: Administrator or superuser privileges may be required for the installation.

### Installation Steps

1. **Download PostgreSQL**:
    - Visit the official PostgreSQL website at [https://www.postgresql.org/download/](https://www.postgresql.org/download/) and choose the version compatible with your operating system. Download the installer for your OS.

2. **Install PostgreSQL**:
    - **Windows Users**: Run the downloaded installer, which will guide you through selecting components (including pgAdmin for database management), setting a password for the superuser (postgres), and choosing a port (default is 5432).
    - **macOS/Linux Users**: Follow the installation process provided on the PostgreSQL website for your specific OS. This may involve package managers or terminal commands. You will also set the superuser password and select the port during this process.

3. **Verify Installation**:
    - Open a command prompt or terminal.
    - Enter `psql -U postgres` and press Enter, then input the superuser password when prompted.
    - Success is indicated by accessing the PostgreSQL prompt.

## Running the App

You have two options for running the application: you can either run only the front-end application, or you can run both the front-end and the server backend for a full application experience. Below are the steps for each method:

### Running Only the Front-End Application

1. **Start the Front-End**: Navigate to the main project folder and locate the `StartFrontEnd.bat` file. Double-click on this file to run the front-end application. This will start the React application in your default web browser.

### Running the Full Application (Front-End and Server Backend)

1. **Start the Full Application**: If you need to run both the front-end and the server backend, locate the `StartFullApp.bat` file in the main project folder. Double-click on this file to initiate both the front-end React application and the server backend. This is recommended for a complete experience of the application's functionality.

Please wait a few moments for the applications to start. Once the front-end application launches in your browser, you should be able to interact with it as expected. If you're running the full application, ensure that the PostgreSQL database is set up and running as described in the previous section before starting the application.


## FAQ



