# PriceBite

The "Pricebite" project addresses the increasing challenge users face in selecting cost-effective options when ordering food from various delivery platforms. As the food delivery market grows, prices fluctuate across platforms, leading to potential savings for users. The project aims to empower users with a tool that automates the comparison of cart prices between different platforms, starting with Swiggy and Magicpin.

# ScreenShots
<img src="frontend\images\screenshots\Screenshot 2023-11-29 083222.png">
<img src="frontend\images\screenshots\Screenshot 2023-11-29 083239.png">
<img src="frontend\images\screenshots\Screenshot 2023-11-29 083307.png">
<img src="frontend\images\screenshots\Screenshot 2023-11-29 083428.png">

# How To Use
1. Go to Login
2. Enter your Phone No.
3. Enter the OTP.
4. Rest we will do !

# How to Run The Project
OLD:

open terminal in folder:
java -jar selenium-server-standalone-3.141.59.jar -role hub -hubConfig hubconfig.json

Java -Dwebdriver.chrome.driver="chromedriver.exe" -Dwebdriver.gecko.driver="geckodriver.exe" -jar selenium-server-standalone-3.141.59.jar -role node -nodeConfig nodeconfig.json


LATEST:

0. start xampp server
1. paste drivertest folder into htdocs folder
2. paste seleniumdbw folder into hrdovs folder
3.open terminal inside drivertest folder and run this command:
	java -jar selenium-server-4.15.0.jar hub
4. open cmd as administator and run these one by one
	a. cd C:\xampp\htdocs\drivertest
	b. Java -Dwebdriver.chrome.driver="chromedriver.exe" -Dwebdriver.gecko.driver="geckodriver.exe" -jar selenium-server-4.15.0.jar node
5. if needed alter the path to your chrome.exe at these lines from index.php and magicpin.php
	$options->setBinary('C:/Program Files/Google/Chrome/Application/chrome.exe');
6. create your cart on swiggy.com or android app.
7. goto localhost/seleniumdbw/index.php
	a. enter the phone number click submitph
	(minimise any windows opening)
	b. enter otp(after receiving) and click submitotp
	c. minimise any window that opens
8. done.



****extra****
latest:
http://localhost:4444/grid/console  (to check)
if conn. prblm check the ip add and correct nodeconfig file