# Embrace Autism

## Code Institute - Milestone Project 1 (Testing)

![template](assets/readme/testing/i-am-responsive-all.png)

[Click here to view the Embrace Autism project live](https://embraceautism2.godaddysites.com/)

## Table of contents

1. [Testing](#testing)
    * [Screen sizes](#screen-sizes)
        * [Desktop homepage](#desktop-homepage)
        * [Mobile and tablet hompepage](#mobile-and-tablet-hompepage)
    * [Navigation bar](#navigation-bar)
        * [Full screen navigation bar](#full-screen-navigation-bar)
        * [Hamburger navigation bar](#hamburger-navigation-bar)
    * [Media Clips](#media-clips)
        * [Screenview media clips](#screenview-media-clips)
        * [Full size media clip 1](#full-size-media-clip-1)
        * [Full size media clip 2](#full-size-media-clip-2)
    * [User stories tested ](#user-stories-tested)
        * [Story 1](#story-1)
        * [Story 2](#story-2)
        * [Story 3](#story-3)
        * [Story 4](#story-4)
        * [Story 5](#story-5)
    * [W3C Markup Validation Service](#w3c-markup-validation-service)
        * [Homepage tested](#homepage-tested)
        * [About page tested](#about-page-tested) 
        * [Resources page tested](#resources-page-tested)
        * [Subscribe page tested](#subscribe-page-tested)
    * [W3C CSS Validation Service](#w3c-css-validation-service)
        * [CSS coding tested](#css-coding-tested)
    * [Web Browsers](#web-browsers)
        * [Google Chrome](#google-chrome)
        * [Apple Safari](#apple-safari)
        * [Microsoft Edge](#microsoft-edge)
        * [Mozilla Firefox](#mozilla-firefox)
    * [Testing responsiveness](#testing-responsiveness)
    * [Lighthouse testing](#lighthouse-testing)
        * [Desktop results](#desktop-results)
        * [Mobile results](#mobile-results)
    * [Issues found](#issues-found)
    * [Further testing](#further-testing)
    * [Bugs outstanding](#bugs-outstanding)

## Testing

### Screen sizes

* When testing the website on different screen sizes within Development Tools I made the decision to change the layout of the homepage for mobiles and tablets against laptop and desktop. The header, cover text and subscribe button is within the hero image on desktop and laptop. On smaller screens like mobile and tablet I decided to reduce the size of the image in order for the user to see the whole image clearly and then scroll down to see the header, cover text and subscribe button. This I believe makes better UX. I made sure the subscribe button a good size to give the user clear indication its there to click on.  

#### Desktop homepage

![template](assets/readme/testing/screen-sizes/homepage-desktop.png)

#### Mobile and tablet hompepage

![template](assets/readme/testing/screen-sizes/homepage-laptop-and-mobile.png)

### Navigation bar

* When testing the navigation bar on smaller screens this would appear as a hamburger menu (3 horizontal bars) which is what I wanted to achieve. I applied styling with a different colour and a bottom border to whichever page the user is currently on for good UX. The bottom border property on bigger screens worked well, however, on smaller screens with the hamburger menu, this didn't work as well. I therefore removed the bottom border property using media queries up to 991px which is the break point between the navigation menu changing format. This was tested on development tools on all break points up to 991px.  For reference, the colours highlighting the current page the user is on, remands in place. Therefore, users on smaller devices would still see what page they are on by the colour difference of the page titles.  

#### Full screen navigation bar

![template](assets/readme/testing/navigation-bar/full-screen-navigation-bar.png)

#### Hamburger navigation bar

![template](assets/readme/testing/navigation-bar/hamburger-navigation-bar.png)

### Media Clips

* I tested the media clips on different screen sizes, making sure that both clips loaded and played fully. I also checked that the 'allowfullscreen' attribute was active and working. I did this by viewing the site on laptop and mobile. Both tests were successful. I also checked to make sure the sound was working and again the testing was successful. 

#### Screenview media clips

![template](assets/readme/testing/media-clips/screenview-media-clips.png)

#### Full size media clip 1

![template](assets/readme/testing/media-clips/full-size-media-clip-1.png)

#### Full size media clip 2

![template](assets/readme/testing/media-clips/full-size-media-clip-2.png)

[Back to top ⇧](#embrace-autism)

### User stories tested

#### Story 1

I am a parent with a young child that's just been diagnosed with Autism. I need some general advice on what to do, now that I know what my child's condition is. I don't necessarily need specific advice at this stage, I just need to be pointed in the right direction.    

**EA Response - Embrace Autism offers useful links to charities that specialise in Autism all over the UK. These links can be found on the about, resources and subscribe pages. For example: Clicking the link to the National Autism Society will offer this parent the right step towards long term help and support. For Northern Ireland parents it would be best to click on the Autism NI charity which is also a link available on the website.** 
    
1. Go to the about, resource or subscribe page
1. On any of these pages the useful links can be found at the bottom in the form of clickable logos.
1. There is a small header above these logos stating 'Useful Links' as a guide.  

![template](assets/readme/testing/user-stories/useful-links-about-page.png)

![template](assets/readme/testing/user-stories/useful-links-resources-page.png)

![template](assets/readme/testing/user-stories/useful-links-subscribe-page.png)

#### Story 2

I have a teenage Son who has Autism. He only wants to play on his computer games every day. He hardly leaves the house and I'm concerned about his health and wellbeing. I would like some help with improving my Son's life style.  

**EA Response - There would be advice on the website to support this parent, often related to encouraging routines and good habits to get into.** 

1. Go to the resource page
1. On this page the user will see some advice and ideas to read. It's likely that there's some information that will help this parent as this is a very common issue for parents with an Autistic teenager.

![template](assets/readme/testing/user-stories/resources-information.png)

#### Story 3

I have five children. The two youngest have been diagnosed with Autism at different levels on the spectrum. I spend a lot of time with them which leaves little time left to spend with my older children and husband. I am in need of some support to free up more time whilst keeping all my children happy and entertained. 

**EA Response - by subscribing to the Embrace Autism mailing list, this parent will get regular updates with new ideas, tips and advice to help free up more time with all members of the family. The user can also take a look at the useful links to see whether one of the charities can offer some additional advice.** 

1. Go to the subscribe page
1. On this page the user can complete the form to subscribe on the mailing list for regular information sent via email. There's useful links at the bottom of this page for this user to click on as well.  

![template](assets/readme/testing/user-stories/subscribe-form.png)

![template](assets/readme/testing/user-stories/incomplete-subscribe-form.png)

![template](assets/readme/testing/user-stories/completed-subscribe-form.png)


#### Story 4

I work for a large Autism charity and see that Embrace Autism is offering advice and support from a parent's point of view with experience raising a child on the Autistic spectrum. How do I reach out to the founders of this website to provide more information and advice to help assist their site visitors?  

**EA Response - There is the option to contact Embrace Autism by email. To send an email the user can click the email envelope icon which can be found within the footer next to the social media icons on all pages. The user can click the icon to open a draft email within their device. The draft will have the pre-populated email address of info@embrace-autism.co.uk in the recipient section of the email. The user can then complete the email and when ready, click send.** 

1. This user can click on the email icon at the footer of any page to open up an email template draft to complete and send. 

![template](assets/readme/testing/user-stories/footer-email-icon.png)

![template](assets/readme/testing/user-stories/email-draft.png)

#### Story 5

I'm a teenager with Autism and have high-level sensory need. I find it difficult to wear a face mask when I'm in shops and with most shops insisting,people wear one, it's becoming very hard to go out. Is there anything I can do to make it easier for me when shopping?

**EA Response - This user can click any of the useful links to gain information. The user is likely to come across support relating to sensory conditions in older children who are more independent.** 

1. Go to the about, resource and subscribe page
1. On any of these pages the useful link for all three charities can be found at the bottom in the form of clickable logos. 

![template](assets/readme/testing/user-stories/useful-links-about-page.png)

[Back to top ⇧](#embrace-autism)

### W3C Markup Validation Service

The W3C Markup Validator was used to validate all coding on every HTML page of my project.

#### Homepage tested 
(1 error found)

1. The element 'a' must not appear as a descendant of the button element. 

    - **How I resolved this error:** Before adopting a div element in place of the button element, I tried placing the button element inside the 'a' element. The error still shown on W3C. I therefore, used the div element to resolve this issue. 

I re-tested the code on W3C Markup validator and no errors were found.

![template](assets/readme/testing/w3c-html/w3c-html-homepage.png)

#### About page tested 
(3 errors found)

2 were the same as I have 2 media clips on this page which shown the same error

1. Bad value true for attribute allowfullscreen on element iframe.
    - **How I resolved this error:** I checked the iframe element code from YouTube and seen that the 'true' value wasn't needed' This value was removed. I tested the media clips to make sure that they were still playing when on the page and that they can be played on full screen size as an option.

1. The element 'a' must not appear as a descendant of the button element.
    - **How I resolved this error:** Before adopting a div element in place of the button element, I tried placing the button element inside the 'a' element. The error still shown on W3C. I therefore, used the div element to resolve this issue. 

I re-tested the code on W3C Markup validator and no errors were found.

![template](assets/readme/testing/w3c-html/w3c-html-about-page.png)

#### Resources page tested 
(3 errors found)

2 were the same error

1. The element 'a' must not appear as a descendant of the button element.
    - **How I resolved this error:** Before adopting a div element in place of the button element, I tried placing the button element inside the 'a' element. The error still shown on W3C. I therefore, used the div element to resolve this issue. 

1. The aria-labelledby attribute must point to an element in the same document.
    - **How I resolved this error:** By matching the aria-labelledby to the id within the relevant element. 

I re-tested the code on W3C Markup validator and no errors were found.

![template](assets/readme/testing/w3c-html/w3c-html-resources-page.png)

#### Subscribe page tested 
(1 error found)

1. The aria-labelledby attribute must point to an element in the same document.
    - **How I resolved this error:** aria-labelledby matched the id in the relevant element, however, there was a capital letter at the start of the aria-labelledby wording. I made the adjustment from uppercase to lowercase which resolved this issue. 

I re-tested the code on W3C Markup validator and no errors were found.

![template](assets/readme/testing/w3c-html/w3c-html-subscribe-page.png)

 **HTML Testing completed**

 [Back to top ⇧](#embrace-autism)

### W3C CSS Validation Service

The W3C CSS Validator was used to validate all CSS used for my project.

#### CSS coding tested
(2 errors found)

1. subscribe-btn-about (error: Value Error : text-align none is not a text-align value : none). 
    - **How I resolved this error:** I removed the declaration in CSS and checked to make sure that the positioning and functionality is still working relevant to the #subscribe-btn-about (Subscribe button on about page). There were no issues with the button on the webpage.

1. subscribe-btn-resources (error: Value Error : text-align none is not a text-align value : none). 
    - **How I resolved this error:** I removed the declaration in CSS and checked to make sure that the positioning and functionality is still working relevant to the #subscribe-btn-resources (Subscribe button on resources page). There was no issues with the button on the webpage. 

Once both errors were fixed, I re-tested the code on W3C CSS valdiator and the message 
'Congratulations! No Error Found' came back.

![template](assets/readme/testing/w3c-css/w3c-css.png)

 **CSS Testing completed**

 [Back to top ⇧](#embrace-autism)

### Web Browsers

Testing was completed on different web browsers making sure that links worked and pages loaded properly. 

* I tested the site across the following web browsers

#### Google Chrome 
- The site was developed using Chrome and therefore testing was being done daily on this browser.

![template](assets/readme/testing/web-browsers/google-chrome/homepage-top.png)

![template](assets/readme/testing/web-browsers/google-chrome/homepage-bottom.png)

![template](assets/readme/testing/web-browsers/google-chrome/about-page-top.png)

![template](assets/readme/testing/web-browsers/google-chrome/about-page-bottom.png)

![template](assets/readme/testing/web-browsers/google-chrome/resources-page-top.png)

![template](assets/readme/testing/web-browsers/google-chrome/resources-page-bottom.png)

![template](assets/readme/testing/web-browsers/google-chrome/subscribe-page-top.png)

![template](assets/readme/testing/web-browsers/google-chrome/subscribe-page-bottom.png)
#### Apple Safari 
- I tested the site by opening it in Safari using an iPhone 12 and a MacBook. 

![template](assets/readme/testing/web-browsers/apple-safari/homepage-top.png)

![template](assets/readme/testing/web-browsers/apple-safari/homepage-bottom.png)

![template](assets/readme/testing/web-browsers/apple-safari/about-page-top.png)

![template](assets/readme/testing/web-browsers/apple-safari/about-page-bottom.png)

![template](assets/readme/testing/web-browsers/apple-safari/resources-page-top.png)

![template](assets/readme/testing/web-browsers/apple-safari/resources-page-bottom.png)

![template](assets/readme/testing/web-browsers/apple-safari/subscribe-page-top.png)

![template](assets/readme/testing/web-browsers/apple-safari/subscribe-page-bottom.png)

#### Microsoft Edge 
- I downloaded this browser, logged into my Gitpod and checked all four webpages across all screen sizes. 

![template](assets/readme/testing/web-browsers/microsoft-edge/homepage-top.png)

![template](assets/readme/testing/web-browsers/microsoft-edge/homepage-bottom.png)

![template](assets/readme/testing/web-browsers/microsoft-edge/about-page-top.png)

![template](assets/readme/testing/web-browsers/microsoft-edge/about-page-bottom.png)

![template](assets/readme/testing/web-browsers/microsoft-edge/resources-page-top.png)

![template](assets/readme/testing/web-browsers/microsoft-edge/resources-page-bottom.png)

![template](assets/readme/testing/web-browsers/microsoft-edge/subscribe-page-top.png)

![template](assets/readme/testing/web-browsers/microsoft-edge/subscribe-page-bottom.png)

#### Mozilla Firefox 
- I downloaded this browser, logged into my Gitpod and checked all four webpages across all screen sizes.

![template](assets/readme/testing/web-browsers/mozilla-firefox/homepage-top.png)

![template](assets/readme/testing/web-browsers/mozilla-firefox/homepage-bottom.png)

![template](assets/readme/testing/web-browsers/mozilla-firefox/about-page-top.png)

![template](assets/readme/testing/web-browsers/mozilla-firefox/about-page-bottom.png)

![template](assets/readme/testing/web-browsers/mozilla-firefox/resources-page-top.png)

![template](assets/readme/testing/web-browsers/mozilla-firefox/resources-page-bottom.png)

![template](assets/readme/testing/web-browsers/mozilla-firefox/subscribe-page-top.png)

![template](assets/readme/testing/web-browsers/mozilla-firefox/subscribe-page-bottom.png)


### Testing responsiveness

* I manually tested the site on different screen sizes by using Development tools throughout the project and once the site was finished and deployed.

### Lighthouse testing 

[Back to top ⇧](#embrace-autism)

#### Desktop results

![template](assets/readme/testing/lighthouse/desktop-lighthouse-results.png)

#### Mobile results
![template](assets/readme/testing/lighthouse/mobile-lighthouse-results.png)

I checked the details of this report and seen that it was the 'Largest Contentful Paint' score that was the main issue. 
[Further research into this is required]

[Back to top ⇧](#embrace-autism)

### Issues found
* I wanted to include a Modal message when the form on the subscribe page is submitted successfully. Adding the code didn't work - assistance from my Mentor (TBC)

* I Used DevTools throughout my project to make sure that all device screen sizes were taken into consideration. I took some time to complete media queries across all pages, however, certain elements on certain screen sizes still didn't look right. I will be working on this more during further projects to perfect the skill between using bootstrap and media queries.

[Back to top ⇧](#embrace-autism)

### Further testing
* I was testing the development of the site on my iPhone throughout this project to make sure it was mobile first responsive. I felt this really helped my stay focused as the site was coded on MacBook. 

* I tested all three external links to the three different charity organisations on all pages relevant. All links open in a different web browser tab for good UX. This was tested across all web browsers mentioned above. 

* I also made sure that the source text external link in red on the about page worked successfully and that it opened in a new web browser as well. 

* All icons in the footer were tested across all pages to make sure that the links worked by taking a user to the right social media landing page and that the link would open an external page in a new web browser tab. 

* The email icon was tested successfully with a email draft opened as it should do with the pre-populated email address info@embrace-autism.co.uk in the recipient section. 

* I tested all internal links across all four pages using the above web browsers mentioned. The links tested were the logo text at the top left of the header, the navigation menu at the top right of the header, all SUBSCRIBE FOR FREE and SUBSCRIBE buttons across all pages, and the resources and subscribe text links on the about page. 

* I tested the form on the subscribe page: -

    1. Contact form:
        * Go to the "Subscribe" page
        * I clicked the submit button with all fields empty which verified that an error message about the required fields appeared. 
        * I attempted to submit the form with an invalid email address which verified that the relevant error message appeared.
        * I submitted the form with all fields correctly filled in and this verified that the form works with an 'alert' message appearing. For reference the message that appears says 'Thank you! You will receive your first newsletter within the next 48 hours that a success message appears'.

[Back to top ⇧](#embrace-autism)

### Bugs outstanding

Lighthouse testing for mobiles - performance score is low and needs to be looked into. All i know is that the Largest Contentful Paint (LCP) is courses the main issues to this score. A couple of sites i visiting to look into this were <a href="https://imageengine.io/" target="_blank">Image Engine</a> and <a href="https://nitropack.io/blog/post/reduce-largest-contentful-paint-lcp" target="_blank">Nitro Pack</a> 



[In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    * Go to the "Contact Us" page
    * Try to submit the empty form and verify that an error message about the required fields appears
    * Try to submit the form with an invalid email address and verify that a relevant error message appears
    * Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.]

[Back to top ⇧](#embrace-autism)