# Note-Taker-App

  ![express](https://img.shields.io/npm/l/express)
  ![Note-Taker-App](https://img.shields.io/github/languages/top/skycode20/Note-Taker-App)
  [![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v2.0%20adopted-ff69b4.svg)](code_of_conduct.md)

  - by *Skyler Rencher*
  
  ## Description    

  The Note Taker App is great for business professionals that have packed schedules and need to remind themselves of information they have in mind one moment and want to remember it for later. This is important because it allows a professional to have maximum productivity over the course of their work day without forgetting new tasks along the way. 

  My inspiration behind this project was to provide a application that was easy to use for the everyday person that could be scaled up for enterprise. I can envision this application being licensed to small and big companies alike for use with each employee. The notes will be saved on a database exclusive to each employee that they alone have access to.

  The main challenge with this project was getting the application to deploy on Heroku for instant access from anyone who wanted to utilize the application right away. The issue I was having with it was the fact that there was an error when engaging the deployment of the application. I couldn't figure out why the error was happening when the entire time the code worked just fine locally. But then I came to realize that all of my source code was within a folder named `Development` and that was causing an error with Heroku. Once I extracted the contents from the Development folder to the main folder, I then tried again and it worked properly. 

  My aspirations for the future of this application are to expand the functionality to be able to do the following:
  - Send reminders to the user.
  - Enable the notes' data to be synced to the cloud and accessed anywhere.
  - Having the ability to work natively with browsers.

  ## Table Of Contents    

  * [Installation](#installation)
  * [Usage](#usage)
  * [License](#license)
  * [Contributing](#contributing)
  * [Tests](#tests)
  * [Questions](#questions)
  
  ## Installation    

  To install the **Note Taker APP** please follow these steps:

  1. Download all of the project's source files `(clone the GitHub repository)`.
  2. Ensure your terminal is inside of the current folder that contains the source files.
  3. Install the following **NPMs** `(Node Package Managers)` in the system terminal:
        * Node.js
        * Express (command: ```npm i express```)
        * FileSystem (command: ```npm i fs```)
        * Path (command: ```npm i path```)
        * Util (command: ```npm i util```)
        * **Or just ```npm i``` that will install the packages within the `package.json` file.**

  Once that is all installed, while the integrated terminal is inside of the folder, run the command in the CLI ```node server.js``` to run the application on the `localhost:3000` (or whichever port it is running on) and input that in the url of a browser. The application will be deployed locally with all of its functionality.

  ## Usage    

  It is a very straightforward and accessible application to use. When the application is launched, press the `get started` button on the splash page of the Note Taker App. 

  <!-- insert picture -->

  Then input the desired information that which includes the title of the note and the description of the note. Press the save icon in the top right corner of the application to save your note. If you decide that you would like to get rid of the note than you can press the delete button found on the right side of the entries. The deletion is permanent. 

  <!-- insert image -->

  ## License    

  The Express npm is covered under the following license: ![express](https://img.shields.io/npm/l/express)

  ## Contributing     

  If you are interested in contributing to this project please adhere to the set of guidelines set forth by the [Contributor Covenant](https://www.contributor-covenant.org/version/2/0/code_of_conduct/). If any questions about the contributor guidelines feel free to contact me at skyler.rencher@gmail.com.

  ## Tests    

  No tests were run aside from manually debugging through trial and error.

  ## Questions    

  If you have any questions about the project feel free to reach out to me on via email: skyler.rencher@gmail.com or via Git Hub: https://github.com/skycode20.
  
  ## Links

  * [Note-Taker-App Application](https://morning-eyrie-44899.herokuapp.com/)
  * [Note-Taker-App Repo](https://github.com/skycode20/Note-Taker-App)
  * [Note-Taker-App Demo Video](https://github.com/skycode20/Note-Taker-App)
