# darkly
Darky 42!


# 1 - Forgot Password html change
  1. Sign in and forgot password
  2. Email is in hidden html
  3. edit email to anything
  4. get flag

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
