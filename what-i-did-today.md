# WHAT DID YOU DO TODAY?

## Including both professional and personal work

---

### September 29 & 30, 2018

#### Personal

- Nothing lol went to LA and saw some cool stuff @ the Museum of Jurassic Technology

---

### September 28, 2018

#### Work

##### Paid Social LP

- Cleaned stuff up re: best practices - componentDidMount instead of componentWillMount, changed arrow function lifecycle methods
- Fleshed out not found page to query list of branches and render as links
- Switched Reviews component from using fetch & local state to GraphQL query
- Seperated out queries into .graphql files with new react-scripts version 2 (hoooorraaayyy)

##### GraphQL Yoga Server

- Added list of branches to API and resolved it to an array of objects so it's not annoying af to work with
- Added Birdeye reviews to API

#### Personal

##### Reci

- Continued working on resolvers

---

### September 27, 2018

#### Work

##### BrowserStack

- Finished testing all sites on all mobile devices

##### Signature Generator

- Updated local version with Tabor award image, sent to Basecamp for review

##### Paid Social LP

- Added images to Basecamp for Ivan to review and edit

##### SD Marketo User Group

- Attended SD MUG meetup & presentation about Velocity script

---

### September 26, 2018

#### Work

##### BrowserStack

- Went through Calcon and Tabor sites on all mobile devices

##### Paid Social LP

- Refined about, header, form, hero sections
- Implemented functions for sending form data to LoanForce in proper format
- Set up redirects to notfound page if invalid campaign or MLO name

#### Personal

##### Reci

- Set up project - created first models, graphql schema, resolvers, repo, etc.

---

### September 25, 2018

#### Work

##### Drip Campaign

- Issue seems to have resolved itself...site loads properly with no error; probably was a problem with the server
- Updated new refinance campaign with correct title, fixed emdash on manual campaign 07 for consistency

##### QC Guide

- Wrote generic QC checklist that takes from NHO and JOT lists plus some new stuff, all genericized
- Added QC guide and QC checklist to Sharepoint FE Job Aids, organized that folder better

##### New Hire Orientation

- Updated to remove css files, remove 2 inactive webinars, remove test file (pushed updated version to server)

##### Branch Pages

- Redirected /branches and /branch to go to the proper /branch/ URL

##### OneTrustMarketing

- Added updates to Menu of Services
- Determined that IT managed to break going directly to URLs; a good time to replace with Gatsby site

##### Paid Social LP

- Added data for all 4 campaigns including modified banner images
- Continued form component with working validators for all fields

#### Personal

##### Apollo Talk

- On schedula for Oct. 2nd to present @ SDJS Monthly Meeting @ Zeeto

---

### September 24, 2018

#### Work

##### MLO Websites

- Updated live site with HBG PDF link, sent out email to team to QC test it

##### Paid Social Landing Page

- Updated Front-end requirements to reflect apollo-boost, @reach/router, campaign URL params
- Created local data file to match with URL param to know which campaign variant to load

##### Drip Campaign

- Added new refinance campaign and encountered some difficulties
- Works properly at driptest URL but not actual url; sent in cache clear request to try to debug

#### Personal

##### Grace Portfolio

- Added about page and content model

---

### September 22 & 23, 2018

#### Personal

##### Grace Portfolio

- Created project and setup basic layout of site, connected to Contentful, built and deployed to Netlify
- Implemented logic for initial homepage content and back/forward content to cycle through static art pages

##### Level Up Tutorials React Testing for Beginners

- Thru video 20

---

### September 21, 2018

#### Work

##### JoinOneTrust

- Finished all comments for forward-facing part of site, for now at least

##### Collateral Generator

- Implemented design of actual flyer to build a proof-of-concept with one template

##### MLO Websites

- Created test deployment at /lo-test/ on OneTrust server
- Updated HBG section to reflect download instead of email and sent for testing (with new test deployment)

#### Personal

##### Apollo Talk

- Added favicon and title to presentation index.html

##### Level Up Tutorials React Testing for Beginners

