# Everest Enthusiast

[View the live project here](https://hen0678.github.io/Everest-Enthusiast/)

## Overview
Everest Enthusiast is a website for those fascinated with the highest mountain on earth - Mount Everest and who want to learn more. For decades this mountain nestled in the Himalayas in the remote country of Nepal has captured the imagination of mankind. Even today, with the advent of modern day travel the mountain still holds an air of mystery. 

As the website grows new content will be added, including more interesting facts, high quality images and a detailed timeline of key events. There will also be video content added which will capture iconic areas of the mountain, such as the various base camps, the Hilary step and the summit itself. For those who aspire to one day climb the mountain, or simply basecamp there will be a section dedicated to the type of kit required. 

![overview-page](assets/media/responsive-overview.png)

## User Experience (UX)  

### First Time Visitors
As a First Time visitor, I want to:
* Easily understand the main purpose of the site.
* I want to be able to easily navigate throughout the site to find content.
* I want to learn some interesting facts about Mount Everest.
* I want to see high quality images.

### Returning Visitors
As a returning visitor, I want to:
* Check the navigation bar to see what new pages have been created.
* Check what new interesting facts have been added.
* Check what new images have been added.

### Frequent User 
* As a frequent user, I want to be able to Subscribe easily to the newsletter to I am the first to be made aware when new content has been added.

## Features

### Header and navigation bar
This features links to the three pages of the site, namely:
1. Home
2. Interesting Facts
3. Sign Up 

The navigation bar is responsive, so as the screen size gets smaller the links change to a burger dropdown icon. The format and layout are the same across all three pages which creates a consistent look and feel for the user.

The colour used for the navigation is "whitesmoke" which is fitting with the image of Mount Everest which has swirling white cloud around the peak.

The same header is used on each page of the website.

#### Full screen
![nav-bar-max](assets/media/nav-bar-max.png)

#### Small screen
![nav-bar-min](assets/media/nav-bar-min.png)

### Home page
#### Top section
The home page has an awe-inspiring image of the top of Mount Everest with the cloud swirling around the peak. The image is overlaid with text proclaiming the top of the mountain as the roof of the world.

![Everest-peak](assets/media/image-of-everest.png)

#### Lower section

The bottom half of the page has a title of "The Allure of Everest". There is then a brief overview to draw the viewer in. There are also links to the Interesting Facts and Sign Up pages. 

![home-page-text](assets/media/allure-image.png)

### Footer
The footer has the same colour as the header. There are also links to various social media websites which open on new tabs. The same footer is used on each page of the website.

![footer](assets/media/footer.png)

### Interesting Facts page
On this page there are a number of interesting facts about Mount Everest, ranging from the various names the mountain as to the modern day queues of climbers looking to summit the peak. The facts will hopefully include things that a lot of people will not be aware of.

Alongside some interesting facts there are some high quality images. 

![interesting-facts](assets/media/busy-mountain.png)

### Sign Up page
For those interested to find out more there is an option to sign up to a mailing list so they can be the first to find out when new content gets added. There are also some bullet points explaining the kind of additional content that will be added in the future. All fields require completing and the Email address field will look for an @ to be included.

![sign-up-page](assets/media/sign-up-page.png)


At the bottom of the page is another high quality evocative image of Mount Everest.

![evocative-everest](assets/media/evocative-everest.png)

### Additional features to include 
The list of additional features to be added at a later date include:

* More interesting facts.
* A gallery page. 
* A timeline of key events at Mount Everest.
* Kit list required for trekking to Base Camp or climbing the mountain.

## Technologies used
The following technologies were used for this site:
* HTML5
* CSS3
* W3C validation for HTML and CSS 
* Google Fonts was used to import the 'Montserrat' fonts into the style.css file.
* Font Awesome was used to add Favicon icons.
* GitPod was used for coding the site and version control.
* GitHub as the repository for the projects code.
* WebAIM contrast checker
* Am I Responsive - for checking the look on different size devices
* Lighthouse in Chrome dev tools

## Testing

### Features
|Features|Test Conducted|Expected Outcome|Test Outcome|
|:----|:----|:----|:----|
|Hamburger toggle works correctly|Tested hamburger icon on all pages|The site menu drops down|Pass|
|Logo|Check to see if takes user back to homepage|User taken to homepage|Pass|
|Navbar-Home|Click on the Home link on each page|User taken to Homepage|Pass|
|Navbar-Interesting Facts|Click on the Interesting Facts link on each page|User taken to Interesting Facts page|Pass|
|Navbar-Sign Up|Click on the Sign Up link on each page|User taken to Sign Up page|Pass|
|Social Media links|Click each link on each page to make sure user is taken to correct site on a new tab|User taken to site in new tab|Pass|
|Sign Up form validates First Name|Tried to Subscribe without entering First Name|Please fill in this field message|Pass|
|Sign Up form validates Surname|Tried to Subscribe without entering First Surname|Please fill in this field message|Pass|
|Sign Up form validates Email|Tried to Subscribe with incorrect email format|Please include @ in the email address|Pass|
|Completed form goes to form dump|Completed all fields and pressed Subscribe|Congratulations message|Pass|

#### Subscribe Form test
![subscribe-form-test](assets/media/subscribe-form-test.png)

### Browser Compatibility
|Browser Tested|Intended Appearance|Test Outcome|
|:----|:----|:----|
|Google Chrome|Good|Pass|
|Firefox|Good|Pass|
|Edge|Good|Pass|
|Firefox|Good|Pass|

#### Chrome test output
![chrome-test](assets/media/chrome-test.png)
#### Firefox test output
![firefox-test](assets/media/firefox-test.png)
#### Edge test output
![edge-test](assets/media/edge-test.png)
#### Safari test output
![edge-test](assets/media/safari-test.png)

### Responsiveness Testing
|Device Tested|Site Responsive <699px|Site Responsive >=700px|Test Outcome|
|:----|:----|:----|:----|
|I-phone 13|Yes|N/A|Pass|
|Galaxy Fold|Yes|N/A|Pass|
|I-Pad Mini|N/A|Yes|Pass|
|Laptop|N/A|Yes|Pass|
|Desktop|N/A|Yes|Pass|

### Code validation
|Page Tested|Screenshot of Errors|Solution Applied|Screenshot of Clear Validator Output|Test Outcome|
|:----|:----|:----|:----|:----|
|Home-HTML|N/A|N/A|![homepage-html-test](assets/media/homepage-html-test.png)|Pass|
|Interesting-Facts-HTML|N/A|N/A|![int-facts-html-test](assets/media/int-facts-html-test.png)|Pass|
|Sign-Up-HTML|![sign-up-test-html](assets/media/sign-up-error-message.png)|Removed id from section element and applied to div element ![sign-up-test-html](assets/media/sign-up-error-fixed.png)|![sign-up-test-html](assets/media/sign-up-error-validate.png)|Pass
|CSS|![css-test](assets/media/css-error.png)|Removed comma between padding values ![css-fix](assets/media/css-fix.png)|![css-validate](assets/media/css-validate.png)|Pass|

### Bugs
|Bug|Description|Solution applied|Result|
|:----|:----|:----|:----|
|CSS error in Sign Up Page|CSS validator did not like id in section heading|Moved ID to div section|Re-checked in validator and passed|
|Gap between header and Hero image|There is an obvious gap between the page header and the Hero image on the Home page|Added padding-bottom to header|Gap has now been removed|
|No alt description in images on Interesting Facts page|The image alt was not present|Images were set as background images in CSS. This has been amended to img elements within the HTML|alt message now appears if there is an error loading the image|

### Lighthouse Testing
|View Tested|Outcome of the audit|Solution applied|Screenshot of clear Validator output|
|:----|:----|:----|:----|
|Samsung Fold|![Mobile-lighthouse-test](assets/media/mobile-lighthouse-test.png)|N/A|![Mobile-lighthouse-test](assets/media/mobile-lighthouse-test.png)|
|Ipad Mini|![Ipad-lighthouse-test](assets/media/ipad-lighthouse-test.png)|N/A|![Ipad-lighthouse-test](assets/media/ipad-lighthouse-test.png)|
|Laptop 1440px|![Ipad-lighthouse-test](assets/media/ipad-lighthouse-test.png)|N/A|![Laptop-lighthouse-test](assets/media/laptop-lighthouse-test.png)|
|4k 2560px|![4k-lighthouse-test](assets/media/4k-lighthouse-test.png)|N/A|![4k-lighthouse-test](assets/media/4k-lighthouse-test.png)|

### Accessibility Testing
|Accessibility Test|Outcome of Test|
|:----|:----|
|![Accessibility-test](assets/media/accessibility-test.png)|Pass|

## Deployment 
### Deploying the site
After creating the website in GitPod, the site was deployed to GitHub to host. To deploy the project, use the following steps:
* In the GitHub repository, navigate to the Settings tab at the top of the page.
* Select Pages on the left hand side of the page
* Under "Build and deployment" there is a Source dropdown. Select Deploy from a branch and then Save.
* Once the main branch has been selected and saved, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.
* The live link to the site can be found here - https://hen0678.github.io/Everest-Enthusiast/

### Cloning the site

* Go to https://github.com/Hen0678/Everest-Enthusiast. 
* Click the Code button. 
* Select Copy URL to Clipboard.
* Open a GitBash terminal and navigate to the directory where you want to locate the clone.
* On the command line, type "git clone" then paste in the copied URL and press the Enter key to begin the clone process.

## Credits
### Content
The content has been accumulated from the following sites:
* [Brittanica](https://www.britannica.com/question/What-are-other-names-for-Mount-Everest#:~:text=Its%20most%20common%20Tibetan%20name,Sir%20George%20Everest%20in%201865)
* [Global](https://www.globaladventurechallenges.com/journal/mind-blowing-facts-about-mount-everest) 
* [Google arts & culture](https://artsandculture.google.com/story/how-this-woman-became-the-first-to-summit-mount-everest/fQUh_Fty-kST3Q?hl=en)
* [Everest Mountain - News from way high up](https://everestmountain.co.uk/30-everest-facts)

### Code
* Code Institute Love Running site.
* HTML & CSS by Jon Duckett.
* Slack support.

### Images
Images have been accumulated form the following sites:
* Mount Everest Hero image - [pexels.com](https://www.pexels.com/photo/snow-capped-mountain-peak-6642124/)
* Trekker image - [pixabay.com](https://pixabay.com/photos/mount-everest-mountains-trekking-6395759/)
* Junko Tabei - [Wikipedia](https://en.wikipedia.org/wiki/File:Junko_Tabei.jpg)
* Everest queues - purchased from [istockphoto.com](https://www.istockphoto.com/photo/mount-everest-summit-top-of-the-world-highest-mountain-gm1312670581-401408488)
* Everest photo on Sign Up page - [unsplash.com](https://unsplash.com/s/photos/mount-everest)

### Other acknowledgments
* Brian Macharia for mentor support and advice.







 


 

[def]: assets/media/edge-test.pgg