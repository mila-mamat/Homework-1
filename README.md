# First Homework

For this homework, our task is to refactor an existing webpage to make it cleaner.


## Getting Started

I'm not quite sure how others are going to access my repository, so here is the SSH key if needed:  git@github.com:mila-mamat/homework-1.git

### Contents
* index.html (html required for homework)
* index-v2.html (html for responsive design)
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
      
## What are the changes?
1. Webpage title is changed from website to Horiseo Homepage.

2. Comments are added in both html and css file to give extra tips on structure.

3. changed the tag names from  < div> to  < nav>, < header>,  < main> ( < section>), < aside> and  < footer>
    * The original  < div> tags, replaced above, used class names like "header","footer" to style in css. Thus the class selectors in CSS is replaced by the element selectors accordingly.
  
  
4. Removed the unnecessary classes in  < main> and  < aside>, like "search-engine-optimization", "benefit-lead",etc. 
    * Summarized the CSS codes under main section{} and aside div{}
    * IDs are untouched as navigation bar on top is linked through IDs
    * original html file didn't add ID to the first section. Fixed. 
  
5. Some properties used throughout the webpage, like font color and font family, are summarized on the top under body{}


## What went wrong?
### For homework: 
I dont know why, the font size of my navigation bar is 20px as the original one, but it visually looks bigger to me. Will double check later.

### For responsive design:
For the screen size smaller than 970, the  < aside> content is stacked under < main>. But I cannot change the margin of it and make its right border in align with the < main>. NEED HELP!!!



## What other changes I would like to make?
1. <s>The width of header,hero img doesnt match up with the rest. Looks weird. Want to add margins to header and hero img.</s> Done.
2. <s>Wanna try my teeth on responsive website design.</s> Done.
3. For the smallest screen, the naviation bar is stacked up on the top right corner, and when the screen is small enough, navigation bar would overlap with the logo. Gonna do some research and change the navigation bar to a dropdown list.
4. Might want to add a comment or email me box on the bottom to see how js works.



## New findings
I was not quite sure about when to use float, when to position. I found their difference when I was trying to reshape the < aside> into the same style with < main> (small screen).

For < main>, float can do the work as the workflow of it is < img>, < h2>, < p>. 
But for < aside>, the workflow is < h3>, < img>, < p>. Can't float the img to the left side of the < h3> and < p>. Position, however, ignores te workflow, and can move around the blocks to anywhere I want. 

My understanding is, flow is easy to use, while position can do complicated designs with detailed measurement. 




