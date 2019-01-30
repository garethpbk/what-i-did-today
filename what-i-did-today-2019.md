# WHAT DID YOU DO TODAY?

## Including both professional and personal work

---

### January 29, 2019

#### Work

##### LoanForce Insider

- Call with parties involved to kick off project and determine next steps
- Started wireframing for React rebuild (mockups were already made...so turning those into wireframes...)

##### Business Card Generator

- New feedback branch to incorporate changes from round 2 QC
- Removed logo from footer, added compliance language
- Header styling for mobile from column to row layout
- Added progress bar below spinner on submission and function to track progress of submission
- Updated welcome page language
- Upload headshot button moved below toggles, conditionally displays based on if headshot is toggled on
- Removed brand from thank you page text content
- Updated NMLS checkbox label language to be less awkward phrasing
- Branch NMLS# field on card back shows "Branch NMLS#" in edit mode
- Fields in edit mode do not display default value and autofocus when entering edit mode

#### Personal

##### Misc

- Reviewd React Hooks, played with them in Codesandbox, in anticipation of Monday release

---

### January 28, 2019

#### Work

##### Weekly WordPress Maintenance

- Updated plugins for OneTrust, plugins and themes for Tabor
- Created task in Basecamp to keep track of updates, changes, etc.

##### Business Card Generator

- ScrollUp wrapper component to return window to top of page on route change
- Tweaks to styling for mobile, esp. Safari on iPhone

##### LoanForce Insider

- First draft of Phase 3 Letters Front End checklist written
- First draft of Phase 3 Borrower Consent Landing Page Front End checklist written
- Fixed password in React rewrite of application

##### MLO Sites

- Fixed issue with flex-direction that was messing up footer (uploaded to OneTrust and CalCon, not Tabor yet)

##### Misc

- Updated website, web application, servers list

#### Personal

##### Laracasts

- Laravel from Scratch series, thru #32, lrearned about custom events and listeners

##### The Ruby Mouser

- Drew out map for first part of dark forest level, grasslands section
- Started building grasslands section in Tiled, got an idea of what new tiles need to be made

### January 26 & 26, 2019

#### Personal

#### The Ruby Mouser (new Phaser game)

- Set up project with Phaser/ES6/Webpack/TypeScript boilerplate
- Implemented: tilesets, backgrounds, controllable character

---

### January 25, 2019

#### Work

##### OneTrust GraphQL Yoga

- Figured out how to deploy to Now 2.0 successfully
- New sql branch, installed sequelize and successfully connected + ran raw queries to licensing database

##### Paid Social LP

- Updated .htaccess on server to redirect all traffic to HTTPS

##### Business Card Generator

- Moved misc methods, validation methods, & image methods to separate files (out of App index.js)
- Set up second round QC test, send to team testers

##### OneTrust Marketing

- Disabled Facebook widget that kept causing problems, requested cache clear to make sure is loading properly

##### Media Release

- Added timestamp to filenames on mailer script and uncommented admin email addresses
- Deployed to live site in preparation for first actual usage
- Swapped positions of Testimonial and Signature components

##### Compliance Language Generator

- Did research on MySQL database and SharePoint options/capabilities, tested MySQL db with GraphQL server (it works hooray)

##### Misc

- Updated icons on Bitbucket repos to match tech used

---

### January 24, 2019

#### Work

##### Business Card Generator

- Removed functionality for new employee NHO data processing (moved back into NHO separate email)
- Cleaned up code on new git branch, removing unnecessary stuff in both React and PHP code
- Fixed SVG icons in Edge being way too big (as Edge does not respect SVG inline width and height properties)
- Added default/404 route & component
- Moved App.js into App folder and started moving methods into separate files (did change handler methods)
- PHP script adds timestamp to headshot images and saves headshot images to folder on server

##### Marketing Orientation

- Restored emailing to PHP script, as business cards email now is done independently
- Added spinner display after clicking submit button

##### Media Release

- Removed unused packages and commented out currently unused imports and functions
- Deployed revamped, single-page version to Netlify

##### TaborMortgage.com

- Fixed broken image icons on Buying a Home and Refinancing pages (asked if we should keep or remove images)

#### Personal

##### Phaser Game

- Started creating enemy sprite, planned out enemies in notebook

---

### January 23, 2019

#### Work

##### Business Card Generator

- Improvements to front/back bleed images
- Investigating best way to get CMYK image to printer

##### Media Release

- Moved canvas ref and functionality to App parent component
- All three sections of media release now on one page
- All validations before continuing to summary implemented
- New SubmitRelease and ReleaseForm components to collect three sections and continue button together

---

### January 22, 2019

#### Work

##### Insider API

- Got expired SSL cert issue fixed

##### Business Card Generator

