Manuals
=============

How and where to download the KYCC wallet
---------------------

Welcome to the KYCC community! 
to become a full fledged member you definitely need to be running the KYCC wallet.

Our wallet will always only be hosted on our official Github repo which is linked on our official website. Please always confirm that you are on the correct website. Never trust any links to the wallet sent to you by random people.

   [Official Site](https://kyccoin.io/kycc-wallet/)  
   [Official GitHub repo](https://github.com/KYCCOIN/kyccoin/)  

1) To download the official KYCC wallet please navigate to our wallet directory on our [Official GitHub v1.0](https://github.com/KYCCOIN/kyccoin/releases/tag/v1.0)
   
   ![Example-Logo](https://i.imgur.com/TwXZ3tZ.jpg)

2) Select the correct wallet file from the above link for your PC,   
   for example I am using Windows so I am going to select the `kyccoin-1.0-win-x64.rar`   

3) It should now download , Once done that's it, Simply run the `kyccoin-qt.exe`

Where can I find my blockchain directory?
---------------------
The following table shows the default blockchain data directory per operating system.

<table>
<th>Operating System</th><th>Default datadir</th><th>Typical path to configuration file</th>
<tr><td>Windows</td><td>%APPDATA%\KYCC\</td><td>C:\Users\username\AppData\Roaming\KYCC\KYCC.conf</td>
<tr><td>Linux</td><td>$HOME/.KYCC/</td><td>/home/username/.KYCC/KYCC.conf</td>
<tr><td>macOS</td><td>$HOME/Library/Application Support/Examplecoin/</td><td>/Users/username/Library/Application Support/Examplecoin/KYCC.conf</td>
</table>

Back up wallet
---------------------
1) Close your wallet
2) Open the folder `%APPDATA%\KYCC\`
4) Copy the `wallet.dat` file to a safe place
   
   ![Example-Back-up-wallet](https://i.imgur.com/eNWM4vp.png)

How do I export the private key for a public address?
---------------------
Export the private key for an address with the following instructions.
Open your wallet.
Go to Tools -> Debug console.
This is the console where you execute RPC commands.
Type the following RPC command, to export your private key:
`dumpprivkey publicaddress`

Replace the text “publicaddress” with a public address from your wallet.

Example:
1) `dumpprivkey KJtA1U2MyfD5AU7kky1q3P5ceWws63xHCC`
2) `aQsLtrgMgD7thc76G5uja9z9wVTZJdh5MMiPHWgUf7aKsDJhHHev`
   
   ![Example-export-the-private-key](https://i.imgur.com/73KPfpa.png)

How do I import the private key for a public address?
---------------------
Import the private key for an address with the following instructions.
Open your wallet.
Go to Tools -> Debug console.
This is the console where you execute RPC commands.
Type the following RPC command, to import your private key:
`importprivkey privatekey`

Replace the text “privatekey” with a private key that your want to import in your wallet.
Example:
1) `importprivkey aQsLtrgMgD7thc76G5uja9z9wVTZJdh5MMiPHWgUf7aKsDJhHHev`
   
   ![Example-import-the-private-key](https://i.imgur.com/CNh5r95.png)

How do I create a receiving address?
---------------------
1) Open your wallet
2) Press on the button `Receive`
3) Press on the button `Request payment` to create a new receiving address
   
   ![Example-import-the-private-key](https://i.imgur.com/OVnJjqM.png)

How do I send coins to a public address?
---------------------
1) Open your wallet
2) Press on the toolbar button `Send`
3) Enter the receiving address after `Pay To:`
4) Enter the amount of coins you want to send after `Amount:`
5) Press on the button `Send` to send the transaction
   
   ![Example-import-the-private-key](https://i.imgur.com/W2Rr0Pc.png)



