# Cross-platform-app
Github repo for the cross platform version of the experimental flights Client App. 

**Note for beginners (as of Spring_2022):**

Use Debug -> 'expo start' inside package.json to run the app. 

When developer tools link open (localhost:X, Metro Bundler), run in web browser instead of IOS or Android emulator options. 
^ Disregard this with later updates post-Spring_2022.

Updates based on FRQs: 

- If you receive an error message while 'expo start', make sure that npm is installed. 
- Make sure the file you're viewing is package.json NOT package LOCK .json. Debugging tool is NOT in there. Those two are two different files!
- If expo start doesn't automatically open up a browser tab, manually copy the localhost link (provided in terminal) and copy&paste into browser tab.

- Summary: pull code from this repo -> open the files in VSCode -> open package.json file -> click Debug icon -> press expo start (make sure npm is installed) -> manually paste developer tools link (localhost:rand_num) OR let the browser open it self -> under Metro Bundler click run in web browser option -> DONE, happy coding
