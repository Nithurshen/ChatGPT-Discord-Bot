# ChatGPT-Discord-Bot
A Discord Chatbot made with the Opensource ChatGPT technology integrated for discord. This project has still way more improvements needed. Developers can fork and improve it.

Requirements:

--> VS Code

--> Node.js

--> Discord Account

--> OpenAI Account


To make your own bot follow this tutorial:


Step 1: (Setting up VS Code)

-->Open VS Code and create a new folder.

-->Import all the items in the repository and rename the ".env.nit" file to ".env".

-->Open terminal and apply the following command:
									
     npm install discord.js dotenv openai
     
        
  Step 2: (Getting OpenAI's API Key)
  
  --> Go to https://platform.openai.com/account/api-keys
  
  --> Create new API key, copy it and paste it in the ".env" file in the variable "OPENAI_KEY" using VS Code, and save the file.
  
  
  Step 3: (Getting Discord Bot Token)
  
  --> Go to https://discord.com/developers/applications
  
  --> Create new application
  
  --> Edit it's information
  
  --> Go to the section called "BOT" and add a bot.
  
  --> Click view token, and copy the code.
  
  --> Paste it in the ".env" file in the variable "BOT_TOKEN" using VS Code, and save the file.

--> Go back to discord bot settings, scroll down and enable "Message Content Intent", and scroll down even further and ensure that the bot has administrator permissions provided.
  
  
  Step 4: (Getting Bot Channel)
  
  --> Add the bot to your server and create a text channel dedicated for the bot.
  
  --> Right click the text channel and click "COPY ID" and then add it to the constant "BOT_CHANNEL" in index.js at line 25 using VS Code, and save the file.
  
  --> Now use the following command in the terminal to activate the bot:
  

    node .\index.js

--> Now chat with the bot in the dedicated text channel only.

Author: https://twitter.com/Nithurshen

https://www.youtube.com/@nithurshen
  
  
  
