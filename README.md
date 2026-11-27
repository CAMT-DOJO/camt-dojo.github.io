# CAMT website
Upload all extracted files and the assets folder to the root of CAMT-DOJO/camt-dojo.github.io, commit to main. Do not upload the ZIP itself. Pages should deploy automatically. Spanish is default; language choice persists locally. No build step.

## Connect services
Create a dedicated public Google Calendar in America/Panama. In its settings, copy the Calendar ID under Integrate calendar. Edit config.js and paste it into calendarId. Add the full HTTPS Instagram and Substack profile URLs in the matching fields. Commit changes. Only publish events intended for the public. No credentials needed. Until configured, the website displays coming-soon notices.

## Content
The supplied logo and two photographs are included. The training portrait is grayscale. The homepage uses the logo rather than an unlicensed stock hero photo. Confirm permission to publish the photographs and provide historical captions, instructor details and contact information before adding them. No invented names or dates.

Version 1.1: enhanced contrast on original portraits; generated illustrative dojo hero (not a photograph of CAMT).

## v1.3 configuration
Set instagram, substack and email in config.js. For Google Calendar, set public calendarId and a browser API key restricted to the Calendar API and your website referrer. Until then events are empty; optional local events use {id,title,start,end,description,location}, with ISO timestamps including offsets or YYYY-MM-DD all-day dates (exclusive end). Help bubble is a contact panel, not a chatbot. Upload all extracted files including links/ and assets/.

## v1.6
Dojo storefront hero is an approved AI-assisted reconstruction of the supplied photo. Address added; Saturday event hours are not confirmed as regular hours. Instagram configured to @camt_pty.
