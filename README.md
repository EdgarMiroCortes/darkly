# darkly
Darky 42!


# 1 - Forgot Password html change
  1. Sign in and forgot password
  2. Email is in hidden html
  3. edit email to anything
  4. get flag
  5. Flag = 1d4855f7337c0c14b6f44946872c4eb33853f40b2d54393fbe94f49f1e19bbb0

# 2 - ?
  1. WGET 10.11.249.65
  2. Read robots.txt
  3. see endpoint /whatever
  4. access 10.11.249.65/whatever
  5. download file and see root:password

# 3 - ?
  1. Copyright links to a page
  2. page URL is a hash

# 4 - I AM ADMIN COOKIE
  1. Inspect element > Application > Cookies
  2. I_am_admin cookie is "false" in md5
  3. encrypt "true" in md5 (b326b5062b2f0e69046810717534cb09)
  4. Flag = df2eb4ba34ed059a1e3e89ff4dfc13445f104a1a52295214def1c4fb1693a5c3

# 5 - Feedback form Xss
  1. In feedback page
  2. xss attack
  3. <script>alert('XSS!')</script>
  4. Flag = 0fbb54bbf7d099713ca4be297e1bc7da0173d8b3c21c1811b916a3a86652724e
