# Tree watering app

## Step-by-step on how we built it

### Getting comfortable with the tools for building the app: an intro to unix commands in the terminal, git, and basics of react native development.
1. Open your terminal. `cd` into your documents folder (type `cd ~/Documents/` into your terminal) then create a projects folder ("mkdir projects") and cd into it ("cd projects"). Then git clone the repository (type `git clone https://github.com/samghelms/Tree-watering-app.git` in the terminal).
2. Once the repository has finished cloning, install npm dependencies. To do this, type `npm install` into your terminal (navigate into the `/Documents/projects/Tree-watering-app` folder if you aren't there already).
3. Install the expo app on your iphone (https://expo.io/tools). You can find it by searching for "expo" in the itunes store. Open the expo app.
4. Type `npm start` into your terminal (still in the `/Documents/projects/Tree-watering-app` folder) and then scan the barcode using the expo app. 
5. Exit out of the server (`ctrl+c` twice in the terminal).
6. Create a branch for yourself on git. (Note: https://www.atlassian.com/git/tutorials can serve as a reference for all these steps). Type `git checkout -b YOURNAME_branch`--typing in your actual first name instead of YOURNAME.
7. Open up the `App.js` file in sublime text and add a new line of code below all of the `<Text> </Text>` tags. I added `<Text> Sam was here </Text>`.
8. Save the file with your changes (`ctrl+s`). 
9. Restart the server ("`npm start`" in your terminal). Scan the QR code again and admire the results of your work. (You should see whatever text you added in step g. on the app).
10. Stop the server again (`ctrl+c`). Time to commit your changes. Type `git add *` and then `git commit -m "Added a line of text to App.js"` into your terminal. Finally, type `git push` into the terminal. You will get an error message since you haven't actually created the branch on the web yet. Copy paste the command git prompts you with into your terminal, then repeat the `git add *` and then `git commit -m "Added a line of text to App.js"`. 

#### References:
* React native tutorial: https://github.com/react-community/create-react-native-app
* Git: https://www.atlassian.com/git/tutorials
* Unix commands: http://blog.teamtreehouse.com/introduction-to-the-mac-os-x-command-line
