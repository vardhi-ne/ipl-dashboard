# ipl-dashboard
let's build a IPL Dashboard App

https://github.com/vivekreddy-k/IPL-Dashboard-App-react-20#refer-to-images-below

Design Files
Extra Small (Size < 576px) and Small (Size >= 576px) - Home
Extra Small (Size < 576px) and Small (Size >= 576px) - Team Matches
Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Home
Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Team Matches


Set Up Instructions
Download dependencies by running npm install
Start up the app using npm start

Completion Instructions


Functionality to be added

The app must have the following functionalities

When the app is opened, Home Route should be displayed
When the Home Route is opened,
Make HTTP GET request to the teamsApiUrl
loader should be displayed while fetching the data
After fetching the data, the list of teams should be displayed
When a team card in Home Route is clicked,
Page should be navigated to the Team Matches Route with the URL /team-matches/:id
When the Team Matches Route is opened,
Make HTTP GET request to the teamMatchesApiUrl with the team id to get the recent matches data of the team
Example: https://apis.ccbp.in/ipl/KKR
loader should be displayed while fetching the data
After fetching the data, the team banner, latest match, and list of recent matches should be displayed

API Requests & Responses

teamsApiUrl

API: https://apis.ccbp.in/ipl

Method: GET
Description:
Returns a response containing the list of all IPL teams


teamMatchesApiUrl

API: https://apis.ccbp.in/ipl/:id

Example: https://apis.ccbp.in/ipl/KKR

Method: GET
Description:
Returns a response containing details of all recent matches of a team

mplementation Files

Use these files to complete the implementation:

src/App.js
src/components/Home/index.js
src/components/Home/index.css
src/components/TeamCard/index.js
src/components/TeamCard/index.css
src/components/TeamMatches/index.js
src/components/TeamMatches/index.css
src/components/LatestMatch/index.js
src/components/LatestMatch/index.css
src/components/MatchCard/index.js
src/components/MatchCard/index.cs

