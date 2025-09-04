TC-002 Login check with empty data
Steps:
1.Go to https://atg.kh.ua/c/index.php?route=account/login
2.Do not enter your login and password (leave the fields empty).
3.Click “Log in.”
Expected result:
The system does not allow the user to log in and displays an error message (“Enter email/password”).
Technique: Equivalence partitioning

Why: Empty data belongs to a separate equivalence class (different from valid and invalid data), which always results in authorization failure.