# ACJBot
Slack bot for creating standup order

# [Environment Setup](https://www.fullstackpython.com/blog/build-first-slack-bot-python.html)
1. Open your terminal and navigate to the ACJBot directory
2. Type `virtualenv starterbot` (you can replace `starterbot` with whatever you want your virtual environment to be called; it's not important)
   * You may need to install this command - on WSL, I needed to run `sudo apt install python3-virtualenv`
3. Activate the virtual environment with `starterbot/bin/activate` (again, replace `starterbot` with whatever you decided to name your virtual environment)
4. Install requirements: `pip install slackclient==1.3.2 dotenv`
5. Export your slack token: `export SLACK_BOT_TOKEN='(bot user access token)'`

Now (in theory) you can run the bot locally with `python3 main.py`.