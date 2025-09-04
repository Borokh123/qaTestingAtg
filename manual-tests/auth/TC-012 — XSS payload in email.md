TC-012 — XSS payload in email
Preconditions: –
Steps: Enter <script>alert(1)</script>@x.com + valid password, click Login
Expected Result: Validation error; UI safely escapes input; no script runs