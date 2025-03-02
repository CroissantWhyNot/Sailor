# Sailor
Free open-source Discord bot with AI powered chat moderation using Gemini's API, and other helpful commands.


Steps to install:

1.) Install the Python libraries Discord, asyncio, and google-generativeai.

2.) If you haven't already, create a new Discord app. If this is your first time, follow the tutorial in Discord's documentation. https://discord.com/developers/docs/quick-start/getting-started. You can skip the steps mentioning Ngrok, it is not necessary for bots from my personal experience.

3.) Make sure your app has the following permissions
![image](https://github.com/user-attachments/assets/28b12db5-df62-4003-8e35-0f87795d0121)

4.) Go to the "bot" page, scroll down, and enable these two switches to look like this. ![image](https://github.com/user-attachments/assets/4af71967-b80c-4314-8fa4-cbb006d0dd8c)


5.) Open a new notepad document, paste the code, and at the top, you will see the areas for the API keys.
![image](https://github.com/user-attachments/assets/3706e203-a433-48aa-99a9-059728034c28)

6.) Go to https://aistudio.google.com/ and create a new API key (make sure to log in with your Google account)
![image](https://github.com/user-attachments/assets/21d62554-cdf4-49ae-a5b4-613b5c450a4c)

7.) You will see an API section like this. If you haven't already, click that and copy your API key and paste it into the space in the notepad code where it says "REPLACE WITH YOUR GEMINI API KEY"![image](https://github.com/user-attachments/assets/3f674ed2-ea69-47ef-b026-a9b9ec4544ee)

8.) Go back to the Discord app page, and click "reset token", copy the new one, and paste it into the text box that says "REPLACE WITH BOT TOKEN"![image](https://github.com/user-attachments/assets/eff0777a-a7ae-4a01-bcff-6aefb4626a87)

9.) All done! Now hit "save as" in notepad, and name the file "discordbot.py", which will save it as a Python file. Now, open the discordbot.py file from your File Explorer, and presto! All done, now, go back to the app page in the developer portal, click Installation, and click the copy button for the install URL and paste it into your browser. ![image](https://github.com/user-attachments/assets/f55caeba-5477-4d4d-82eb-ccc4383c99b4)

Now, it should open the Discord app and ask you what server to add to. All this is now up to you, enjoy! When the bot gets updated, I will release new source code, and all you have to do is replace the gemini API key section and the Discord token section again, and the bot will be updated. Enjoy!





