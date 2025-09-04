TC-005 — Email case-insensitivity
Preconditions: DB has John.Doe@example.com, valid password
Steps: Enter john.doe@EXAMPLE.COM with valid password, click Login
Expected Result: Successful login; normalized email stored in session