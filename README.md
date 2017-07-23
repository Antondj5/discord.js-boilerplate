# Discord Bot Example
All the files are well documented with what they do, the `app.js` also has instructions on what to install.  
But if you don't read that for some reason, then I'll just tell you what you need here.  

1. Download the repository as a zip file and un-zip it anywhere you like (preferably in a folder).  
2. Open a terminal in the bots project directory ex: `cd C:\Projects\DiscordBotExample-master`. Now we want to create a package.json file in our project folder that can save all the dependencies for our project, and also some information about it. Run the following and just fill in the fields: `npm init`.
3. Now we want to intall the required dependencies for the bot to work. Run: `npm install --save glob discord.js`.  And it will install the dependencies.

**NOTE:** The `playFile` command will only work if you also install `node-opus` or `opusscript`. To install these you need  
to have `windows-build-tools` installed. You can install them with: `npm install -g --production windows-build-tools`.  You will also need to have `FFMPEG` that can be installed with: `npm install -g ffmpeg-binaries` or by downloaded the binaries manually and adding them to your PATH variable (Google it if you don't know how to do that).  


If you have all you need installed you should just be able to open a terminal in your project directory and run `node app.js` and it should run the bot for you.
