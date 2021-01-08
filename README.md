# Shortest way to Check Card details

## ValidatingCardNumberAndCVV
* Store card details in a database, 
* basic validation like validating card number and expiration date



### Logic

* Length of the Name must be greater than 5
* Card is vaild upto maximum 10 years from the card issued month 
* validateCardNumber(cardNumber.val())  ->Given Condition in question -> **card number is equal to 16 digit** using payform interface
* validateCardCVC(CVV.val())  ->   using payform interface
* payform.parseCardType()   -> is used to change the types of card in mastercard, amex and visa.

### Testing Vaild Temp cards [ Ref: https://www.vccgenerator.com/]
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
   