- Thru video 19

---

### September 20, 2018

#### Work

##### JoinOneTrust

- Going through all code and commenting

##### BrowserStack

- Tested on 8 mobile devices: onetrustmarketing, drip campaigns, marketing orientation, joinonetrust

#### Personal

##### Apollo Talk

- Installed SSL on all subdomains (and main domain)
- Finished presentation slides, deployed to DigitalOcean server

---

### September 19, 2018

#### Work

##### JoinOneTrust

- Further QC tweaks from last round, minor content changes, scrolling offset on mobile
- Officially launched site @ https://joinonetrust.com hooray
- Started going through code and removing unused stuff and adding comments
- Further tweaked readme.md

##### Paid Social Landing Page

- Moved query into App and pass data down as props into components
- Set up system for finding branch from MLO city and state and bringing in banner image (prolly won't actually use tho lol)
- Built out reviews component and figured how to get Birdeye to work with fetch (hooray!)

##### GraphQL Yoga Server

- Made most fields for MLOs not required cuz it's horribly inconsistent what fields are not null in the REST api

#### Personal

##### Apollo Talk

- Moved GraphQL queries and mutation into separate file in React front (had to use .js file cuz cra doesn't support graphql-loader atm)

##### Level Up Tutorials React Testing for Beginners

- Thru video 16

---

### September 18, 2018

#### Work

##### Broken Bash

- Have to use my laptop today until IT can help try to fix work PC...

##### JoinOneTrust

- Sent out for last round of QC, recieved feedback and go-ahead to launch tomorrow
- Tweaked specifically for Micaela's 1600 x 900 resolution desktop, figured out issues
- Finished first draft of readme.md

##### Misc

- Wrote QC Guidelines for process of deploying new projects and changes/updates to existing projects

#### Personal

##### FLAVA

- Registed exec board member who had not been able to register for ~reasons~

##### Level Up Tutorials React Testing for Beginners

- Thru video 14

##### Apollo Talk

- Deployed React and Vue front ends to DigitalOcean, fixed API endpoints

---

### September 17, 2018

#### Work

##### Misc

- Computer decided it would be good to geek out today and bash has stopped working x.x
- Seems likely to be the fault of the Trend Micro anti-virus...

##### OneTrustMarketing

- Reverted to previous backup cuz site was having a MIME error, uploaded new announcements JSON, all good now

---

### September 15 & 16, 2018

#### Personal

##### Camping!

- Camping @ Lake Dixon all weekend so not accomplishing anything productive 8-)

---

### September 14, 2018

#### Work

##### JoinOneTrust

- Fixed various remaining bugs, screwed up a rebase, fixed, ready to officially launch

#### Personal

##### Apollo Talk

- Created presentation with spectable, made a few slides, fixed endpoint in frontends

##### FLAVA

- Addressing various concerns some of which have already been addressed @\_@

---

### September 13, 2018

#### Work

##### JoinOneTrust

- Updated top producer slides for August on current site, a few times
- Added new device-specific helper in theme, using for MLO laptops @ 1366 x 768 resolution
- Fixed OTHLLive slides to be full width of slides (72vw vs 70vw)
- Further responsive tweaking and cross-device/browser testing
- Attempted to implement active class for nav, works with fixed height sections but not on mobile, not implemented
- Refactored major parts: sections now use a base component with render prop, that holds all calculation logic

##### Paid Social Landing Page

- Fleshing out About section, continuing to build page skeleton

---

### September 12, 2018

#### Work

##### MLO Websites

- Fixed reviews with blank comments/content so that they do not show up
- Uploaded most recent build of site to OTHL, CalCon, and Tabor servers

##### JoinOneTrust

- More and more responsive tweaking, fixing mobile & Safari background images
- Fixed reviews with blank comments/content so that they do not show up
- Sent partner image specs & PSD template to designer

##### OneTrustMarketing

- Updated announcements with 9/12 announcement

##### Paid Social Landing Page

- Created new project to use apollo-boost and GraphQL api
- Laid out page with skeleton components and basic MLO query

---

### September 11, 2018

#### Work

##### Branch Pages

- Fixed reviews to ignore reviews with missing data

##### OneTrust WordPress Site

- Added Customer Service section to contact page

##### New Hire Orientation

- Added cell # to thing that gets sent to backend to process email and csv

##### Marketo

- Helped figure out date token thing

##### Collateral Generation

- Got frustrated and nowhere really with react-pdf rip, time to try something else???
- Tried something else: @progress/kendo-react-pdf, it works very well
- Can generate and export PDFs dynamically using data from GraphQL API

---

### September 10, 2018

#### Work

##### JoinOneTrust

- Added footer component and implemented on all pages
- Continuing to improve mobile experience and make everything fully responsive
- Finished the project, for now at least
- Deployed build to local and remote Apache servers at /updated path

##### Collateral Generation

- Started looking into solutions to dynamically create PDFs (https://github.com/diegomura/react-pdf)

### September 8 & 9, 2018

#### Personal

##### Apollo Talk

- Put recipe api on digitalocean to allow remote access
- Added field validations and error/success messages to vue and react fronts
- Project is finally really done, time to start slides for it

##### Level Up Tutorials React Testing for Beginners

- Thru video 8

##### Misc

- Did a lot of random digitalocean management junk to use gareth.cool domain

---

### September 7, 2018

#### Work

##### JoinOneTrust

- Went through entire site and implemented various responsive tweaks
- Sent for second round of QC testing, received feedback to fix on Monday

##### GraphQL Gateway

- Did more research into PHP implementation of GraphQL server and determined that I need to know PHP better before trying to write one (probably learn Laravel too)
- Will stick with node graphql-yoga server for now, and see about getting a place to deploy it properly

#### Personal

##### Apollo Talk

- Added admin form to Vue front and set up fetch posting and graphql mutations
- Project is basically done now, just some UI/styling polish left

##### Level Up Tutorials React Testing for Beginners

- Thru video 9

---

### September 6, 2018

#### Work

##### MLO Websites Phase 3

- Created images for 5 example partners
- Switched template/css to use just images instead of images & text
- Redid partner field requirements to reflect just images and URLs (2 fields)
- Added HBG PDF new tab open to HBG form on successful completion and new success message
- Disabled Marketo posting

##### JoinOneTrust

- Fully integrated Marketo form embed with success/error messages, tweaked to reduce load time
- Mobile tweaks for form, determined that Brave browser does not allow cross origin scripting or something?

#### Personal

##### Apollo Talk

- Better styling for React front including admin page
- Created favicons and changed Vue theming to Vivacious Viands

---

### September 5, 2018

#### Work

##### GraphQL Gateway

- Built schema for mlos and branches, including branch owner and branch member nested fields
- Figured out how to implement resolvers to standardize field names
- Deployed graphql-yoga server to Now successfuly

##### MLO Websites Phase 3

- Had meeting, decided on using only images
- Started implementing image-only entries
- Figured out kinda how AngularJS data works?

---

### September 4, 2018

#### Work

##### JoinOneTrust

- Tweaking and various fixes, going over first round of QC checks - have ready for second tomorrow
- Inquired re: Marketo or LoanForce, have to wait til tomorrow to meet and finalize

##### Warp Speed

- Did further research, looked docs/presentations, and some existing competitors

##### MLO Websites Phase 3

- Mocked up partner section in Photoshop
- Created new partner section component in AngularJS app and implemented with styling
- Did field requirements for partner section

##### GraphQL Gateway

- Did more research on GraphQL PHP implementations, tried some PHP GraphQL tutorials
- Started building schema from REST APIs

#### Personal

##### SDJS

- Went to meetup, talked to some ppl, saw some presentations

##### Apollo Talk

- Implemented individual GraphQL pages for Vue, added lots of styling

---

### September 1, 2, & 3, 2018

#### Personal

##### Apollo Talk

--- Created VueJS frontend and set up fetch and GraphQL querying for all and individual recipes

### August 31, 2018

#### Work

##### JoinOneTrust

- Responsive optimizations for exclusive and public parts of site
- This also took all day!

##### Misc

- Sat in on call with Google support re: phone tracking, investigated issue further

#### Personal

##### Apollo Talk

- Better styling for individual recipes
- Implemented GraphQL querying for individual recipes

##### Level Up Tutorials React Testing for Beginners

- Thru video 2

---

### August 30, 2018

#### Work

##### JoinOneTrust

- Finished building out all sections for exclusive part of site, including menu
- This took all day more or less

---

### August 29, 2018

#### Work

##### JoinOneTrust

- Building out the exclusive content portion of site - OTHLLive, LoanForce, Post Close Campaign (mostly) done

##### OneTrustMarketing

- New announcement for 8.29.18

##### Landing Pages

- Trying to figure out how tf google tag manager works with phone conversions

#### Personal

##### FLAVA

- Misc fixes, tweaks, helping, etc (0.5 hrs to log)

---

### August 28, 2018

#### Work

##### Drip Campaign

- Added new Recruit Campaign for OTHL and deployed new build of site
- Updated readme with minor fixes

##### JoinOneTrust

- Swapped placeholder for higher resolution assets
- Implemented better slideshow logic for OTHLLive modal
- Created and styled Marketo form embed component...hopefully won't have to actually use...

#### Personal

##### Grocery List

- Updated grocery list to go shopping after work!!
- Went grocery shopping and got a lot of produce!!
- Made a dank salad and mashed potatoes for dinner!!

---

### August 18 - 27, 2018

#### Vacation

##### On vacation all week lol

- Did a buncha cool stuff unrelated to web dev!!
- Figured out how to properly use mutations with apollo-link-state and continued working on apollo talk

---

### August 17, 2018

#### Work

##### JoinOneTrust

- Continued building out functionality
- Added reviews API fetch and modal display of latest 3 reviews
- Started building exclusive content
- Implemented OTHLLive slideshow and debugging it

#### Personal

##### Apollo Talk

- Got posting to work to API from react admin

---

### August 16, 2018

#### Work

##### JoinOneTrust

- Moved some data from JSX into separate file
- Implemented functionality for all slide elements (modal pop ups)

##### MLO Websites

- Set to only one of Boast or Birdeye reviews load

##### Marketo

- Further tweaks to landing page template & live Dr/Atty site

##### Misc

- Added audio files to marketing site to see if it works (it works hooray)

#### Personal

##### Apollo Talk

- Started building form to send new entries to API

---

### August 15, 2018

#### Work

##### JoinOneTrust

- Added opacity animations for all elements on screens (not sure if will keep or use different animations)
- Implemented screen-size agnostic scroll settings so animations trigger properly regardless of screen size

##### New Hire Orientation

- Minor tweak to header image sizes for mobile layout

##### Marketo

- Tweaks to Clear Dark landing page template & Dr/Atty live LP

#### Personal

##### FLAVA

- Exhibitor update, misc fixes

##### Apollo Talk

- Started implenting actual styling w/ CSS Grid to React front

##### Level Up Tutorials VueJS For Everyone

- Continued through video 19

---

### August 14, 2018

#### Work

##### Branch Pages

- Continued building out page, got to calculator section

##### JoinOneTrust

- Implemented layout of components on each slide

##### Misc

- Had compliance meeting and reviewed compliance materials in preparation for upcoming audit

#### Personal

##### Level Up Tutorials VueJS For Everyone

- Continued through video 16

##### Apollo Talk

- Changed model a bit, continued building out React front

---

### August 13, 2018

#### Work

##### Branch Pages

- Figured out how types work with nested data from API
- Started implementing styling and building out branch page components, got to Team Members

##### OneTrustMarketing

- Added EHO logo and info to footer

##### Modular Resources

- Added EHO info to footer

##### Warp Speed

- Read all about it and went through presentations and such

#### Personal

##### FLAVA

- Troubleshooted exhibitor email caught in spam filter because of word 'communication'

##### Level Up Tutorials VueJS For Everyone

- Continued through video 14

---

### August 11 & 12, 2018

#### Personal

##### Apollo apollo-link-rest talk

- Set up recipe API
- Created React front end with GQL and fetch component examples

##### Level Up Tutorials VueJS For Everyone

- Started series and got through video 7

---

### August 10, 2018

#### Work

##### Marketo

- Learned how Marketo templating works and how to create/customize templates
- Updated Clearer Title - Dark landing page template with new sections

##### Branch Pages

- Implemented querying for individual page routes if accessed directly - if from home, loads from cache, if not, does call at runtime
- Moved initial call to get all branch data to home-only component for much faster individual branch loading
- Started working with full queries, ran into issue with nested data for unknown reasons, may have to just pull all nested data (oh well)

#### Personal

##### FLAVA

- Helped Paloma out with exhibitor stuff

##### Level Up Tutorials React & Apollo

- Finished series! Probably will start vue.js series next

---

### August 9, 2018

#### Work

##### JoinOneTrust

- Updated top producer slides for July

##### OneTrust Marketing

- Removed marketing policy thing and rebuilt/uploaded site

##### Branch pages

- Bashed my head against the wall all day tryna get dynamic routing to work with branch queries
- Eventually got it working pretty well - loads data from cache if accessed from home page

##### New Hire Orientation

- Added third webinar icon & link to screen 13, uploaded newest build of site

---

### August 8, 2018

#### Work

##### New Hire Orientation

- Weekly meeting, went over final landing page tweaks
- Implemented final landing page tweaks
- Added flippy triangle to submit button (very important)
- Added route + component for paths outside of what ppl should see

##### Branch Pages

- Successfully can generate dynamic queries by utilizing query variables to load each branch's data

#### Personal

##### Level Up Tutorials React & Apollo

- Finished videos #19 & #20

---

### August 7, 2018

#### Work

##### New Hire Orientation

- Refactored title and body copy content to import HTML strings rather than directly in JSX
- Set up clearing of localStorage entry upon successful submission of form
- Pushed out to team for next round of QA testing

##### Branch Pages

- Explored options for pre-generating pages; ruled out SSR
- Decided static site generation not the best option as it requires a full update
- Started setting up an Apollo project and creating dynamic queries with some success

##### JoinOneTrust

- Weekly meeting; waiting to decide if should stick with Marketo script or use custom

##### Drip Campaign

- Merged dev into master (been a while since this was done)

##### Misc

- Did the employee survey thing
- Set up Fira Code font in VSCode (ok I like ligatures now)

#### Personal

##### FLAVA

- Various updates to Fall 18 forms and entries and such'

##### Level Up Tutorials - Apollo & React

- Started on video #19 but fell asleep after a few minutes lol

##### SDJS Monthly Meetup

- Went to meetup @ Zeeto, saw some cool presentations, talked to some cool folks

---

### August 6, 2018

#### Work

##### New Hire Orientation

- Finished fixes for MLO laptop resolution
- First round of QC tweaks implemented
- Added actual Thank You video to TY screen

#### Personal

##### Level Up Tutorials - Apollo & React

- Continued working through videos, on #19

---

### August 4 & 5, 2018

#### Personal

##### Level Up Tutorials - Apollo & React

- Continued working through videos, about 2/3 done

---

### August 3, 2018

#### Work

##### Branch Pages

- Ran performance tests with Google Pagespeed and Pingdom (pretty good results!) - optimizing headshots did help

##### New Landing Pages

- Met with team and determined next steps and viability of project design and such

##### OneTrust WordPress

- Got admin access to WP site, hooray, thanks Steve
- Fixed dumb Thesis theme loading header scripts with escape slash characters

##### New Hire Orientation

- Got a laptop with 1366 x 768 resolution to test on
- Started making specific responsive fixes for dumb MLO laptop screen size (ugh)
- Moved header to pure flexbox layout

#### Personal

##### Level Up Tutorials - Apollo & React

- Continued working through videos

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
