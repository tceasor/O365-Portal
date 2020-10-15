# O365-Portal

The O365 Power Portal app is a centralized location to store and access all of the your favorite pages for your product subscriptions.

Do you ever forget or get lost in all of the apps on your phone?
Are you a collaborative, intuitive, or business man/ woman?
Need a fast easy simple fix to declutter you o365 work space?
This app is for you!
The benefit to using this app is that you're always just one click away from your next work forlder or collaborating station. Keep it centralized simple and clean with this power app!

# Dependencies:
Visual studio code: Git extentions, GitBash extentions 

# Lets Get started: 
(I have a windows PC, so I use Windows Terminal for my oreferred commandline)
# Step 1: Download Zip files for node js and ionic app : 
https://nodejs.org/en/
 ionic app on commandline 
> npm install -g ionic@latest

# Step 2: Create Ionic side menu app Project and run it in browser
>ionic start [project name] sidemenu --type=angular
>cd .\[project name]
>ionic serve 
*after portal opens...on windows to create app look: go to "setting  ... on the top left of browser" ---> "extentions"-->"apps"-->"install this site as an app " and minimize screen*

# Step 3: Generate New pages
>cd .\[project name]
> ionic generate page pages/[new page name]
 *the project will generate a new page and root in the app rooting module. these roots will be the main means of navigation through the app pages.
 
 
 # Step 4: App Appearance and functionality: Html, ts
 edit the .html page and add buttions with links to the sites: create Buttons(documatation for button styling): https://ionicframework.com/docs/api/button, rout links using the following in the button --> href= "https://[website name]"
 
 the .ts page is for creating components/functions that will be used on the html pages
 # Step 5: Navigation: rooting module
 by adding roots to a rooting module, you are changing the tabs or pages that pages will navigate to.
