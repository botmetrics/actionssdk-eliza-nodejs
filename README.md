# Actions On Google Actions SDK Eliza Sample using Node.js

This sample includes code from elizabot by N. Landsteiner, based on the original ELIZA program by Joseph Zeizenbaum (MIT 1966).

## Setup Instructions

### Pre-requisites
 1. Actions SDK: [https://developers.google.com/actions/develop/sdk/getting-started#getting-started](https://developers.google.com/actions/develop/sdk/getting-started#getting-started).
 1. Google Cloud SDK: [https://developers.google.com/actions/develop/sdk/getting-started#deploy-your-action-web-service](https://developers.google.com/actions/develop/sdk/getting-started#deploy-your-action-web-service).

See the developer guide and release notes at [https://developers.google.com/actions/](https://developers.google.com/actions/) for more details.

### Steps
 1. Deploy this app to your preferred hosting environment (we recommend Google App Engine).
 1. Update the action package, eliza.json, with your endpoint URL.
 1. Preview the action using the gactions CLI: ./gactions preview --action_package eliza.json --invocation_name "eliza action" --preview_mins 1234
 1. Use the gactions simulator to test the action (try "talk to eliza action"): ./gactions simulate

For more detailed information on deployment, see the [documentation](https://developers.google.com/actions/samples/).

## Tracking Your Bot's Conversations

Set up a Google Home bot on [Botmetrics](https://www.getbotmetrics.com) and get the API Key and Bot ID for the bot. Set the environment variables `BOTMETRICS_API_KEY` and `BOTMETRICS_BOT_ID` with these values. Add `botmetrics` to your `package.json` and add the `Botmetrics.track` API calls to your code as shown [here](https://github.com/botmetrics/actionssdk-eliza-nodejs/commit/c205f261bb0afc475cc56f74d2e7cbd8eb8b9c08).

## References and How to report bugs
* Actions on Google documentation: [https://developers.google.com/actions/](https://developers.google.com/actions/).
* If you find any issues, please open a bug here on GitHub.
* Questions are answered on [StackOverflow](https://stackoverflow.com/questions/tagged/actions-on-google).

## How to make contributions?
Please read and follow the steps in the CONTRIBUTING.md.


## License
See LICENSE.md.

## Terms
Your use of this sample is subject to, and by using or downloading the sample files you agree to comply with, the [Google APIs Terms of Service](https://developers.google.com/terms/).

## Google+
Actions on Google Developers Community on Google+ [https://g.co/actionsdev](https://g.co/actionsdev).
