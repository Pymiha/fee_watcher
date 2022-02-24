# fee_watcher
Is a simple Python code packed into an executable. 
It monitors MetaMask window in web browser and executes transaction when fee is below set limit.
Currently only supports windows OS.

HOW TO USE
1. Download fee_watcher.exe and put it in some folder. 
2. Install tesseract from https://github.com/UB-Mannheim/tesseract/wiki and note down path to tesseract.exe.
3. Open web browser and MetaMask and request a transaction - claim or stake tokens. Make sure you have enough funds in wallet and transaction could actually go through. 
   Otherwise a warning is displayed and it messes up position of confirm button.
5. Run fee_watcher.exe. It opens in console window. Open positions.jpg from this repository, to see where to click. Using it for the first time follow through with configuration steps.    When done conf.txt file will be stored in base folder. In case configuration did not end succesfully, delete this file and try again. Delete this file in case of any changes 
   that move elements on the screen - resolution, browser, changed MetaMask window,...
7. Set some very low value for maximum fee and confirm program is correctly reading fee value. Fee values are written to fee_DD_MM_YY.txt file in base folder. 
   Screenshots are stored in same folder as metamask.png. A new screenshot is taken every 15 seconds. 
7. For program to work MetaMask must be visible on the screen.
8. After confirming it properly reads fee value, restart program. Put a sensible maximum fee and let it run. If fee will be lower than set value, transaction will be 
   executed.
   
DISCLAIMER
I have no responsibility or any other accountability in case program would not run as expected or execute transaction at a wrong time. 
You are running it fully at your own responsibility. By using it, you implicitly confirm you agree to this condition.

SUPPORT
In case you are happy with this code and wish to share some of the money it helped you save, here is my wallet address on ETH:
0x5f1922742223d6114003F251a382A15070bA76A6

CONTACT
easysent5p@gmail.com
Obviously I will be much more willing to answer those who contributed to above mentioned wallet. If you did, and have questions, put your wallet address in email.

