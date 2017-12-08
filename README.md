PLAYERUNKNOWN'S BATTLEGROUNDS overlay for the game streams
==========================================================

Usage:

1. Obtain your personal API KEY on https://pubgtracker.com/site-api

2. Setup the cron job as example:

`*/15 * * * * /usr/bin/curl --header "TRN-Api-Key: {API_KEY}" --output /full/path/to/data.json https://api.pubgtracker.com/v2/profile/pc/{YOUR_GAME_NICKNAME}`

3. Check the cron job by manual copy-paste and run (you should get the file as described).

4. Deploy the content of this repo to the same directory.

5. Open `overlay.html` in your browser.

6. Update `overlay.css` as you wish.
