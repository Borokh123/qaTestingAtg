TC-013 — SQL injection in email
Preconditions: –
Steps: Enter ' OR 1=1 -- @x.com + any password, click Login
Expected Result: Login denied; no error leakage; app unaffected