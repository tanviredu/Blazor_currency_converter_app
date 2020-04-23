1) we take fromCurrency to store a currency name
2) toCurrency store a target currency name
3) take the fromValue to take the input from the user and init with 1 by default
4) and we take the toValue for converted result

5) also declare  IEnurable which is like the list and it is iterable to store all the Currency name
6) and we also set the default currency in the first render


7)in the html we bind the input to the fromValue to get the value
then we select the currency from a dropdown menu
that is binded with the IEnumrable list

8)then same thing from the toCurrency

9)and in the middle we write @toValue to show the converted value

10) make two function getRate() to set the rate
11) and convert() to convert the value

12) and we add the convert() method to OnInitialized() so that it can be accessable

13)and onclick we execute the ans which is binded with the conver()

15) and we add this app to  index.razor page


** in this app there is no work for html form "name property"
** and it is client side app







