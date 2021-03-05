# Flight_Deals
A script to look for flights deals under a trigger price for our chosen destinations

The flight deals looked for are stored in a Google sheet with destinations, airport codes and lowest price we're interested in

You need to set your starting city destination in main.py line 6 as a IATA code

You also need to set the environment variables for the APIs from your accounts:
-Google Sheet Data Management - https://sheety.co/
-Kiwi Partners Flight Search API (Free Signup, Requires Credit Card Details) - https://partners.kiwi.com/
-Tequila Flight Search API Documentation - https://tequila.kiwi.com/portal/docs/tequila_api
-Twilio SMS API - https://www.twilio.com/docs/sms

Finally you'll need to set the variables for the notifications (notification_manager.py)
