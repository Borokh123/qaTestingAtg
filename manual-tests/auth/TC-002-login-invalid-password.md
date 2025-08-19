Authorization — invalid php
ID: TC-002
Title: Login check with invalid password

Steps:
1.Go to https://atg.kh.ua/c/index.php?route=account/login
2. Enter a valid email address and an incorrect password.
3. Click “Log in.”
Expected result: “Incorrect password or email” .

Technique: Equivalence classes + negative testing

Why: It is necessary to ensure that the system responds appropriately to incorrect data.