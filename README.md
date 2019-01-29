# CSE135PA1

1. Employ password protection
   - We set authentication whith .htpasswd and .conf
   - The valid-name and valid-password in pdf which is submitted on GradeScope.
   
2. Have a static team page that indicates your name and/or team members, emails, etc.
   - The main page is index.html.
   - In this page we list name and e-mail of teammates.
   - Here is a bootstrap e-mail validation.
   
3. Use custom error pages
   - We set one 403 error page and one 404 error page.
   - For each page we changed the default content.
   
4. Have a favicon 
   - We set a favicon using url provided online.
   - Related code is in index.html, head part.
   - We think A is the best letters for student, so we pick a red A.
   
5. Have a robots.txt file
   - We create a robots.txt.
   - Inside we block all robots to let them can't search our website.
   
6. Deploy from Github
   - We connect our github repo and digital ocean server.
   
7. Log Properly
   - We upload the origin log files.
   - We also use goAccess program to create a log report and upload them.(apache_result.csv & access.html)
   
8. Compress Textual Content
   - We configure mod_gzip to compress our web content.
   - But may because our content is limited, so the chenge is not obvious.

9. Obscure server identity
   - The server infomarion are protected.
   - You can't see apache or nginx in website header.
   
10. Run PHP
   - We write a php script. (phpinfo.php)
   - You can check php information in browser.
   
11. Deliver Clean URLS
   - When you want to check php information in step 10, when you type /phpinfo.php, it will become /phpinfp.
   - We use the mod_rewrite to let url can be cleaned.
