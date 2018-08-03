# WHAT DID YOU DO TODAY?

## Including both professional and personal work

---

### August 2, 2018

#### Work

##### OneTrust Marketing

- Added 8/2/18 announcement to Angular and Gatsby sites, uploaded rebuilt Angular site to FTP

##### New Landing Pages

- Wrote FE requirements for 3 new landing page projects in preparation for meeting tomorrow

##### Paid Social Landing Page

- Created project with cra and Apollo
- Set up GraphQL with apollo-link-rest to query data from MLO endpoint and bring into application (it works!)

##### New Hire Orientation

- Built for production and moved to live server
- Finalized mailer script with actual addresses and fixed .csv attachment
- Added new additionalInfo field to summary screen and mail content

---

### August 1, 2018

#### Work

##### New Hire Orientation

- Wrote QC document guidelines and distributed to team members - goal to start testing Friday
- Updated MLO Post Close agreement to most recent version
- Added additionalInfo field to screen 5 to cover MLOs covering other costs and Jump Start campaign
- Set up PHPMailer to send a user email in addition to admin email

#### JoinOneTrust

- Added all sections to parent component
- Started implementing footer
- Continued to work on scrolling animations for sections

---

### July 31, 2018

#### Work

##### New Hire Orientation

- Set up summary table to have working router Links to each screen for easy access
- Added conditionally rendered 'return to summary' button to return to summary when form is complete

##### Misc

- Helped Rose figure out HTML email formatting in dumb Encompass thing
- Meeting with Cory to go over first stages of next 2 landing page projects - Paid Social LP and MLO Phase 3

#### Personal

##### Level Up Tutorials - Apollo & React

- Continued working through tutorial, joined Slack channel

##### MERC

- Updated SVG banner with dots and monocolor header

##### FLAVA

- Updated exhibtior map link, added big registration button to home page

---

### July 30, 2018

#### Work

##### JoinOneTrust

- Started writing own functions for scrolling animations
- Implementation of scrolling animations using Lagrange Polynomial Interpolation - works for 2 sections so far...
- Figured out that the parallax thing is just background-attachment: fixed

##### Dr/Atty Landing Page

- Started front-end requirements doc

#### Personal

##### Level Up Tutorials - Apollo & React

- Started tutorial, got through a few videos - subscribed to Level Up Pro

---

### July 28 & 29, 2018

#### Personal

- Went camping & fishing by myself at Lake Morena to escape technology for a lil bit
- Caught a fish and cleaned it and filetted it and ate it on the lake, was tasty

---

### July 27, 2018

#### Work

##### New Hire Orientation

- Finished implementing real design
- Implemented Wistia video component successfully! And added all videos except Thank You
- Responsive styling for mobile
- Responsive styling for MLO laptops - 1366 x 768 screen resolution
- Various fixes for Firefox's stupid flexbox rendering failures

##### Test Server

- Confirmed that FTP access now works, can enter and upload stuff
- But domain still does not resolve properly...always gives 'Internal Error: Missing Template ERR_CONNECT_FAIL'

---

### July 26, 2018

#### Work

##### New Hire Orientation

- Continued doing the same thing to make the thing look nice
- Implemented flip cards for business cards
- Attempted to integrate with Wistia with little success so far...

##### Drip Campaign

- Updated _Weekly Updates to All Associates Parties_ email campaign

---

### July 25, 2018

#### Work

##### New Hire Orientation

- Further implementation of design into app, pretty much all day

##### MERC

- Fixed tabbed content not working properly
- Inquired about what to do about banner image?

---

### July 24, 2018

#### Work

##### New Hire Orientation

- Refactored screens 6, 8, 9 to use radio button binary choice instead of single checkbox
- A lot of refactoring in general, to reduce amount of code and centralize actions for error handling
- Started working on adding actual design assets to replace placeholder content

##### MLO Sites & Branch Pages

- Checked on how POST requests are sent to LoanForce and Marketo APIs

##### Marketo

- Figured out how to center things in Outlook with a pretty fool-proof <center></center> tag method

#### Personal

##### Misc

- More Lvl Up Tuts Meteor/Graphql/React tutorial - implementing refetch directly in mutations

---

### July 23, 2018

#### Work

##### Drip Campaigns Gatsby

- Added a rather detailed readme.md
- Updated Job Aid on Sharepoint

##### New Hire Orientation

- Responsive image code for 01 New Hire email
- Job aid for adding responsive images started
- Got vector assets to start dropping into project

##### Portfolio Product Landing Page(s)

- Initial meeting to discuss project kickoff starting with Doctor Attorney loans

##### Test/Dev Server

- Created entry in Basecamp to track progress of setup of server

