# awtrix-strava-app
A Strava Statistics App for AWTRIX
This App works with the Blueforcer's Awtrix framework for a 8x32 smart led matrix. It displays basic statistic information for a given (authenticated) strava athlete profile id.

## What is displayed?
Based on the Strava API `stats`-Endpoint, this app will display the following values:
- Cycling distance last 4 weeks
- Cycling elevation gain lat 4 weeks
- Cycling distance current year
- Cycling elevation gain current year
- Running distance last 4 weeks
- Running distance current year

## Setup
First, you need to create a Strava App in your profile settings under: https://www.strava.com/settings/api

Next, you need to insert the obtained *clientID* and *clientSecret* into the globals section of `Strava.bas`

After Compilation as described in the official AWTRIX documentation, you should be able to see the Strava app in the "my apps" section in the AWTRIX webinterface.

As the Strava API requires authentication via OAuth2, you need to authenticate in the app settings before using it.
