# Slack Webhook integration for FileMaker Pro
-
This module enables you to post to [Slack](http://www.slack.com) from a FileMaker Pro solution using the webhook integration detailed at https://api.slack.com/incoming-webhooks.
# Setup
1. This assumes you already have Slack setup with Channels
2. Go to https://my.slack.com/services/new/incoming-webhook/ and set up an incoming webhook integration to one of the Channels in your account
3. Open the Script Workspace
4. Open the *Set Webhook URL > webhookUrl* script
5. In Line 3, paste in the hooks.slack.com/services/ full address received in Step 2.  Save the script.
6. Run the *Send "Hello World" test* script
7. Optional: Change the icon_emoji parameter in Step 1 of the Hello World test script to something other than :filemaker: - for example, :blue_heart: or any other option from [http://www.emoji-cheat-sheet.com](http://www.emoji-cheat-sheet.com)
