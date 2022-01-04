Manuals
=============

How and where to download the KYCC wallet
---------------------

Welcome to the KYCC community! 
to become a full fledged member you definitely need to be running the KYCC wallet.

Our wallet will always only be hosted on our official Github repo which is linked on our official website. Please always confirm that you are on the correct website. Never trust any links to the wallet sent to you by random people.

   [Official Site](https://kyccoin.io/kycc-wallet/)  
   [Official GitHub repo](https://github.com/KYCCOIN/kyccoin/releases)  

1) To download the official KYCC wallet please navigate to our wallet directory on our [Official GitHub](https://github.com/KYCCOIN/kyccoin/releases)

![Example-Logo](https://i.imgur.com/TwXZ3tZ.jpg)

2) Select the correct wallet file from the above link for your PC,   
   for example I am using Windows so I am going to select the `kyccoin-1.0-win-x64.rar`   

3) It should now download , Once done that's it, Simply run the `kyccoin-qt.exe`

Back up wallet
---------------------
1) Close your wallet.
2) Open the folder "% APPDATA% \ KYCC \".
3) Copy the "wallet.dat" file to a safe place.

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

    dumpprivkey KLEgTdix7PMqBQ2Mg1PRVZ2dmYND1yRzkL

Example output:
`aQPjfn1B7TtGJEjhuVbJdkEwvVuKDUbVfowdJroxiNkZhJqtw69i`

How do I import the private key for a public address?
---------------------
Import the private key for an address with the following instructions.
Open your wallet.
Go to Tools -> Debug console.
This is the console where you execute RPC commands.
Type the following RPC command, to import your private key:
importprivkey privatekey

Replace the text “privatekey” with a private key that your want to import in your wallet.
Example:

    importprivkey aQPjfn1B7TtGJEjhuVbJdkEwvVuKDUbVfowdJroxiNkZhJqtw69i

How do I create a receiving address?
---------------------
Create a public receiving address with the following instructions.
Open your wallet.
Press on the button "Receive".
Press on the button "Request payment" to create a new receiving address.

How do I send coins to a public address?
---------------------
Send a coins to a public address with the following instructions.
Open your wallet.
Press on the toolbar button "Send".
Enter the receiving address after "Pay To:"
Enter the amount of coins you want to send after "Amount:"
Press on the button "Send" to send the transaction.

Follow these additional steps when you see the message "(Smart fee not initialized yet. This usually takes a few blocks...)"
Press on the button "Choose..."
Select "Custom".

Where can I find my blockchain directory?
---------------------
The following table shows the default blockchain data directory per operating system.

<table>
<th>Operating System</th><th>Default datadir</th><th>Typical path to configuration file</th>
<tr><td>Windows</td><td>%APPDATA%\KYCC\</td><td>C:\Users\username\AppData\Roaming\KYCC\KYCC.conf</td>
<tr><td>Linux</td><td>$HOME/.KYCC/</td><td>/home/username/.KYCC/KYCC.conf</td>
<tr><td>macOS</td><td>$HOME/Library/Application Support/Examplecoin/</td><td>/Users/username/Library/Application Support/Examplecoin/KYCC.conf</td>
</table>
