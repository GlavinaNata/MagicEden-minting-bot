# MagicEden minting bot

---

This bot will help you mint all the Magic Eden NFT's projects, This bot of does not guarantee a successful mint but increases chances as well as gives you the possibility to mint bypass the minting limit !

Easy setup which uses ChromeDriver to open up a new chrome instance and mint the nft you are looking for quicker than a human. **This bot does not guarantee you will get your NFT**, this bot simply goes faster than humans to mint and automates everything since you do not have to click yourself.

- This bot sends a request to the magiceden server.

- Make sure the time on your computer is set correctly.
- For Support: 7XGhYc1dDAzrAjqV2nhLjHQ9nLzmZ1VSqRTggjbt3SoM (sol)

I laughed heartily, thank you
Our bots died guys, no one uses after the collapse of the blockchain

You can **launch multiple instances of the bot to bypass minting limit / wallet**

---

### Support

-   [x] Window
-   [x] Mac (Intel + m1)
-   [x] Linux (Not verified)

---

-   This bot uses ChromeDriver so on mac there is a possiblity that you will have to **allow the software to run in your privacy settings**. Check mac folder for more info.

-   The chrome window will appear **WITHOUT** loading the images, this is to ensure the fastest loading.

---

## Tutorial

1. Clone the repository / Download zip file (to the root of disk C:)

    `https://github.com/SolanaNFTHolder/MagicEden-minting-bot.git`

    OR

    [Download Zip File](https://github.com/SolanaNFTHolder/MagicEden-minting-bot/archive/refs/heads/main.zip)
    

2. Be sure you have installed Python correctly, [here is a link to download](https://www.python.org/downloads/)

3. Open command prompt

4. Install all python module

   `pip install selenium requests webdriver-manager`
   

5. Replace Phantom Passphrase and password in `config.json`

    `launchpadLink` --> Provide a link to the sale

    `seedPhrase` --> Specify the passphrase wallet (Careful do not share this key)

    `password` --> Enter your wallet password

6. Open CMD and go to directory
   `cd /path/to/directory/magiceden-minting-bot-main/`

7. Run the python file

    windows : `python main.py`

    mac : `python3 main.py`
    
    or start : `start.bat`
