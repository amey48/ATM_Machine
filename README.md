# ATM_Machine


In this assignment you will create a program that allows a user to do the following:

1)	Create a bank account by supplying a user id and password.
2)	Login using their id and password.
3)	Quit the program.

Now if login was successful the user will be able to do the following:

1)	Withdraw money.
2)	Deposit money.
3)	Request balance.
4)	Quit the program.

If login was not successful (for example the id or password did not match) then the user will be taken back to the introduction menu.

This is what your program in action will look like:

Hi! Welcome to Mr. Zamar’s ATM Machine!

	Please select an option from the menu below:

l  -> Login
c -> Create New Account
q -> Quit

> l

Please enter your user id: 12
Please enter your password 2345

******** LOGIN FAILED! ********

Please select an option from the menu below:

l  -> Login
c -> Create New Account
q -> Quit

> c

Please enter your user name: 12
Please enter your password: 2345

Thank You! Your account has been created!

l  -> Login
c -> Create New Account
q -> Quit

> l

Please enter your user id: 12
Please enter your password: 2345

Access Granted!

d 	-> Deposit Money
w -> Withdraw Money
r  -> Request Balance

> d

Amount of deposit: $20

d 	-> Deposit Money
w -> Withdraw Money
r  -> Request Balance

> r

Your balance is $20.

d 	-> Deposit Money
w -> Withdraw Money
r  -> Request Balance

> w

Amount of withdrawal: $2.5

d 	-> Deposit Money
w -> Withdraw Money
r  -> Request Balance

> r

Your balance is $17.5.

d 	-> Deposit Money
w -> Withdraw Money
r  -> Request Balance

> q

Thanks for stopping by!
