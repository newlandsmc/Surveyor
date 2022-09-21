# Surveyor

A plugin to collect metrics on new player sources

## Initial Ask
I want to provide a survey to new players asking where they found the server or who invited them
once they finish it, the  "thank you" page will provide a coupon code for a free loot crate from the store

i want to have a plugin on the server side that:
1. Provides new players with a welcome message in chat asking them to do the survey
2. Reminds them 10 minutes later if they didn't complete it yet
3. Thanks them for completing it via a chat message after they do, and queue the message for the next time they join if they are offline
4. If they specified another player as a "referrer" I want to thank THEM via a chat message for inviting someone and provide them a free crate as well. again, queue the message for next time they join if they are offline

some details I have to work out still:
- how can we provide the referrer with a free crate? I'd like to go through the store, but we can't dynamically create coupon codes...
- will this plugin run on lobby, or somehow sync across all servers?
