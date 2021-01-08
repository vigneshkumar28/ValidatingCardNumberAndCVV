# Shortest way to Check Card details

## ValidatingCardNumberAndExpDate
* Store card details in a database, 
* basic validation like validating card number and expiration date



### Logic

* Length of the Name must be greater than 5
* validateCardNumber(cardNumber.val())  ->Given Condition in question -> **card number is equal to 16 digit** using payform interface
* validateCardCVC(CVV.val())  ->   using payform interface
* payform.parseCardType()   -> is used to change the types of card in mastercard, amex and visa.
