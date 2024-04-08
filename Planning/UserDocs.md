# User Documentation for HACKADEMIA

Welcome to the user documentation for HACKADEMIA. This guide will help you set up the application, configure the database, run the app, and address frequently asked questions.

## Setting up the Application

To set up the application, you will need to have a basic setup ready. This includes having a modern operating system capable of running batch files (e.g., Windows) and an internet connection. Currently our application setup does not support MAC. Please follow the steps below to get started:

1. **Download the Project**: Start by downloading the project folder from [Project Download Link](https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/connolrc/Hackademia-dev). Save the folder to a location of your choice on your computer.

2. **Run the Setup Script**: Inside the main project folder, you will find a batch file named `SetupScript.bat`. This script is designed to automate the setup process for your front-end React application, along with downloading necessary dependencies such as npm and node-gyp. Note: the batch file only works on Windows operating systems.
![Screenshot (36)](https://github.com/Phinmala/CS5001-Senior-Design/assets/43516411/79bc631f-c482-4c6a-ae19-608e4371490a)
    - Right-click on `SetupScript.bat` and select "Run as administrator". This is necessary to ensure the script has the permissions it needs to perform installations.
    - The script will execute several commands in the command prompt. This process may take a few minutes, depending on your internet speed and computer's performance. You will see messages indicating the progress of the setup.
    - Once completed, you should see a message indicating that the setup was successful.

3. **Verify the Installation**: After the script finishes running, it's a good idea to verify that everything was installed correctly. You can do this by checking the respective folders, frontend-dev and backend-dev, for the `node_modules` directory, indicating that npm packages have been installed successfully.

![image](https://github.com/Phinmala/CS5001-Senior-Design/assets/43516411/df5a5b39-dc5e-4eae-bc75-5743fb1778c6)

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

![image](https://github.com/Phinmala/CS5001-Senior-Design/assets/43516411/eb1eb7a4-b857-482d-9ffc-92cefe186012 | width=50)
### Running Only the Front-End Application

1. **Start the Front-End**: Navigate to the main project folder and locate the `StartFrontEnd.bat` file. Double-click on this file to run the front-end application. This will start the React application in your default web browser.

### Running the Full Application (Front-End and Server Backend)

1. **Start the Full Application**: If you need to run both the front-end and the server backend, locate the `StartFullApp.bat` file in the main project folder. Double-click on this file to initiate both the front-end React application and the server backend. This is recommended for a complete experience of the application's functionality.

Please wait a few moments for the applications to start. Once the front-end application launches in your browser, you should be able to interact with it as expected. If you're running the full application, ensure that the PostgreSQL database is set up and running as described in the previous section before starting the application.

## Running the App
When you first open HACKADEMIA, you'll be greeted with a stylish **Landing Page** featuring a neon grid floor and the HACKADEMIA slogan: DISCOVER, LEARN, and DEFEND. Click the `ENTER` button to proceed to the dashboard where the learning modules are located.
![Screenshot (42)](https://github.com/Phinmala/CS5001-Senior-Design/assets/43516411/4b92af02-e3c2-4ee9-b015-d92ee9e3ce5d)

The **Dashboard** is where you can access various learning modules:

- **The Call Stack**: Understand how C code interacts with the system's call stack.
- **Buffer Overflow**: Learn how buffer overflows can lead to vulnerabilities to overwrite memory of the program stack.
- **Command Injection**: Discover how command injection exploits a buffer overflow vulnerability.
  
Choose a module by clicking `Start` and begin your learning experience.
![Screenshot (43)](https://github.com/Phinmala/CS5001-Senior-Design/assets/43516411/801d5735-35a1-494b-a648-27694dbf0fe7)

Each module is designed to offer an in-depth learning experience:
![Screenshot (44)](https://github.com/Phinmala/CS5001-Senior-Design/assets/43516411/0303b5fb-6fc6-47d2-8e5a-82d6f50db626)

1. Read through the module's introductory text to grasp the topic's background.
2. Click `Next` to start the interactive experience and follow along with code examples and visual aids.
3. Use the `Back` and `Skip to End` buttons to navigate through the module at your own pace.
4. If you need to restart the module or practice again, simply click `Reset`.

If you need to return to the main **Dashboard** at any time to select a different module or revisit previous content, simply click the `Dashboard` link located in the top navigation bar. This will immediately take you back to the overview of all available modules.
Clicking on the **H**ACKADEMIA logo at the top left corner of the screen will always bring you back to the **Landing Page**.
![image](https://github.com/Phinmala/CS5001-Senior-Design/assets/43516411/db166ad1-6b95-44e0-9d0d-5e48681dd817)

## FAQ
**Q: Who can I contact if I have feedback or suggestions?**  
**A:** We value your feedback! Please submit any comments anonymously via the [Google Form](https://forms.gle/Ki2DBTHKK9BYDnHs5).


