# eth_beginner

Contract will have public variables that store the details about your coin (Token Name, Token Abbrv., Total Supply)
Contract will have a mapping of addresses to balances (address => uint)
There will be a mint function that takes two parameters: an address and a value. 
The function then increases the total supply by that number and increases the balance 
of the “sender” address by that amount
Contract will have a burn function, which works the opposite of the mint function, as it will destroy tokens. 
It will take an address and value just like the mint functions. It will then deduct the value from the total supply 
and from the balance of the “sender”.
Lastly, burn function should have conditionals to make sure the balance of "sender" is greater than or equal 
to the amount that is supposed to be burned.
