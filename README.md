# _Text-to-Speech App_

#### _A React app that leverages Text-to-Speech API to read..._

By James Cho\_

## Components

![Alt text](HEADER.png?raw=true "structure")

## Description

See static version here: https://github.com/hwisoo/capstone-static-version.git

\_Name of Project: Text-to-Speech Reader

Project’s Purpose or Goal: (What will it do for users?) Fetch news articles of the day and read articles to the user.

List the absolute minimum features the project requires to meet this purpose or goal:

Fetch articles of the day using API or web scraping
Convert text to speech and read out loud for the user
Provide user-interface for the user to interact with
What tools, frameworks, libraries, APIs, modules and/or other resources (whatever is specific to your track, and your language) will you use to create this MVP? List them all here. Be specific.

IBM text-to-speech API
React
Bootstrap
If you finish developing the minimum viable product (MVP) with time to spare, what will you work on next? Describe these features here: Be specific.

Possible translating service with Google translate
Customizable news feed
Possible alarm feature, that will allow the program to run at the specified time
What additional tools, frameworks, libraries, APIs, or other resources will these additional features require?

Google translate
Access to a variety of news API's\_

### Specs

| Spec
| :-------------  
| 1
| 2
| 3
| 4
| 5

## Setup/Installation Requirements

- 1
- Clone this repository https://github.com/hwisoo/capstone-planning-repo.git
- Install Node.js
- Open Mac Terminal or Windows Command Prompt.

- Type "npm install" and press enter to install plugins and dependencies.
- Go to https://firebase.google.com/ and log in or create an account.
- Create a firebase project.
- Click on the circular gear icon next to the 'Project Overview' in the project you just created in Firebase.
  - Under the general tab, click on "Add Firebase to your web app:.
  - Copy everything inside the curly brackets of 'var config = { ... }.
- Create a file in the app folder called 'api-keys.ts'.
  - Inside the api-keys.ts file, type in 'export const masterFirebaseConfig = {}'
  - Inside the curly braces, paste what you copied earlier from Firebase.
- Click on 'Database' on the left side of Firebase console under your project and create a database.
  - Next to the 'Database' header click on the dropdown menu and click on 'Realtime Database'.
  - Click on the icon that looks like three vertical dots under the 'Data' tab and click on 'Import JSON'.
  - Import the 'sample-exclusive-booklist.json' file inside this repo in the root folder."
  - Click on the 'Rules' tab of the database.
  - Under rules, change the 'false' of '.read' to true.
- Type in "ng serve -o" to start the app in your Chrome browswer.

## Support and contact details

- _James Cho - hwisoocho@gmail.com_

## Technologies Used

- _React_
- _NPM_
- _VS Code_
- _Git_
- _GitHub_
- _HTML_
- _Javascript_
- _CSS_

## License

_This software is licensed under the MIT license._

Copyright (c) 2019 \*\*\_ James Cho
