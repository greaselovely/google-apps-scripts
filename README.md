# google-apps-scripts

## 
ISS (International Space Station) emails are sent if you are subscribed to them.

Create a Label called SpotTheStation, create a filter under settings to auto label emails, and then add this script to run against that label.  Add a proper / real secondary email address for a pal to receive calendar entries also, create a trigger to run once a day, and you're good to go.

## phishing

Used at work, it looks for the label in the email header and then labels the message with that label.  If the label doesn't exist, it will create it for you.
