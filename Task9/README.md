1 - Passwords should not be stored as plain text because if the database is leaked,
anyone can see all user passwords. 

2 - Raw SHA-256 is not a good choice for passwords because 
it is very fast and makes brute force attacks easier. 

3 - Salt is used to make the same password generate different
hashes for different users. 

4 - Salt is stored together with the hash, while pepper is a secret
value stored separately from the database.


5 - Authentication is the process of checking who the user is, 
while authorization checks what the user is allowed to access. 

6 - Hiding a link in a view is not enough because a user can
still manually enter the URL in the browser.


7 - Showing a message like "there is no such user" can be a problem
because it helps attackers discover which accounts exist in the system.


Olena Ch. s32774