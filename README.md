# LimitSwap
LimitSwap is a trading bot for UniSwap & Many Other DEXs. It has the ability to scan multiple pairs on uniswap and grab the price in realtime and make automated trading decisions based on the users settings [AKA: Limit Orders]


*This bot was built as a learning project for me to learn how to use Web.py, Erc20, & improve my coding skills please use at your own risk!*

&nbsp;
&nbsp;

## HOW TO INSTALL LimitSwap
### 1. Run The Python Code Locally (this is most ideal and can work on any OS)

Here is a tutorial step-by-step: 
- [x] Download last LimitSwap code on the "Code" page https://github.com/CryptoGnome/LimitSwap by clicking on Code > Download Zip : 
<img src="https://user-images.githubusercontent.com/70858574/145568534-e22c2887-d761-4fba-8dd0-f765b4300a6c.png" width="300">

- [x] Unzip file
- [x] Install Python on your computer : https://www.python.org/downloads/ 

**PLEASE ADD IT TO PATH BY CHECKING THIS OPTION:**

<img src="https://user-images.githubusercontent.com/70858574/145738124-e724c843-82d5-410d-b0b4-d7a9dda92258.png" width="500">

- [x] Install Visual Studio : https://visualstudio.microsoft.com/fr/thank-you-downloading-visual-studio/?sku=Community&rel=17

Please install the default package and all those options :
![image](https://user-images.githubusercontent.com/70858574/145580447-bd648d6d-c3ce-4dd9-8527-84ecfb5f30cc.png)

- [x] Open **Windows Powershell** (or Mac Terminal on MacOs)

- [X] Run this command to locate LimitSwap folder : 

`Get-ChildItem -Filter LimitSwap.py -Recurse -ErrorAction SilentlyContinue -Force`

- [x] It should look like this:

<img src="https://user-images.githubusercontent.com/70858574/145693132-509cb684-8fd8-45d3-8ecf-0e90a5c7e513.png" width="700">

- [X] Copy the Directory 

(on my computer it's : `C:\Users\Administrator\Desktop\LimitSwap-master`  but adapt it to your own result obtained above !!)

- [X] Paste the Directory after the "cd" command to navigate through the bot folder 

(on my computer it's : `cd C:\Users\Administrator\Desktop\LimitSwap-master`  but adapt it to your own result obtained above !!)

<img src="https://user-images.githubusercontent.com/70858574/145731606-9a990d30-737a-444e-98e9-cd93f169315d.png" width="700">


- [x] Run command: `pip install -r requirements.txt`  --> this will install all the packages needed to run LimitSwap

&nbsp;

✅ ✅ ✅ And it's done! ✅ ✅ ✅

&nbsp;

- [x] Simply **double-click on "LimitSwap.py"** and it will run, since you've installed Python 👍👍


&nbsp;

### 2. With Docker

#### Requirements
- [x] MacOS and Windows users require Docker for Desktop https://www.docker.com/products/docker-desktop
- [x] Ubuntu Linux require Docker installed `sudo apt-get install docker.io`

#### Usage
- [x] Navigate into the bot directory and build the Docker image by executing the following command:

`docker build -t limit_swap_v4 .`

- [x] (For MacOS and Linux) 

Still within the main directory you can run Docker via:

`docker run --rm --name limit-swap_v4 -it -v $(pwd)/settings.json:/app/settings.json -v $(pwd)/tokens.json:/app/tokens.json limit_swap_v4`

- [x] (For Windows with Powershell):

`docker run --rm --name limit-swap_v4 -it -v $PWD/settings.json:/app/settings.json -v $PWD/tokens.json:/app/tokens.json limit_swap_v4`

- [x] If you wish to run the container in the background please include -d for detached.

- [x] The streaming container logs can be visualised with: `docker logs -f limit_swap_v4`

- [x] To stop the bot: `docker stop limit_swap_v4`

#### Pros and cons
🟢 : easy to setup if you know Docker

🔴 : needs Docker

&nbsp;
&nbsp;


## Developers 🔧
Want to help contribute to LimitSwap, reach out on telegram all you need to do is make changes or fix bugs and we will pay developer bounties in $LIMIT for helping make the bot batter!


## Links & Socials

#### WiKi
https://limitswapv3.gitbook.io/limitswap/

#### Website:
https://www.limitswap.com/

#### Twitter:
https://twitter.com/LimitSwap

#### Telegram:
https://t.me/LimitSwap
