Welcome to the Masternode JebatCoin Installation Guide


To complete the installation of the Masternode, you must have this elements :

> 5 000 JCOIN
> 1 VPS (Configured on Ubuntu Server 16.04)
> Last version of JCOIN Wallet : https://github.comach-group/jebatcoin/releases 


- Step 1

Send your JCOIN coins from the exchange or from another wallet directly to the JCOIN official wallet.

Once the confirmation period is over, the pieces are on the wallet. 
Create a new receiving address with a meaningful name (for example : MN01).

Send the 8000 JCOIN coin back to this address of the MN01.

- Step 2

While the transaction is confirmed, Register account VPS at [Vultr](https://www.vultr.com/?ref=8239119)

Create Instance VPS $5 

Choose any country Ip

Choose Ubuntu and Select Ubuntu 16.04 LTS

Name your vps instance

Push deploy then wait finish installation for get ip and password 

go to your VPS with "Bitvise SSH Clien" software. Download here [Bitvise](https://dl.bitvise.com/BvSshClient-Inst.exe)

setting Authentication Username as "root" and Initial Method as "Password"

Copy VPS Ip Address to Host and Port on "22" then push login button

Use the following commands :  "sudo apt-get update && apt-get upgrade -y "

Your VPS is now cleaned up and up to date.

Enter the following line :

wget https://github.com/ach-group/jebatcoin/releases/download/2.0.1.1/JCOIN-mn-multi.sh

Then, complete :

bash ./jcoin-mn-multi.sh


- Step 3

Once the installation is complete, please enter your « TX ID » as requested.

To get it, go to the wallet: Tools -> Debug Console -> Type « masternode outputs » , you get the TX ID and the index (Take care to wait for the confirmation of your transaction to MN01).


- Step 4

You have finished ! Recover what the Installation Script gives you and copy it to the 
« masternode.conf » file.

To access it, go to the wallet : Tools -> « Open configuration file masternodes », there you are.
Final Step

Wait until the first rewards appear. 
If the masternode does not appear in the « Masternode » tab of the wallet, consider restarting the wallet.

In case of problem, do not hesitate to contact us on Telegram with the following link : 

https://t.me/joinchat/F76XdEyNIIjn1QjMX6bayw




Thank you for using JebatCoin
Complete Eco-System For PoS Coin
