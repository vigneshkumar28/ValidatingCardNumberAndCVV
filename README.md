# Check Card details

# Question

Design a webpage to capture card details. Include basic validation like validating card number

and expiration date. Also include a field for name on card and cvv.

Store card details in a database and show success message when stored.

1) You are allowed to use any frontend technologies. React would be preferred but

html,css and javascript will also do. Other frameworks you can consider - Angular, Vue

2) You can use any backend and any database. Most easy would be Firebase. You can

also consider any backend language with in-memory database. Most recommended

would be node.js with express and mongodb.

3) Regarding the validation for credit card number. It needs to be all numbers and should

be 16 digits long. Provide appropriate error message in line using javascript.

4) Expiration date can be input text or dropdown.

# Solution

## ValidatingCardNumberAndCVV
* Store card details in a database, 
* basic validation like validating card number and expiration date


### Using
* Firebase
* HTML, Java script and css
* Payform interface
* 000webhostapp
* vccgenerator.com


### Logic

* Length of the Name must be greater than 5
* Card is vaild upto maximum 10 years from the card issued month 
* validateCardNumber(cardNumber.val())  ->Given Condition in question -> **card number is equal to 16 digit** using payform interface
* validateCardCVC(CVV.val())  ->   using payform interface
* payform.parseCardType()   -> is used to change the types of card in mastercard, amex and visa.

### Testing Vaild Temp cards [ For More Valid Cards Ref: https://www.vccgenerator.com/]
1)
* CARD BRAND : VISA
* CARD NUMBER : 4201348489345670   
* Name : Suriya Vijay
* Exp:07/2023
* CVV: 451

2)
* CARD BRAND : MASTERCARD
* CARD NUMBER : 5353402679633198
* Name : Abi suriya
* EXPIRY : 03/2024
* CVV : 791
  
 3)
 * CARD BRAND : AMERICAN EXPRESS
 * CARD NUMBER : 377398429462024
 * Name : Vignesh Kumar 
 * CVV/CVV2 : 733
 * EXPIRY (MM/YYYY) : 10/2025
   
   
  #### Facing any diffcuilt in runing website.Please Download the this folder as zip and extract, Run the index.html file in browser
   
   
 # OutPut
 
 ## 1) Layout
 ![Empty Layout](https://github.com/vigneshkumar28/ValidatingCardNumberAndCVV/blob/main/Output_Images/intro.PNG )
 
 ## 2) Created New Empty Real time Database
 ![Empty database](https://github.com/vigneshkumar28/ValidatingCardNumberAndCVV/blob/main/Output_Images/Empty%20database.PNG)
 
 ## 3) Card Number 1
 ![Card Number 1](https://github.com/vigneshkumar28/ValidatingCardNumberAndCVV/blob/main/Output_Images/Card%20number%201.PNG)
 
 ## 4) Card 1 stored in firebase database
 ![Card 1 stored in firebase database](https://github.com/vigneshkumar28/ValidatingCardNumberAndCVV/blob/main/Output_Images/card%201%20stored%20in%20firebase.PNG)
 
 ## 5) Card Number 2
 ![Card Number 2](https://github.com/vigneshkumar28/ValidatingCardNumberAndCVV/blob/main/Output_Images/Card%20number%202.PNG)
 
  ## 6) Card 2 stored in firebase database
 ![Card 2 stored in firebase database](https://github.com/vigneshkumar28/ValidatingCardNumberAndCVV/blob/main/Output_Images/card%202%20stored%20in%20firebase.PNG)
 
  ## 7) Card Number 3
 ![Card Number 3](https://github.com/vigneshkumar28/ValidatingCardNumberAndCVV/blob/main/Output_Images/Card%20number%203.PNG)
 
  ## 8) Card 3 stored in firebase database
 ![Card 3 stored in firebase database](https://github.com/vigneshkumar28/ValidatingCardNumberAndCVV/blob/main/Output_Images/card%203%20stored%20in%20firebase.PNG)
 
 ## 9) Wrong card Number Notifcations
 ![Wrong card Number](https://github.com/vigneshkumar28/ValidatingCardNumberAndCVV/blob/main/Output_Images/Wrong%20card%20number.PNG)
 
 # 10) All 3 Cards are successfully stored in Firebase realtime database
 ![ALL cards in Firebase](https://github.com/vigneshkumar28/ValidatingCardNumberAndCVV/blob/main/Output_Images/ALL%203%20cards%20in%20db.PNG)
 
 # Hosted in https://cardcheckervigneshkumarr.000webhostapp.com/
 ![Hosted in Webhost website](https://github.com/vigneshkumar28/ValidatingCardNumberAndCVV/blob/main/Output_Images/Hosted%20in%20000webhost.PNG)
 
 
<h2 align="center"> Thanks for Visiting! :innocent::smiley:</h2>
