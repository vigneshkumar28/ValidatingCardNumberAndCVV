# Shortest way to Check Card details

## ValidatingCardNumberAndCVV
* Store card details in a database, 
* basic validation like validating card number and expiration date


### Using
* Firebase
* HTML, Java script and css
* Payform interface


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
   
   
 # OutPut
 
 ## Empty Layout
 ![Empty Layout](https://github.com/vigneshkumar28/ValidatingCardNumberAndCVV/blob/main/Output_Images/intro.PNG )
 
 ## Empty database
 ![Empty database](https://github.com/vigneshkumar28/ValidatingCardNumberAndCVV/blob/main/Output_Images/Empty%20database.PNG)
 
 ## Card Number 1
 ![Card Number 1](https://github.com/vigneshkumar28/ValidatingCardNumberAndCVV/blob/main/Output_Images/Card%20number%201.PNG)
 
 ## Card 1 stored in firebase database
 ![Card 1 stored in firebase database](https://github.com/vigneshkumar28/ValidatingCardNumberAndCVV/blob/main/Output_Images/card%201%20stored%20in%20firebase.PNG)
 
 ## Card Number 2
 ![Card Number 2](https://github.com/vigneshkumar28/ValidatingCardNumberAndCVV/blob/main/Output_Images/Card%20number%202.PNG)
 
  ## Card 2 stored in firebase database
 ![Card 2 stored in firebase database](https://github.com/vigneshkumar28/ValidatingCardNumberAndCVV/blob/main/Output_Images/card%202%20stored%20in%20firebase.PNG)
 
  ## Card Number 3
 ![Card Number 3](https://github.com/vigneshkumar28/ValidatingCardNumberAndCVV/blob/main/Output_Images/Card%20number%203.PNG)
 
  ## Card 3 stored in firebase database
 ![Card 3 stored in firebase database](https://github.com/vigneshkumar28/ValidatingCardNumberAndCVV/blob/main/Output_Images/card%203%20stored%20in%20firebase.PNG)
 
 ## Wrong card Number
 ![Wrong card Number](https://github.com/vigneshkumar28/ValidatingCardNumberAndCVV/blob/main/Output_Images/Wrong%20card%20number.PNG)
 
 ![alt text](http://url/to/img.png)
 
 ![alt text](http://url/to/img.png)
 
 ![alt text](http://url/to/img.png)