- Replaced directions and steps markdown with final copy
- Adjustments to layout and design for Tabor, including accommodating long names
- Sent new CMYK proofs to printer for review
- CMYK fixes for bleed images that are added to proof PDFs

##### Media Release Form

- Started reworking to have 3 different screen components all on one page

#### Personal

##### FLAVA

- Set up Fall 2019 conference call for proposals form
- Fixed email forwarding for new nominations person

---

### January 18, 2019

#### Work

##### Business Card Generator

- Length awareness of name entered on card front to increase padding/not break layout when name breaks to two lines
- Fixed link to licensing spreadsheet on SharePoint

##### MLO Websites

- Show Ashlie Roe logo for user aroe (show nothing for any other user) in About section

##### TaborMortgage.com

- Looked over plugins again, listed which ones have updates and which are installed but not activated/being used

#### Personal

##### Laracasts

- Laravel from Scratch Series, thru #31, learned about mailers and mailtrap

---

### January 17, 2019

#### Work

##### Business Card Generator

- Created SVG icons for card icons to replace PNG icons
- Meeting to go over status and finalize last steps before launch is possible next week

##### OneTrust GraphQL Yoga

- Attempted to switch to organizational account and move project to now v2; no luck (doesn't deploy properly)

#### Personal

---

### January 16, 2019

#### Work

##### Business Card Generator

- New problem...images have to be in CMYK to be print-ready; currently RGB
- Solved tentatively by using Cloudinary as an inbetween to convert images from RGB to CMYK
- Added functions to PHP script to extract and insert formatted Cloudinary images

##### OneTrust GraphQL Yoga

- Added type and query resolver for business card images to upload to Cloudinary to convert to CMYK
- Attempted to deploy to Now with additions, did not read .env properly, try again tomorrow

#### Personal

##### Laracasts

- Laravel from Scratch series, thru #29

##### Pixel Art

- Continued working on new 16x16 grass/dirt tile set, started creating scene

---

### January 15, 2019

#### Work

##### Business Card Generator

- Added spinner to indicate submission in progress
- Wired up actual submit button to process and send data
- Uploaded latest (final? almost final?) version of mailer script to live server
- Added base path and homepage
- Wrote QC guide, including integration with Marketing Orientation Questionnaire, and sent to team for first round QC
- Started looking into more persistant storage for marketing orientation data...perhaps read from CSV that gets saved already

##### New Hire Orientation

- Restored writing to CSV function on submission (no email, just writes to CSV and directs to business card generator link)

##### OneTrustHomeLoans.com

- Updated all plugins and themes in need of update
- Updated Thesis theme
- (Re?)installed UpdraftPlus backplugin, created manual backup
- Updated WordPress to latest version (5.0.3); using classic editor plugin

##### TaborMortgage.com

- Updated all plugins and themes in need of update
- Installed UpdraftPlus backplugin, created manual backup
- Updated WordPress to latest version (5.0.3); using classic editor plugin

#### Personal

##### Laracasts

- Laravel from Scratch series, thru #26

---

### January 14, 2019

#### Work

##### Business Card Generator

- Conditional logic for headshot attachment in admin email
- Added shipping address to body of admin email
- Attempted to add IE support with polyfills; does not really work tho lol
- Integrated Marketing Orientation Questionaire data into email (for new employee)
- Integrated post-close email information into email (for new employee)
- Updated draft image overlays for higher resolution

##### New Hire Orientation

- Removed screens 6 and 7 from flow as they are now covered by business card generator
- BusinessCards component to replace ThankYou component at end of process
- On successful submission, does not trigger email, instead directs to BusinessCards screen

##### Media Release Form

- Added babel and react-app polyfills...IE will need some serious work to get working tho x_x

#### Personal

##### Laracasts

- Laravel from Scratch series, thru #25, using mysql instead of sqlite for auth example

##### Grace Portfolio

- Updated site to new Gatsby installation (for working gatsby-image)
- Implemented gatsby-image components for all images
- Added favicon
- Switched Netlify deployment to new version of site & repo

---

### January 11, 2019

#### Work

##### MLO Sites

- Updates to Apply Now and Get a Quote buttons/links and nav menu, pushed to test server
- Updates reviewed, approved, and deployed to live server

##### Business Card Generator

- Scripting to create HTML table containing entered user values compared to LoanForce values
- Headshot image attachment in admin email
- Email body content from Basecamp for admin and user emails

#### Personal

##### Laracasts

- Laravel from Scratch series, thru #22 again, understood muuuch better

---

### January 10, 2019

#### Work

##### LoanForce Insider

- Created front-end checklist for revamp

##### Business Card Generator

- Modified PDF generation to match printer-provided card template dimensions
- Spent a lot of time fussing with bleeds for card front as PDF generator compression slightly modifies colors and sizes (next try on canvas image instead of PDF?)
- Resized draft images to fit individual card side PDFs (probably remake them in higher-quality)
- Organized data to send from front-end to PHP script
- Wrote extractor functions for all bits of data that need to be extracted in PHP

##### Media Release Form

- Wrote QC guide and sent to team for QC check tomorrow

#### Personal

##### Laracasts

- Laravel from Scratch series, went thru #21 again (understood much better this time)

---

### January 9, 2019

#### Work

##### Business Card Generator

- Tweaks for Tabor layout - nmls in top right corner, labels for contact fields
- Error indicator for upload headshot button if headshot toggled on but not uploaded
- Responsive mobile styling for all screens
- Reworked handling of submission (everything takes place in App component now), broke up into multiple functions
- Continued PHP scripting to process PDF and send emails
- Created images to watermark user PDFs as draft

#### Personal

##### Laracasts

- Laraval from Scratch series, thru #22 (this is confusing stuff, need to rewatch #21 & #22)

---

### January 8, 2019

#### Work

##### OneTrust GraphQL Lighthouse

- Determined that live deployment is not working because PHP version too old (7.0.33; needs > 7.1)

##### Business Card Generator

- Tried to use pure CSS to create Tabor divider line with clip-path and linear-gradient; didn't work very well
- Created SVG line extension and setting up refs and props to show line and push main SVG left
- State and props and functions to correctly display Tabor line position in creation and approval screens
- Use html2canvas library to save card preview elements as canvas and then base64 images
- Started writing PHP to generate business card proof PDF (it works! pretty well!)

#### Personal

##### FLAVA

- Updated Spring 2019 conference forms plus new W9 form

##### Catgame

- Started beach scene mockup and experimented with gradient transition into background dark color

---

### January 7, 2019

#### Work

##### Business Card Generator

- Validation for card approval checkboxes

##### Media Release Form

- Function for setting direction of transition slide on mouse over of navigator buttons
- Added basepath to config and to all navigators
- Tested and deployed to live onetrusthomeloans.com server
- Scaling space alotted for signature in PDF based on height of signature image
- Started writing real readme.md

##### OneTrust GraphQL Lighthouse

- Figured out how to work with Lighthouse GraphQL server for Laravel
- Imported schema (same as graphql-yoga server) and set up resolver for Mlo type query
- Attempted to deploy to onetrusthomeloans.com server, did not work (requires more research)

#### Personal

##### Laracasts

- Laravel from Scratch series, thru #21

---

### January 5 & 6, 2019

#### Personal

##### Grace Portfolio

- Fixed about text section rendering as raw markdown

##### Udemy Pixel Art Tutorial

- Finished section on tiles and scene mockup

---

### January 4, 2019

#### Work

##### Branch Pages

- Designed CTA buttons for request consultation and contact us
- Added localCallNumber field to branch graphql query to render in button
- Fix for MS Edge display of branch tiles (flexbox space-evenly doesn't work in Edge)
- Confirmed that redirect issues have been fixed

##### Business Card Generator

- Moved around stuff on preview screen
- Validation for shipping address fields on attempted submission

##### Misc

- Server/SSL call to figure out responsibilities and such

#### Personal

##### Laracasts

- Laravel from Scratch series, thru #20

---

### January 3, 2019

#### Work

##### OneTrust GraphQL Yoga

- Tried to debug slow performance on VPS; concluded VPS is just slow (probably unusuable unless fixed)

##### Business Card Generator

- Field validations for card fields (content not validated, just not same as default and not blank)
- Full validation for card fields and setup fields before navigation to approval screen allowed

##### Drip Campaigns

- Updated birthday campaign emails for all three brands

##### Branch Pages

- Investigating redirect issues; determined problem comes from onetrusthomeloans.com root htaccess rules
- Solved htaccess issues, site now respects client-side routing and forces https (check again tomorrow to make sure)
- Added footer with compliance info to home route

#### Personal

##### FLAVA

- Edits to Spring 2019 conference registration and registration payment forms

##### Laracasts

- Laravel from Scratch series, thru #16

##### Udemy Pixel Art Tutorial

- Finished section on colors and materials

##### Misc

- Randomly found a cool color #1d127d

---

### January 2, 2019

#### Work

##### Media Release Form

- Finished responsive styling for all screen sizes, including error message positioning
- Added line to mailer script to increase memory limit to 256mb
- File size upload limit of 5mb for testimonial image

##### Business Card Generator

- Edit icons toggle between red and blue (or white) depending on if field has been touched/different from default

##### Marketo

- Fixed image on new 'i've moved' email to be responsive (removed fixed height)

##### Compliance Updates

- Updated footer with new compliance language: joinonetrust.com (also fixed .htaccess to force https), onetrusthomeloans.com, onetrusthomeloans.com/theloanprocess, onetrustmarketing.com, tabormortgage.com

##### Misc

- Created phpinfo.php file for onetrustmarketing server
