# TokenCrowdsale

##Crowdsale for PupperCoin

In the first contratc we create an ERC20 token called puppercoin passing thru name, symbol and inital supply parameters.

Then in a separate .sol file we create the crowdsale and the deployer for both. 
In creating the crowdsale contract we use the constructor to pass thru variables of wallet, goal, rate, token, open and close.
After passing thru the contructor we then utilize our openzepilin libraies and pass thru the correct parameters for each contract we import.

Then we created a new contract called the deployer. 
This contract creates the crowdsale start and finish as well as creatiung the token sale address and token address.
This contract also allows for the minting of coins and assigning ownership of the minting. 


![crowdsale](https://user-images.githubusercontent.com/78838822/135174170-70e0ecd2-43dd-4d88-ac92-98d3e34ce145.PNG)

![puppercoin](https://user-images.githubusercontent.com/78838822/135174209-fc5c8352-7b71-4430-83cc-acd49cb9cecb.PNG)

![image](https://user-images.githubusercontent.com/78838822/135174280-288f4771-a794-41bd-9d24-a4e51e44f3bf.png)