#### Personal

##### Misc

- Continued Lvl Up Tuts Meteor/Graphql/React tutorial - getting data actually into component

---

### July 21 & 22, 2018

#### Personal

##### Hidden Treasures

- Met w/ Keegan to discuss initial steps to take to start planning app

##### Misc

- Level Up Tutorials Fullstack Meteor + Graphql + React tutorial - about halfway done

---

### July 20, 2018

#### Work

##### MLO Website

- Fixed problem of sites not loading

##### JoinOneTrust

- Spent most of the day messing around with different animation/scrolling libraries
- None of them can do what is needed...somehow...might have to write my own...

---

### July 19, 2018

#### Work

##### JoinOneTrust

- Created new mockups in XD with working prototype transitions
- Started working on rebuild in React, created Header component
- Set up Opener section with animated elements
- Implemented modal component
- Updated favicon and site title

##### MLO Website

- Tried to fix hombuyer's/homebuying disparity, wait to see when cache clears

##### Drip Campaigns

- Updated othl-a01 campaign first image

---

### July 18, 2018

#### Work

##### New Hire Orientation

- Generated csv file from json input and attach it to email that is sent
- Dynamic filenames for csv - get saved to FTP server and attached to emails (don't want just email - redundancy good)
- Switched to using PHPMailer instead of mail() function

##### Test Server

- Told that test server is up and running at https://mdev.onetrusthomeloans.com/

---

### July 17, 2018

#### Work

##### JoinOneTrust

- Successfully deciphered development and build gulp pipeline and can now change/update code
- Had meeting with team to discuss next steps, will redo prototypes in XD tomorrow
- Determined that updates will require serious restructing; investigating if it's a good idea to rebuild entire thing in React (it is)
- Initialized new project with create-react-app and started recreating opening slide

---

### July 16, 2018

#### Work

##### New Hire Orientation

- Starting to ensure site is fully responsive and usable on any device
- Tested build and made sure production version works properly on Apache server
- Tested build on Netlify (it works!) - might be best way of deploying live app...

##### MLO Website

- Attempting to fix /LO directory by redirecting to /lo via 301 redirect rule

##### FLAVA

- Exhibitor registration update
- Investigation of registration issues & fix emailed to exec board

#### Personal

##### Catgame

- Put spooky tree sprite into game

##### Art Stuff

- Drew a rat next to cat and added a background

---

### July 14 & 15, 2018

#### Personal

##### Misc

- Saw a COOL SHOW and met my internet friend in Witch Mountain
- Ran Pride 5k, with a new PR and best mile time too
- Nothing productive re: coding or art or anything

---

### July 13, 2018

#### Work

##### New Hire Orientation

- Address validation for screen 7
- Added exclusion parameter for checkIfScreenValid function to allow conditional required fields to be validated/not validated
- Started testing out real video media
- Added thank you screen
- Ate a lot of food at company potluck

---

### July 12, 2018

#### Work

##### New Hire Orientation

- Replaced progress blocks with percent tracker bar
- Client-side form data formatter to package data for summary display and sending to email
- Better styling for email HTML content
- Converted shipping address textarea into broken-out fields
- Added error class to hilight specific fields with errors (in addition to messages)

---

### July 11, 2018

#### Work

##### New Hire Orientation

- Weekly meeting - reviewed mockups and decided on some changes (progress bar instead of blocks)
- Added comments to all screens documenting how each screen works
- Added error writing on attempted route change for all screens with required fields
- Added error messages for required fields in routes.js data file, and reworked error writing accordingly
- Made real error messages when validators aren't passing
- Lots of progress on getting json form data into html response format to send in email (can send html email of whole shebang)

#### Personal

##### Art Stuff

- Drew a jellyfish

---

### July 10, 2018

#### Work

##### New Hire Orientation

- Added detailed comments to several parts of application
- Fixed some random errors/warnings/bugs
- Set up working PHP email script - only works when deployed to FTP server (localhost and CRA dev server don't have mailserver I guess)

##### Drip Campaign Gatsby

- Confirmed test deployment on FTP is working properly (no problems with fragments not being bundled properly)
- Deployed rebuilt Gatsby site to live url @ https://onetrustmarketing.com/lxercmbowpozmwbdgxky/ and confirmed is working
- Added detailed comments to /components directory files, plus small tweaks/bugfixes
- Moved styling in campaign page template to use theme helpers
- Dev --> master PR in Bitbucket repo
- Got suggestions for improvements (alphabetizing and adding X to modal)

##### Branch Pages

- Wrapped up updates/fixes for now, closed out ticket in Basecamp

##### OneTrust Marketing

- Added LO Social Bot job aid to both Angular and Gatsby sites (uploaded Angular update to live site)

#### Personal

##### Art Stuff

- Drew a cat
- Finished pixel tree

---

### July 9, 2018

#### Work

##### New Hire Orientation

- Tested local apache deployment using router basename (success!)
- Progress bar error checking/disabled links if errors
- Dynamic screen transitions - left or right animated slide depending on current + destination slides
- Started setting up modal data for screen 5 (post close agreement)
- Removed generic CRA readme (will start a real readme tomorrow)

##### Drip Campaign Gatsby

- Fixed build artifact errors and successfully deployed to test FTP
- Waiting for finalization of last few campaigns then will make new site live

---

### July 7 & 8, 2018

#### Personal

##### Drawing

- Drew some drawings with new colored pencils

---

### July 6, 2018

#### Work

##### New Hire Orientation

- Styling moved to match wireframes
- Custom checkbox and radio styling and behavior implemented
- Switched to react-transition-group for animations and got basic slide animation working
- Implemented switch to keep track of active screen string
  -- Will use later in error handling to disable progress block links if there are errors

##### Drip Campaign Gatsby

- Met with Cory to finalize last few steps
- Added New Hire Post Close campaign
- Conditional rendering for othl-only campaigns

---

### July 5, 2018

#### Work

##### Branch Pages

- Implemented address fixed: Loanforce for display, Google for links
- Working with team to get headshot size issue fixed
  -- Suggested 50kb limit, or 300x300px

##### New Hire Orientation

- Continuing to write validators
  -- Screens 3, 4, 5, 7, 8, 10, 11, 12
- Conditional rendering for screen 15 summary
- Misc tweaks and fixes to validators and validation flow

##### FLAVA

- Big exhibitor update, switching to regular registration

##### MERC

- Attempted to set up meeting with David to discuss changes

---

### July 4, 2018

#### Work

- It is a holiday and I am off, hooray, time to go to the beach

---

### July 3, 2018

#### Work

##### New Hire Orientation

- Implemented data persistance via localStorage
- Cleaned up project (removing unused packages, branches)
- A whole lot of stuff with validating
  -- Determined it will be best to write custom validators for everything - no external libraries
  -- Wrote custom validators for first and second screens (can be used over for other screens too)
- Started adding more detailed comments to various parts of application

---

### July 2, 2018

#### Work

##### OneTrustMarketing (+Gatsby)

- Updated announcements
- Cleaned up git branches for both projects

##### New Hire Orientation

- Finished tying fields to state for each screen
- Various fixes, tweaks, small improvements
- Started implementing localStorage persistance
- Conditional rendering across all screens

---

### June 30 & July 1, 2018

#### Personal

##### Pixel Art

- UFO animation

---

### June 29, 2018

#### Work

##### Branch Pages

- Address bug where Google formatted address was displayed instead of API address

##### New Hire Orientation

- Continuing to structure/skeleton, all screens set up
- Start of implementing logic to track form state
- Decided to remove Formik (for now at least) as it couldn't do what I needed

### June 28, 2018

#### Work

##### New Hire Orientation

- Set up project with CRA and repo on Bitbucket
- Started project structure and building prototype
- Got as far as setting up first 4 screens, general layout, several components, and initial state

---

### June 27, 2018

#### Work

##### Training

- HDMA: Enhanced Reporting Requirements
- BSA and AML: Essentials
- Key Essentials of Customer Service
- Mortgage Origination: Security, Identity Theft, and Fraud
- Information Security: Preventing Identity Theft
- Understanding Privacy: The Essentials
- Laws and Regulations for Mortgage Lending
- Predatory Lending Awareness
- Harassment Prevention Training for Employees

##### Drip Campaign Gatsby

- Successful deployment on OneTrust FTP
- Consolidation of emails to prepare for meeting

---

### June 26, 2018

#### Work

##### Component Library

- Started researching to think about how to build component library

##### Drip Campign Gatsby

- Retooled styling to centralize in theme and use theme styles everywhere possible
- Another attempt at modifying htaccess to deploy via FTP
- Added prefixed branch with pathPrefix
- Set up local site on Xampp to test Apache server

##### OneTrustMarketing Gatsby

- Another attempt at modifying htaccess to deploy via FTP
- Added prefixed branch with pathPrefix
- Set up local site on Xampp to test Apache server
- Successfuly deployed to https://onetrustmarketing.com/gatsby/

##### New Marketing Orientation

- Updated wires to reflect landing page form changes

#### Personal

##### Grocery List

- Made a grocery list lol (see it here if u wanna see what I eat)

---

### June 25, 2018

#### Work

##### Drip Campaign Gatsby

- Cleaned up data and images for all branches
- Merged restructure branch into dev with new design/organization
- Fixed several deployment bugs and pushed new version to Netlify

##### Branch Pages

- QA testing from team members confirm no more 404s (htaccess working)
- Updated PageSpeed results
- Shrunk images of team members where needed
- Proper images loading - only 2 left that need banner updated

---

### June 23 & June 24, 2018

#### Personal

- Nothing lol went to the Safari Park instead of doing work

---

### June 22, 2018

##### Branch Pages

- New htaccess rules following FB guidelines - seems to work
- Pushed updates to live /branch site including working htaccess

##### Drip Campaign Gatsby

- New datasets for Calcon and Tabor
- Branch for restructuring into automatic & manual sections
- Manual campaigns listed on index, queried as pages, links for each branch

---

### June 21, 2018

#### Work

##### Branch Pages

- Researched page speed insights and optimizations
- Discovered weird API behavior (loads different images at same endpoint?)

##### OneTrustMarketing Gatsby

- Changed order of icons to match live site
- Added htaccess to attempt to deploy to FTP

##### Drip Campaign Gatsby

- Started consolidating emails into manual vs automated categories
- Set up new dataset for OTHL - CalCon and Tabor tomorrow

---

### June 20, 2018

#### Work

##### Drip Campaign Gatsby

- Added new Tabor campaign
- Dev --> master big bang merge
- Made test branch on FTP to try and deploy there; rewrite rule currently not being followed
- Updated model to use frequency array of objects rathern than arbitrary objects (much better for graphql querying)

##### Drip Campaign AngularJS

- Added new Tabor campaign

##### Josh Award Email

- Added contact info block

##### Branch Pages

- Set up Netlify deployment branch for rapid live testing

---

### June 19, 2018

#### Work

##### OneTrust Birthday

- Did 5 trivia questions

##### Branch Pages

- Added loading screen/component when branch is selected
- Compressed banner images
- Investigated 404 errors
- Uploaded most recent version to test branch, waiting for it to take...

##### New Hire Orientation

- Finished XD wireframes for landing page form process

##### Josh Award Email

- Tweaks and fixes for Cory

### June 18, 2018

#### Work

##### OneTrustMarketing site Gatsby

- Finished Menu of Services landing page
- Made fully responsive
- Made footer sticky at bottom with 100vh min page height
- Added favicon
- Successfully deployed via Netlify

##### New Hire Orientation

- Started wireframes in XD

---

### June 16 & 17, 2018

#### Personal

##### Zine Site Gatsby

- Set up additional user on Contentful
- Added new fields for zine model

---

### June 15, 2018

#### Work

##### Branch Pages

- Pushed branch title and footer fix to live site

##### OneTrustMarketing site Gatsby

- Started rebuilding OneTrustMarketing site in Gatsby
- Created header, footer, materials, and announcments components
- Created branch pages and components
- Almost fully done...two big things remaining: Menu of Services landing page, fix Facebook bug

---

### June 14, 2018

#### Work

##### New Hire Orientation

- Successfully made tracker image responsive in email (different image on desktop and mobile)

##### JoinOneTrust

- Got project files from Rachel and set up development version of site with gulpfile

##### OneTrustMarketing site

- Added new icon in top nav
- Fixed responsive display in top nav
- Added new Services component to display Menu of Services

#### Personal

##### Zine Site Gatsby

- Created project and repo
- Set up Contentful for CMS storage
- Pulled in data from Contentful to app
- Added 4 zines to test display on index page

---

### June 13, 2018

#### Work

##### Drip Campaign site rebuild in Gatsby

- Minor tweak to automated campaign 'Weekly Updates to All Associated Parties' emails
- Made fully responsive on index and campaign pages
- Investigated IE11 support - may need polyfill

##### JoinOneTrust

- Updated top producer images

---

### June 12, 2018

#### Work

##### Drip Campaign site rebuild in Gatsby

- Fixed JSON shape for consistency and accounting for frequency and triggers
- Created custom modal to view images in larger size
- Successfully deploying to Netlify - investigate if this is an option (alias to proper URL)
- Updated job aid information about site on SharePoint
- Fixed favicons by disabling path prefix (not needed for static images anymore)
- Fixed querying and conditional rendering of pauses section on each campaign page

##### MLO AngularJS site

- Attempted to fix console warning on live site by switching YouTube image to HTTPS (have to wait and see if it takes)

##### Branch Site

- Added header text to non-mobile displays
- Fixed mobile 'back to top' button display
- Removed unnecessary logging
- Fixed directly mutating state in calculator

##### Menu of Services Email

- Added List Reports item
- Fixed weird spacing in intro paragraph
