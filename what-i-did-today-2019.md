# WHAT DID YOU DO TODAY?

## Including both professional and personal work

---

### April 4, 2019

#### Work

##### LoanForce Insider

- Turned off Google Geocode address formatting to stop sending requests (for now)
- Download button & text component for modifying letters
- Disable modified letter preview button when sending request
- Success component for successful letter modification/creation
- Organized components for animating between success and loan information views
- Added logic to display modified letter in letter history from front-end state
- Request to create new letters (with email and conversation log write) for modified letter on "download new letter" click
- Animation for moving between successful new letter and letter information pages

---

### April 3, 2019

#### Work

##### LoanForce Insider

- Fully built out modify letter component with all slides, formula for updating values on change, reset functionality
- Tweaked pose animations for better transitions between modify/letter components

##### Azure Crane Capital

- Tested out wp-graphql plugin, rigged up gatsby site with it to pull in page content

#### Personal

##### Misc

- Started building useGraphqlFetch hook (maybe try to make it a real package eh)

##### Stravisualize

- Styling for activity content, adjustment to calories type

---

### April 2, 2019

#### Work

##### LoanForce Insider

- Split letter widget and letter history into totally separate components and adjusted styles & mobile/desktop display accordingly
- Placeholder permissionLevel flag for mobile buttons in loan information component
- Loading state for preloading letter in preload hook
- Moved letter preload to top-level PreLoan component (to prevent refetching when letter buttons component rerenders)
- Letter buttons disabled while letter is loading, disabled style added
- Adjustments for letter history components to have margin included instead of in letter buttons
- Modify letter component set up
- Sliding transition for switching between letter and modify letter components
- Reorganized all styled components into one directory at PreLoan top-level component
- Added react-compound-slider for slider components
- Prequal/preapproved letter processing includes min and max loan amount and max LTV
- Set up loan amount slider with constraints and styling
- Tested preview letter function with modified loan amount value (it works hooray)

##### Marketo

- Figured out Velocity scripting for marketing communications owner phone to show if exists

---

### April 1, 2019

#### Work

##### LoanForce Insider

