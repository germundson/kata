**TDD KATA 3**

Create a Password verifications class called “PasswordVerifier”.

* Add the following verifications to a master function called “Verify()”
  - password should be larger than 8 chars
  - password should not be null
  - password should have one uppercase letter at least
  - password should have one lowercase letter at least
  - password should have one number at least
> Each one of these should throw an exception with a different message of your choosing
* Add feature: Password is OK if at least three of the previous conditions is true
* Add feature: password is never OK if item 1.4 is not true.
* Assume Each verification takes 1 second to complete. How would you solve  items 2 and 3  so tests can run faster?
  






