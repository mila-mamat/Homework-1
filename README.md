# First Homework

For this homework, our task is to refactor an existing webpage to make it cleaner.





## Contents
* **index.html (html required for homework)**
* **index-v2.html (html for responsive design)**
* assets folder
   * CSS folder
      * style.css (css required for homework)
      * style-v2.css (css for responsive design)
   * images folder
      * brand-awareness.png
      * cost-management.png
      * digital-marketing-meeting.jpg
      * lead-generation.png
      * online-reputation-management.jpg
      * search-engine-optimization.jpg
      * social-media-marketing.jpg
      
      
      
## What are the changes made in Homework?
1. Webpage **title** is changed from website to Horiseo Homepage.

2. **Comments** are added in both html and css file to give extra tips on structure.

3. changed the **tag names** from  < div> to  < nav>, < header>,  < main> ( < section>), < aside> and  < footer>
    * The original  < div> tags, replaced above, used class names like "header","footer" to style in css. Thus the class selectors in CSS is replaced by the element selectors accordingly.
  
  
4. Removed the **unnecessary classes** in  < main> and  < aside>, like "search-engine-optimization", "benefit-lead",etc. 
    * Summarized the CSS codes under main section{} and aside div{}
    * IDs are untouched as navigation bar on top is linked through IDs
    * original html file didn't add ID to the first section. Fixed. 
  
5. Some properties used throughout the webpage, like font color and font family, are summarized on the top under body{}





## What other changes I would like to make?
1. <s>Wanna try my teeth on responsive website design.</s> Done.
2. Might want to add a comment or email me box on the bottom to see how Bootstrap works.
3. The current style-v2 is too messy. Try rewrite it using Bootstrap.




## Thoughts
1. I was not quite sure about when to use float, when to position. I found their difference when I was trying to reshape the < aside> into the same style with < main> ( in small screen).

  For < main>, float can do the work as the workflow of it is < img>, < h2>, < p>. 
  But for < aside>, the workflow is < h3>, < img>, < p>. Can't float the img to the left side of the < h3> and < p>. Position, however, ignores te workflow, and can move around the blocks to anywhere I want. 

  My understanding is, flow is easy to use, while position can do complicated designs with detailed measurement. 



2. When element { width:100% } , any margin would be added on top of the width, pushing the element to the side. 



