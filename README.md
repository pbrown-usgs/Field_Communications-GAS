# Field Communications GAS - Google Sheet Application used by the GGGSC to track personnel in the field and their communications plan(s) using Google Forms and Google Calendars.
US Geological Survey (USGS)

Geology, Geophysics, and Geochemistry Science Center (GGGSC)

Google Application Scripts (GAS)

Contact Phil Brown (pbrown@usgs.gov)

USGS Profile: https://www.usgs.gov/staff-profiles/philip-j-brown

ORCID: https://orcid.org/0000-0002-2415-7462

GitHub: https://github.com/pbrown-usgs


## FieldComEmails:

Google sheet script for sending notification emails when Google Forms are submitted.
- **SendEmailOnFormSubmit**, function that sends communications plan creation confirmation email that contains responses to the form
- **SendResponseEditEmail**, function that sends a confirmation/notification email when a response is edited.  Email contains responses edited in the form 

## FieldComAssignEditURLs:
Google Sheet Script for assigning Edit Urls, response IDs and Calendar Event IDs to form responses
- **returnLastResponseEditURL**
- **assignLastEditUrlsFieldWorkCommResponses**
- **assignLastResponseID**
- **mannuallyAssignCalendarEventIDs**
- **assignCalendarEventId**

## FieldComCalendarFunctions:
Google Sheet Script for populating Google Calendars with Form Responses and Sheet Values
- **manualPushToCalendar**
- **pushToCalendar**
- **EditCalendarEvent**
- **TestDateMath**

## FieldComOnFormSubmit:
Google Sheet Script for calling functions on an On Form Submit Trigger
- **RunOnFormSubmit**
- **CheckIfResponseIdExists**
