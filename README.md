# Binance-Trade-Copier App
# Running the bot
This program uses web scraping to monitor the positions opened by traders sharing their positions on Binance Futures Leaderboard. We then mimic the trade in your account using the Bybit api. MongoDB is the database used in this software.

# Software setup
1. Setup a telegram bot using Botfather (details on telegram official site) and mark the access token.
2. Setup a discord channel for urgent/alert messages, and get a webhook url. (Reason is to avoid mixing them into the telegram channel and missing out on them.)

# Using the software
Click Setup.exe and make sure its up and running, go to your telegram bot and type /start, then follow the instructions.
It should be rather straightforward but if you encounter any uncertainties, please report it to me by raising an issue.
Refer to the file telegram-commands.txt for a list of commands you can use.
I personally suggest you go to the binance leaderboard, pick a longer timespan (e.g. monthly or all-time) and choose the top traders sharing their positions.
# Disclaimer
> Users are solely responsible for their own trading decisions and the management of their accounts. The author is not a financial advisor, and any information provided by the bot should not be taken as financial advice. Users should conduct their own due diligence and consider seeking advice from an independent financial advisor.
> Author does not accept any liability for loss or damage as a result of reliance on the information contained within this bot. Please be fully informed regarding the risks and costs associated with trading the financial markets.
> Remember that trading can lead to losses that exceed initial investments. Therefore, you should not trade with capital that you cannot afford to lose. If you have any doubts, it is advisable to seek advice from an independent financial advisor.
