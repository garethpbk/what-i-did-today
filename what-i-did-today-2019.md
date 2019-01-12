# WHAT DID YOU DO TODAY?

## Including both professional and personal work

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
