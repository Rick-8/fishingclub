# BDA Fishing

BDA Fishing website is for people that want to fish, shop or relax around the lakes and rivers the club manages.

Users of the site will instantly be aware on the page opening up, what they are looking for with a simple and easy way to navigate pages. it has 3 sections aimed at the what the club offers, the community who fish and use the waters, and how anyone can leave their details for a club member to contact them to provide legendary customer service.

![Screenshot of the websites homepage on different devices](assets/images/multi-screen-mock2.jpg) 

## Features

* Favicon
  - using the site Favomatic (https://favicomatic.com/) I was able to make my own Favicon from a cropped picture I sourced from pexels.com

* Navigation Bar

    - Shown at the top of all three pages, and each page having an identical theme.
    - Smaller screens, the navigation can be accessed to the top right of the screen by tapping the burger Icon and the page links appear below in a toggled menu.
    - On larger screen sizes the links appear in the header neatly displayed to the left of the screen.
    - The main club text is also a home page link back to the index page.

* The Header

    - The header sits at the top of all three pages, containing the nav links in the format described above.
    - The Club has no logo, but uses google fonts, to style a H1 heading to give it a better look.

 ![Screenshot of the websites homepage on different devices](assets/images/header-shot.png) 


 * The Home page

    - This is the landing page, with a stunning view of the lake overlooking the boats its sure to get any angler wanting to join!


    ![Screenshot of the websites homepage on different devices](assets/images/main-content-index.png) 

    - This section below shows very simply how and what the club offers and the benefits of fishing, 
    - Including one of the clubs star catches, demonstrating a typical fish size on one of the waters, offering the potential new member or day ticket holder the chance and wonder of netting that an exciting oppertunity!
    - The bottom of this section show the venues available to fish and the shop. The shop headder is in white so it stands out, and creates a visual aid then linked to from the enquireis/signup page. 

       ![Screenshot of the websites homepage on different devices](assets/images/love-fishing-main-two.png) 


* The Footer

    - This section has relivent links to Facebook, Instagram and You Tube.
    - The links open in a new browser tab, and allow the user to interact with the club community and watch related content.


  ![Screenshot of the websites homepage on different devices](assets/images/footer-p1.png) 


* The Photos Page

    - The photos page is there for the club to post key photos that help the potential member gain a real world experience in what to expect.
    - The page also helps the exsisting members display their acomplisments, and something to be proud of!
    - No writing was used in this page, to keep the page true to its inteded purpose.
    - Pictures are responsive on diffrent sizes depending on the available realestste.


    ![Screenshot of the websites homepage on different devices](assets/images/p1-photos.png) 

* The Enquiries / Signup Page

  - In this section are two easy to read and short text explinations with the main text seperated from the form to fill out, to give a simple focus to the page.
  - The form contains placeholder text, giving an example of what data the user should input.
  - Both sections are basic with no distractions, it is clear on what the user is expected to do, if they are interested in taking their interest to the next level in becoming a member, and joining the club.


![Screenshot of the websites homepage on different devices](assets/images/signup-page-p1.png) 

### Features left to impliment

 - I would love to add maps of the waters to aid in the allure of joinging the club and assist members in finding the right spot.
 - I would also like to add another page for a club shop, selling bait and tackle online, including new memberships with an online pay section.
 - Finally a sign in members area where members can sign in and and access their profile, Specific Venue details like gate codes and a booking section to regulate how many anglers can fish at one time, to protect the fish. Wich also has a news or updates section to keep members uptodate with club news.


## Testing

I ran my page through Lighthouse to ensure my site is easy to read an nicely accessable.

![Screenshot of the websites homepage on different devices](assets/images/lighthouse-score-p1.png) 

- I tested my site on Chrome, Safari and Firefox, and it works well on these browsers.
- I tested all links on pages to make sure they were working
- I tested all external links to make sure they work, and link in a separate tab to the correct site.
- I tested that the form works, and submits the all the information correctly.

![Screenshot of the websites homepage on different devices](assets/images/form-submit.png) 

* HTML 
  - I ran the code through the checker and found 1 concern regarding the Phone number field on the Enquiries page, and some browsers might not support this functition.
  - The concern was addressed by placing * next to the name and email labels, and puting a key at the bottom.
  - I also reaserched the type="tel" on https://www.w3schools.com/tags/att_input_type_tel.asp which showed the following browsers that support it, and felt confident the risk was very low.
  
  ![Screenshot of the websites homepage on different devices](assets/images/tel-type-browser.png) 
 
* CSS
  - No errors were found when the code was run through the CSS validator 

  ![Screenshot of the websites homepage on different devices](assets/images/css-validation.png)

## Bugs
  - being my first ever page, there were a few bugs, and "opertunities to learn" along the way, which I spent time reaserching and spoke to tutor support for help and advice a could of times. but to name a couple,
  - getting the pics on the pictures page to fit toghter nicely was a challenge, but after speaking with a tutor and my mentor I discovered that the picture sizes were very big, and needed scaling down, which I was able to do easily using the windows paint function, and using flex-box got them lined up nicely.
  - There were various minor errors, that I was quickly able to discover, because I was running my code through both validator services at periodic points, correcting things using the correct heading tags in the expected places, correctly spacing the content out.
  - The imgage for the sign up page was fixed, and not relative and did not load when deployed. This was easily fix and a bux fit update done, upon discovering it.


## Deployment

* Version Control

  - The site was created using the Gitpod editor and pushed to the remote fishing club repository on Github.com
  - Git commands were used reguraly during the construction of the club website using the following Git commands
  - git add .  - to add files to the staging area before being commited
  - git commit -m "commit title" - to commit a file to the queue ready for the final process.
  - git push - used to send the comitted files to the Github repository.

* Deployment to Github pages

  - I used the follwing steps to deploy using the Github pages as follows
  - Once inside the repository, I clicked on the settings tab
  - I then went to the pages section
  - Making sure the main branch was selected I then clicked on save and the page url was created.
  - Please click here to find the live site [BDA Fishing](https://rick-8.github.io/fishingclub/)

* Using Gitpod

  - To set up my working IDE I loged in to Gitpod and navigated to the workspaces section
  - Clicking on new workspace and in putting the repository url, 
  - The IDE was created.

## Design - Wireframes

 - Making the site I used the mobile first method in developing. I used [wireframe](https://balsamiq.com/) to plot a general layout both on Mobile first and being responsive on bigger screens.

* Mobile screens from 280px
  - ![Screenshot of the websites homepage on different devices](assets/images/wireframes-android.png)

 * Larger screens with a min-width of 768px
  - ![Screenshot of the websites homepage on different devices](assets/images/wireframes-desktop.png)


## Credits
- I would like give a special thank you to my mentor for his help and support.
- I would also like to credit the Love Running project walkthrough, for inspiration on the layout of the header, footer and basic page design.

### Content
 - The Icons in the header, footer and on some heading titles were imported from [Font Awsome](https://fontawesome.com/)
 - The social media links in the footer, are the real logo's from You Tube, Facebook and Instagram.
 - The favicon used for this website was created from a Picture of a float in the water taken from [pexels.com](https://www.pexels.com/) Croped and uploaded to [favomatic](https://favicomatic.com/) which made me a full free set, this was then uploaded to gitpod, and implimented into my project.
 
### Media

 - The Images listed below were sourced from [pexels.com](https://www.pexels.com/) 
  - All 3 pictures on The Index / Landing page
  - Three pictures from the club photos page 
  - The background picture on the Enquires page
  - 6 of the photos were taken from my private collection, (made for this project by myself)
  