- Checked out new Context branch to reorganize context
- Replaced most of AppContext (except for modal) with LoggedInContext for better separation of code
- Reorganized styled components for Dashboard, ForgotPassword, Login, Loan, PreLoan components
- Use prop boolean for loggedIn in Header component instead of checking context values (why did I do that lol)
- Level One letter now preloads on component mount instead of being triggered by click (it doesn't change so this is better)
- Level One letter download button opens PDF in new window and automatically downloads file with generated filename
- Fixed specificity issues with person labels on LoanHeader components with new styled component instead of inheritence
- Level Two letter buttons component created
- Placeholder permissionLevel value to determine which letter components to display
- Tested create loan letter API successfully, created 2 letters for sample preapproved loan
- Letter creation history component to display created letters
- Resized PreLoan sections to better fit created letter history and loan information values
- Reported bug with profile pic and company logo uploads in dev API, backend team fixed

##### Azure Crane Capital

- Set up local WordPress site for testing stuff
- Looked at/thought about how to structure custom content needs
- Added ACF to development and live WP sites

##### Misc

- Weekly WordPress maintenance for OTHL (no updates) & Tabor
- Added 4/1/19 announcement to OneTrustMarketing site

---

### March 31, 2019

#### Personal

##### FLAVA

- Finished & tested Fall 2019 registration form and payment form
- Wrote Node.js server to transform GF registration & membership entries into ACTFL spreadsheet format and generate spreadsheet

##### Stravisualize

- Unit conversions for Activity resolver, started building out Activity component/page

---

### March 29, 2019

#### Work

##### Marketo

- Milestone progress graphics for milestone emails created
- Milestone progress graphics inserted into milestone emails for all brands & emails

##### LoanForce Insider

- Renamed RootContext file in preparation for moving AppContext out of App component and to its own file
- Loan page direct loan fetching uses same function to get and cache loan as dashboard loan hover (removed duplicate logic & files)

#### Personal

##### FLAVA

- Fixed bug with membership registration for check payment

##### Stravisualize

- Added leaflet.js maps for individual activities
- Added @mapbox/polyline to server to decode polyline data, added decoded polyline fields to activity type
- Individual activity component routes set up with query on load
- Added posed router, messing around with route transitions

---

### March 28, 2019

#### Work

##### LoanForce Insider

- Revised loan information layout to use table instead of lists
- Broke up loan letter component buttons into separate level one component buttons
- Regenerate letter logic moved to custom hook
- Level one permission buttons displayed in proper places on mobile and desktop
- Added react-pdf and started working on rendering regenerated pdf preview in modal (may keep or may go for html render)
- App function to fetch and cache individual loan works for active, funded, prequal, preapproved loans (condense into one hook prolly)
- Test preapproved loan (duplicated test prequal loan), now know how to create test prequal/preapproved loan data and what flags do what
- Preapproved loans added to dashboard
- Replaced loan cache state in App with custom hook for loan cache with useReducer

##### OneTrust Marketing

- Added social media calendars icon and link to site

---

### March 27, 2019

#### Work

##### LoanForce Insider

- PreLoan component setup with loan information section created and styled
- PreLoan letter widget component set up (for level 1 permission loans)
- Formatting for data to send to endpoint to create & regenerate letters
- Tested POST call to regenerate letters, mostly works, a few tweaks needed

##### Misc

- Fixed real estate invite email HTML

#### Personal

##### FLAVA

- Set up F2019 Participant Registration & Payment forms

---

### March 26, 2019

#### Work

##### Media Release

- Updated agreement text with new brand-inclusive language
- Swapped Othl component for AllBrands component
- Updated mailer script with new language
- Uploaded updated version to both OTHL and CalCon servers

##### Azure Crane Capital

- Updated mobile wireframes, saved in Basecamp & Sharepoint, sent to designer

##### LoanForce Insider

- Started separating out Active & Funded loan from Prequalified & Preapproved loan components

#### Personal

##### Stravisualize

- Wavy text animation for header (ugly markup rip)
- Added router
- Links to individual Activity components

---

### March 25, 2019

#### Work

##### LoanForce Insider

- Individual loan detail fetching and formatting logic extracted to custom hook
- Fixed loan partners hook not using reduce properly, replaced with a filter & Set method
- Notified API team that all user loans on dev API is currently not working properly (is fixed)
- Set up test prequalified loan in dev Encompass (still needs work)
- Switched from live API to dev API now that test data is available

##### Misc

- Weekly WordPress maintenance/updates for Tabor and OneTrust

---

### March 22, 2019

#### Work

##### LoanForce Insider

- Re-cloned AngularJS repo cuz original one was borked
- Registration submit logic, confirmed as working with data in right shape (receives proper error response, can't fully test yet tho)
- Created HTML email for buyer agent permission granted notifications

##### Azure Crane Capital

- Revised desktop wireframes

#### Personal

##### Stravisualize

- Added react-pose, started tryna implement animations for toggling activity feed types

---

### March 21, 2019

#### Work

##### LoanForce Insider

- Various styling tweaks across application as relayed by team review
- Drawer component loan partners logic moved to custom hook
- Moved registration form state to parent index component, pass state & dispatch through props
- Registration submit button component and logic for validating required fields then submitting form values

#### Personal

##### Stravisualize

- More generic resolver for athlete stats (includes all, ytd, recent)
- YTD run stats component
- Icons to toggle visibility of different activity types in feed

---

### March 20, 2019

#### Work

##### LoanForce Insider

- Fetch Google-formatted addresses with Promise.all, instead of at component level
- Handle missing values for profile gender, headshot, company logo
- Get loan type of individual loan on loan page load (checks if processed already, if not run through processing functions)
- Loading spinner for individual loan page based on if loan type has been determined
- Call to go over functionality of new API additions for letters
- Rest of registration fields implemented
- Registration profile and company logo file upload fields implemented

---

### March 19, 2019

#### Work

##### Azure Crane Capital

- First draft of desktop wireframes with skewed and simpler style alternates
- First draft of mobile wireframes completed
- Explored animations for menu with slant transforms

##### Misc

- BAI training on Marketing & Advertising
- Read about Encompass Borrower Widgets and thought about how to potentially leverage them

---

### March 18, 2019

#### Work

##### Azure Crane Capital

- Wireframes for desktop site (first draft more or less done)

##### Misc

- WordPress updates for OTHL & Tabor
- Referral partner HTML email template and example
- Uploaded updated flowpaper pitchbook

---

### March 15, 2019

#### Work

##### LoanForce Insider

- Tweaked formatAddress function to organize it better (split into two functions)
- Moved format addressing fetch call to Google Geocode API to individual component level with custom hook
- Ref in AppContext for keeping track of addresses that have been retrieved

---

### March 14, 2019

#### Work

##### LoanForce Insider

- Custom hook for fetching profile data at App component level
- Switched out useState for useReducer for controlling profile form inputs
- Custom hook for handling image uploading logic with filereader
- Custom hook for loan fetching logic on initial App load
- Fixing problems with loan processing/formatting to sort out active loans
- Renderfunded loans on dashboard (lil buggy tho)
- Limited number of loans that can be rendered at once to 200 (temporarily at least)

---

### March 13, 2019

#### Work

##### LoanForce Insider

- Disable route transitions for profile page
- Profile state all kept in one same piece of state in App context instead of copying in Profile custom hook (many bugs)
- Moved functions for controlling/editing profile state out of custom hook
- First set of fields for registration set up with reducer
- Accidentally registered unknown@unknown.com and discovered thousands of test loans o\_\_\_O

#### Personal

##### Context Hooks Presentation

- Gave presentation at SDJS React meetup

---

### March 12, 2019

#### Work

##### LoanForce Insider

- Responsive mobile styling for in process loan detail page
- Responsive mobile styling and various style tweaks for profile page

#### Personal

##### Context Hooks Presentation

- Finished first draft of slides

---

### March 11, 2019

#### Work

##### Marketing Orientation Questionnaire

- Fix for height scaling issues on MLO laptop screen sizes

##### LoanForce Insider

- Responsive mobile styling for dashboard, header, footer components
- SVG icons (fontawesome via Wikimedia) for mobile profile and logout

##### Misc

- Weekly WordPress updates for OTHL and Tabor
- Tabor Betheme update broke site (500 error), fixed by reverting from child to regular theme (zzz)
- Backed up Tabor site with UpdraftPlus
- Added reCaptcha to Tabor site (registered with OTHL gmail) and consultation Gravity Form

#### Personal

##### Context Hooks Presentation

- CodeSurfer for code examples
- Slides on nested context with contrived example and screenshot of production app

---

### March 8, 2019

#### Work

##### LoanForce Insider

- Set up Registration component and route
- Logic for submitting registration request and handling response (failure and success)
- Header component links to login page if user not logged in (prevent memory leak from unmounted App component)

#### Personal

##### Context Hooks Presentation

- Started presentation slide deck, drafted first batch of slides, set up github repo

---

### March 7, 2019

#### Work

##### LoanForce Insider

- Error handling with view of error messages for login
- ResetPassword component and route set up
- Logic for handling reset password with code from query string
- Cleaning up, reorganizing, modularizing project

#### Personal

##### Stravisualize 2.0

- Bangers and Oswald fonts, headers use former and most text uses latter
- Styling for stats card
- Footer component with 'powered by Strava' svg
- Total stats type time fields changed to String, function to convert seconds to hours & minutes

---

### March 6, 2019

#### Work

##### LoanForce Insider

- Error and success message handling for profile password change attempts
- Header conditionally renders login link or profile & logout links if user logged in or out
- ForgotPassword component and route set up
- Functionality for forgot password, with input, submission, and response handling
- Added mock loan data from AngularJS project, not useful for much rn tho
- Reset password change form state on successful change
- Margins for password change form labels

##### Misc

- Enabled anti-spam honeypot on Tabor consultation form

#### Personal

##### Stravisualize 2.0

- Type added to activity list query and card
- SVG icons from Material Icons for run and cycle
- AthleteStats type and type for all run, all ride, all swim stats
- Resolver for getting all athlete stats of any of the 3 types
- Client query for all total run stats and basic component for rendering
- Created svg treadmill icon based on Material run icon
- Added subType field to Activity type and activityList resolvers for inside/outside

---

### March 5, 2019

#### Work

##### MLO Sites

- Tweaked mortgage calculator PHP config and Angular template view to allow 3 decimal places

##### LoanForce Insider

- Password component added to profile section
- Input fields and state/change handler and API call for password changes
- Router added to profile section
- Tweaks to routing for proper transitions/no weird animation stuff
- Submit button as reuseable component instead of identical separate components
- Profile header icon/title links to profile page

#### Personal

##### Stravisualize 2.0

- Added date-fns to server to format date strings
- Convertor function for average speed in min/mile (changed schema type to string)
- Colors for theme, started styling components
- Set up remote repo on github

---

### March 4, 2019

#### Work

##### LoanForce Insider

- Reorganized ProfileContent component into its own directory
- Built out submit component and added spinner with submitting state
- Formatting for birth date field and input with date-fns
- Placeholder and default values for profile field inputs
- File uploads for headshot and company logo in profile
- Headshot and company logo new uploaded images post to API and save to profile
- Fix so co-borrower address doesn't get formatted when no co-borrower exists
- Fix to how loan status milestones are displayed to hide past non-completed milestones
- Expand/open controls for each item in drawer menu for slightly better UX
- Call logout function in top right Logout link instead of link
- Loan contact cards render email addresses as links

##### OneTrust Marketing

- 3.4.19 update added to site, attempted to deploy (tbd if it worked zzz)

##### Misc

- Weekly WordPress updates for Tabor (none for OneTrust)

#### Personal

##### Stravisualize 2.0

- Set up grid, theme, added packages, directory structure
- Building out activity feed components
- Replaced start_date with start_date_local in resolvers

---

### March 2 & 3, 2019

##### Stravisualize 2.0

- Set up client project and hooked up graphql server to Apollo client

---

### March 1, 2019

#### Work

##### LoanForce Insider

- Broke out ProfileContent component for better organization
- Edit mode and field data for first and second sets of profile fields
- Radio options for gender field
- Date picker/input for birthDate field
- Function for submitting updated profile data to api

---

### February 28, 2019

#### Work

##### Business Card Generator

- Pushed updated language and headshot placeholder to live site
- Dynamic year in footer instead of static 2018

##### LoanForce Insider

- Tweaks to loan contacts in header hover actions (displaying contact card) and styling
- Functional Profile component and setting up subcomponents
- Logic for fetching headshot base64 string from api and storing in state
- Built layout and view for all values in Profile component
- Netlify project for test deployments (loanforce-insider.netlify.com)
- Change handler for profile fields

#### Personal

##### Stravisualizer 2.0

- Set up repo and server project
- graphql-yoga server connected to Strava API and returning activity data

---

### February 27, 2019

#### Work

##### LoanForce Insider

- Tried extracting individual loan fetching to custom hook, wasn't very useful tho
- Function to group contacts for displaying in list
- LoanContacts component built out & processing contacts on load
- LoanContactCard component for each contact to be displayed
- Address formatting for borrower & coborrower added to loan page individual loan fetching (might have to change)
- Expandable boxes for each contact on loan detail page
- Login data stored in session storage, redirect to login page if not found

##### Azure Crane Capital

- Created placeholder index.html with logo and threw up on server
- .htaccess rules for forced https redirects

#### Personal

##### Recipe App (tentatively titled Garlick)

- Set up project server files and got basic graphql-yoga server running
- Exploring database options starting with MongoDB Atlas

---

### February 26, 2019

#### Work

##### Media Release

- Removed OTHL logo from header, added all 3 brand logos to body
- Hosted mailer and application on CalCon server
- Added all 3 logos to PDF template
- .htaccess for forced HTTPS (just on this subdirectory of CalCon server)
- Styling adjustments for logo and header sizes for more initial visibility

##### Business Card Generator

- Updated directions with new aspect ratio language and link
- New placeholder image with ratio included

##### LoanForce Insider

- Better formatting of loan detail data to manage contacts

---

### February 25, 2019

#### Work

##### LoanForce Insider

- Coborrower data in loan object and associated styling
- Loan status box styling
- Grid moved from App to sub-components
- Component for loan dates and contacts for in process loan
- Added all possible contacts to loan page API call (still need to add to onMouseOver dashboard call)

##### Misc

- Weekly WordPress updates for OneTrust & Tabor
- Finished performance review

#### Personal

##### FLAVA

- Tweaks to exhibitor forms and info page for launch preparation

##### Zine Site

- Added home page to front end
- Field in Contentful for home page text

##### Misc

- Installed Postgres and went through Express + Postgres REST api tutorial

---

### February 23 & 24, 2019

##### Personal

- FLAVA Exhibitor forms for 2019 fall conference (CfP, Registration, info page)

---

### February 22, 2019

#### Work

##### LoanForce Insider

- Added posed router with slide transition to App component
- Simple cache for loading loans on hover, replacing App loaded loan context state
- Loan entries in Drawer link to loan page
- Display functions for expanding/hiding for Drawer Partners & Profile and Dashboard Loans
- Loading state in App to slightly delay rendering
- Dev access token as a config var
- API call for loan details when loan page directly loaded
- Design tweaks to loan pages

##### Misc

- Completed first three sections of performance review

---

### February 21, 2019

#### Work

##### Signature Generator

- Changed owner of signature directories on VPS to admin user (can now use SFTP hooray)
- Updated CalCon signature with new compliance language
- Fixed extra bullet point appearing in non-sales CalCon signatures

##### Media Release

- Removed word Consumer's from testimonial section

##### LoanForce Insider

- Exported new menu icons as svg
- Reworked Drawer component to be its own directory with subcomponents
- Drawer menu items components basic setup
- Moved AppContext to wrap entire App tree
- State in Drawer component for extracting partners from raw loans
- Logic to display partner and loans lists in Drawer component
- Custom hook for toggling Drawer items and svg for toggle icon
- Ref to DrawerLoans component to provide height of list for height transition

---

### February 20, 2019

#### Work

##### LoanForce Insider

- User login logic using root context provider to communicate between Login and App components
- Rewriting App component using hooks instead of class
- Rewriting existing Dashboard and Loan components using hooks

##### Consent Landing Page

- Added design colors
- Logos component and SVG logos added
- Polyfills for IE support lol

##### Business Card Generator

- Uploaded tweaked version to staging site

---

### February 19, 2019

#### Work

##### Weekly WordPress Maintenance

- Updated plugins for OneTrust, plugins and themes for Tabor

##### Business Card Generator

- Various tweaks to layout and field lengths and such based on QC feedback

##### Consent Landing Page

- Added basepath to route changes
- Deployed working version of site to live CalCon server

##### LoanForce Insider

- Upgraded packages to latest version (gimme dem hoooooks)
- Added proper favicon and site title
- Created Login component with form, controlled inputs, and API request for logging in
- Added routing to root index to account for Login
- Added polished and darken color theme helper function
- Created root context component and hooked up Login component (user values passed to context on login)

##### Marketo

- Sort of fixed broken HTML in email that Outlook didn't like

---

### February 16, 17, 18, 2019

#### Personal

##### Phaser Game

- Dead tree sprite, gravestone sprite, new cloak character sprite

---

### February 15, 2019

#### Work

##### Consent Landing Page

- Figured out how to manually do bullet points w/ FPDF (is tedious but works)
- Finished scripting for generating PDF and sending emails (tested locally)

##### Misc

- Did BAI videos due today

---

### February 14, 2019

#### Work

##### Consent Landing Page

- Better method of saving signature canvas (using onMouseLeave event)
- Validation on submission for fields and signature canvas
- Agreement and Form components together for routing (set up routing)
- Added Success component and route
- Added ScrollUp component (wraps Success)
- Added 404 component and route
- Directory in Laragon to host locally

---

### February 13, 2019

#### Work

##### Consent Landing Page

- Content and styling for Footer component
- Content and stsyling for Agreement component (added raw.macro and react-markdown)
- Component and mask for SSN digits (added react-number-format)
- Change handler method for input (methods in separate files)
- Added validators for all fields
- Method for populating current date in App component (useEffect hook)
- Signature pad component with ref, blank data url on load, clear function

---

### February 12, 2019

#### Work

##### LoanForce Insider

- Went over design mockups and walked through functionality/UX
- Reorganized App component as folder containing components that are visible everywhere
- Upgraded packages (deleted lockfile and ran yarn)
- Converted Drawer component to functional and used hook for state (coooooooool)
- Transitioning design of React version of app to match new mockups

##### Consent Landing Page

- Created project, removed default CRA files, set up repo on Bitbucket
- Set up basic project directory structure
- Added packages, set up styled-components

##### Business Card Generator

- Fixed wrong logo component displaying with headshot off and Club logo on
- Set up new test deployment at "-staging"
- Wrote QC guide for new Club logo and sent out to team

---

### February 11, 2019

#### Work

##### Weekly WordPress Maintenance

- Updated plugin and theme for Tabor, theme for OTHL

##### Business Card Generator

- Special toggle logic for chairmans and presidents club seals
- Layout adjustments for Tabor including line and various tweaks to accomodate chairmans and presidents club
- Special SVGs with adjusted width for when club selected (html2canvas needs this to scale logos properly)
- Moved all submission methods to separate file from App component (all methods separated out now)

---

### February 8, 2019

#### Work

##### MOQ

- Troubleshooting for continue/previous buttons not visible at some screen sizes
- Uploaded fixed version to production server
- QC checklist for updates and fixes, sent to team

##### Business Card Generator

- Exported presidents club and chairmans club image SVGs
- Toggle sliders for presidents club and chairsmans club

##### LoanForce Insider

- Sent requirements, fillable PDFs, final wireframes out

#### Personal

- GraphQL Yoga + Now Article

- Finished article, ran through for testing successfully
- Published on dev.to

---

### February 7, 2019

#### Work

##### LoanForce Insider

- Finished requirements including detailed letter fields

#### Personal

##### GraphQL Yoga + Now Article

- Finished server and first draft of article
- Ran through from fresh project once to ensure it works (needs a few tweaks)

---

### February 6, 2019

#### Work

##### LoanForce Insider

- Further tweaking and revising Phase III and current wireframes, mobile and desktop (finalized and passed to designer)

#### Personal

##### GraphQL Yoga + Now Article

- Set up graphql-yoga server, started schema and resolvers

---

### February 5, 2019

#### Work

##### LoanForce Insider

- Revised desktop wireframes for Phase III
- Revised checklist for phase III
- Finished first draft of front-end requirements for Phase III (including consent landing page)
- Revised checklist for consent landing page

---

### February 4, 2019

#### Work

##### OneTrustMarketing

- Added 2/4/19 announcement
- Slight adjustment to footer margins on mobile/tablet widths

##### Weekly WordPress Maintenance

- Updated plugins and themes for OneTrust and Tabor

##### Modular Resource Center

- Updated borrower FAQ doc (new file on server to prevent reading cached old file)
- Updated email address for borrower draw request card
- Attempted installing getting gatsby-image set up, did not work and broke everything (have to restart with new starter later)

##### LoanForce Insider

- Finished wireframe for buyer consent landing page (first draft)
- Started comprehensive front-end requirements doc for phase iii including borrower consent landing page
- Updated desktop wireframes for new prequalified and preapproval sections to be added
- Shared desktop wireframes and commented a lot about fields, actions, etc.

---

### February 2 & 3, 2019

#### Personal

##### The Ruby Mouser

- Fixed accidental cmyk noise issues with tileset image
- Progress towards figuring out how to best do dynamic backgrounds
- Grass tile edge/corner pieces

---

### February 1, 2019

#### Work

##### LoanForce Insider

- Fixed typos in BRD on SharePoint
- Clarified how consent form process will work
- Started desktop wireframes for borrower consent landing page

##### OneTrust GraphQL Yoga

- Updated Cloudinary information from test to live OneTrust account
- Added folders to Cloudinary functions for better organization
- Set now secrets and moved from deploying to now with explicit .env to using secrets
- Removed alias from now 1.0 deployment and aliased now 2.0 deployment to onetrust-graphl-yoga.now.sh

##### Marketing Orientation Questionnaire (aka New Hire Orientation)

- Updated videos on screens 1 and 10
- Deployed updated version of MOQ to production server at live URL

##### Business Card Generator

- Added all state copy (minus image base64) to data that gets sent to PHP
- Added developer email that includes all state for debugging purposes
- Added Wistia script and component and videos to welcome and success pages
- Deployed to production server in anticipation of Monday launch

#### Personal

##### Misc

- More hooks in Codesandbox, useGraphQl hook to extract data fetching (with fetch()) to custom hook

---

### January 31, 2019

#### Work

##### Misc

- Put together quick demo of onetrusthomeloans.com + Gatsby to show how headless WP works
- Hosted demo on onetrustmarketing.com and made notes in preparation for call w/ IT

##### LoanForce Insider

- Continued working on mobile wireframes
- Clarification of next steps to take and needed documentation

##### Business Card Generator

- Added new CalCon logo

#### Personal

##### Misc

- Filed PR for Gatsby monorepo to update starter readmes to reflect removal of .prettierrc (approved hooray)

---

### January 30, 2019

#### Work

##### Loanforce Insider

- Continued working on desktop wireframes for tweaks to existing design & new additions
- Started mobile wireframes for tweaks & new additions

##### Business Card Generator

- Deployed most recent version with updates/tweaks from yesterday to live site (tested, is good, works)
- Meeting to figure out last few bits and tweaks before can be launched (aim for Friday)

#### Personal

##### Laracasts

- Laravel from Scratch series, thru #34, learned about notifications and Laravel + front end

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
