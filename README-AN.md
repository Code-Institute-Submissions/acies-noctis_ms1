# Acies Noctis

This website represents a virtual home for my friend and artist Acies Noctis. Since Acies so far didn't have any official website I decided to create one with his help and feedback.
Acies Noctis is a musician and I wanted website to be focused on music first, and help him get it out there. I believe the artist deserves strong and simple online presence and my aim with this website is to create it.
-  **[Live Site](https://wertzhog.github.io/acies-noctis_ms1/)**
## UX
In my UX design I was following 5 plains of UXD.
1. Strategy plane
    * I talked to artist about ideas and we reached agreement on the approach to develop this web page. 
    We decided to create website for musician which would provide  a stronger online presence and show his dedication towards art. 
2. Scope plane
    * I wanted to provide a solid base website which is easy to upgrade and update.
    I wrote a few different user stories to guide me in development.

### User stories

* As a fan of electronic music I want to listen to newly released music.
* As a fan of electronic music I want to find out where I can see artist perform live.
* As a fan of electronic music I want to buy/download music and support the artist.
* As record label owner I want to contact artist for colaboration/publishing deals.
* As venue owner I want to contact artist for live performance.
* As a fan of electronic music I want to visit artist's Soundcloud/Bancamp page to listen to more of his music.
* As a fan I want to visit artist's social media to see what is he like in private life.

3. Structure, Skeleton and Surface plane I developed in my mockup design.
    * I used Figma to create mockup ([mockup](https://github.com/Wertzhog/acies-noctis_ms1/blob/master/Mockup/mockup-acies%20noctis.pdf))
    * I deviated from my original mockup. I went for black&white color profile since other color introduced problems in readability on smaller devices.

## Features

### Exisiting Features

* **Navigation Bar** - allows users to easily navigate the site and to visit outside resources(social networks and music streaming platforms).
                     - I used Bootstrap 4 class .fixed-top so user can easily access any part of website anytime.
                     - I also added navbar toggler (hamburger icon) for a compact view of navbar on mobile devices.

* **Callout image/logo** - created in collaboration with artist himself it sets out to create a visual identity for website.

* **Music section** - offers music player to listen to newly released music and link to visit artist's profile on music streaming platforms.

* **Tour dates** - In clean table user can find dates presented for upcoming live performances.

* **Bio** - gives users brief information about artist and his photograph. On mobile view, the photo is replaced with a logo and styled vertically.

* **Gallery** - presents users with photos from past performances and gives option to get their photos featured in gallery on website.

* **Footer** - provides users with links to social and music streaming platforms. Also email to contact for business collaboration.


### Features left to implement

* **Shop** - a place where users can buy different kinds of merchandise (clothes, cd's, LP's, etc.)

* **Wallpapers/Artwork Gallery** - since this artist is creating digital artwork users can download and use it for decoration of rooms etc.

* **Youtube videos gallery** - users can browse and artist's Youtube music videos, interviews etc.

* **Behind the scenes of recording process** - short videos about recording process and tutorials about sound design.


## Technologies Used

* **[HTML/HTML5](https://en.wikipedia.org/wiki/HTML5)** - it is used for basic structure of website.

* **[CSS/CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)** - used for styling of website.

* **Javascript/[JQuery](https://jquery.com/)/[PopperJS](https://popper.js.org/)** - integrated with Bootstrap, used for navbar toggler to function properly.

* **[Bootstrap 4](https://getbootstrap.com/)** - used for styling and adding responsiveness across whole website. Every section of website from navbar to footer has some Bootstrap styling.

* **[FontAwsome 4.7.0.](https://fontawesome.com/)** - used for icons of social media and streaming platforms.

* **[Google Fonts](https://fonts.google.com/)** - used for fonts on entire website.

* **[Animista](https://animista.net/)** - used for logo and text animation.

* **[Hover.css](https://ianlunn.github.io/Hover/)** - used for hover animation on navbar.

* **[Figma](https://www.figma.com/)** - used for mockup.

* **[GitPod](https://www.gitpod.io/)** -  used as IDE for this project.

* **[GitHub](https://github.com/)** - used for version control, hosting project files and live website via GitHub Pages.

* **[Gimp 2](https://www.gimp.org/)** - resizing and editing photos.


## Testing

* **Automated testing**

    * I used Chrome audit to to do automated testing. Here are results:
            [Chrome audit results](https://github.com/Wertzhog/acies-noctis_ms1/blob/master/Testing/chrome%20audit.png)

* **Manual Testing**

    * **Desktop**
       
        * **Google Chome**: everything is working good. Page loads, and all of the page features are working.

        * **Mozilla Firefox**: everything is working good. Page loads, and all of the page features are working.

        * **Microsoft Edge**: everything is working good. Page loads, and all of the page features are working.

    * **Mobile**

        * **Chome Dev Tools**

            * tested with Chome Dev tools for all available devices (from Moto G4 to iPad),
                webpage works well. It is responsive as intended, no weird page deformations.

        **Real-world testing:**

        * **Huawei P20Pro** - site loads good. It is responsive as intended. All of the features are working.

        * **Samsung Galaxy S9** - site loads good. It is responsive as intended. All of the features are working.

        * **HTC Desire 630** - site loads good. It is responsive as intended. All of the features are working.

        * **Samsung Galaxy A5** - site loads good. It is responsive as intended. All of the features are working.

        * **Xiaomi mi 9t** - site loads good. It is responsive as intended. All of the features are working.

    * **Testing User Stories Scenarios**

        * As a fan of electronic music I want to listen to newly released music.
            - click Music link in navbar
            - Once in Music section hit play on integrated player from Sound Cloud

        * As a fan of electronic music I want to find out where I can see artist perform live.
            - click Tour link in navbar
            - once in Tour section, I see that there are dates and option to buy tickets
            - link to buy tickets works

        * As a fan of electronic music I want to buy/download music and support the artist.
            - in navbar I click  Soundcloud/Bandcamp links/icons
            - links working, I am redirected to said pages. (**NOTICE** only links to Soundcloud and Facebook redirect you to artist's profile, rest of the links will be updated later on when respective pages are created)
        
        * As record label owner I want to contact artist for collaboration/publishing deals.
            - In navbar I can find links to artist's social networks
            - links are working
            - In footer I can find email contact
            - link is working

        * As venue owner I want to contact artist for live performance.
            - In navbar I can find links to artist's social networks
            - links are working
            - In footer I can find email contact
            - link is working

        * As fan of electronic music I want to visit artist's Soundcloud/Bancamp page to listen to more of his music.
            - in navbar I click  Soundcloud/Bandcamp links/icons
            - links woring, I am redirected to said pages. (**NOTICE** only links to Soundcloud and Facebook redirect you to artist's profile, rest of the links will be updated later on when respective pages are created)
        
        * As a fan I want to visit artist's social media to see what is he like in private life.
            - in navbar I can find links to social media profiles
            - links are working

## Deployment

 **[GitHub](https://github.com/)** - is used to host code and files for this project. Project has only one branch(master). Deployed version is most current version of repository.

 * **GitHub pages** was used to deploy this site.
    - Go to repository master branch.
    - Press Settings button on right.
    - Scroll down to Github Pages section.
    - Choose Master branch and link to hosted site should appear on top of the section.

 **How to run this project locally**
- **To clone this project from GitHub:** 
([Source](https://github.com/Edb83/penny-for-your-thoughts/blob/master/README.md#testing))

* Under the repository name, click "Clone or download".
* In the Clone with HTTPs section, copy the clone URL for the repository.
* In your local IDE open Git Bash.
* Change the current working directory to the location where you want the cloned directory to be made.
* Type git clone, and then paste the URL you copied in Step 3.
* Press Enter. Your local clone will be created.


## Credits

### Content

* All of the textual content of site was written by me.

### Media

* Music in the music section was authored by Acies Noctis and he gave me permission to use it.

* Logo used on callout section was downloaded from [game-icons.net](https://game-icons.net/).

* Images from Bio and Gallery are obtained from Acies Noctis which he got from their respective owners.

* Callout image was designed by Acies Noctis.

* Design of website was inspired by [Thespecials.com](https://www.thespecials.com/) , [soundgardenworld.com](https://soundgardenworld.com/)

**Acknowledgements**

 * I want to thank my mentor [Precious Ijege](https://www.linkedin.com/in/precious-ijege-908a00168/) for his guidance and help.

* Slack community of Code Institute for their constructive criticism.

* My girlfriend and my friends on their support and help with testing. You are the best! :kissing_heart:


#### This project is for educational purposes and hopefully in near future it will be fully deployed.

**[Live Site](https://wertzhog.github.io/acies-noctis_ms1/)**