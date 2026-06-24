Medi-Fill – Smart Medicine Expiry and Refill Management system

So Medi-Fill is basically a clever medicine tracking app it s meant to make it easier for people to keep control of what they take. It helps users remember expiry dates, get refill nudges, and steer clear of risky drug interactions. I mean yeah, the whole point is less stress, more safety.

The thing uses AI based Optical Character Recognition (OCR) so it can pull medicine details straight from the label, so you don’t have to type everything by hand. On top of that it connects with trusted medical databases, which then enables drug interaction warnings and general safety alerts, kind of like an extra layer of care.

Through automated notifications and some smart monitoring, Medi-Fill supports better medication adherence, and it also reduces the chance of using something that s already expired. Simple right?

Main Things You Get (Key Features)

Medicine label scan with AI

You point your phone camera at the medicine label and scan. Medi-Fill then relies on Google Vision API OCR to pull the medicine information automatically, and not require the usual manual entry.

Watching expiry dates

It keeps an eye on expiry date info and sends alerts before medicines expire so people don’t accidentally consume something unsafe. It s more like prevention than reaction.

Refill reminders that actually help

When supplies are getting low, Medi-Fill sends reminders so the medicine can be refilled in time. No last minute scrambling, hopefully.
Detecting drug interactions

This part is backed by the OpenFDA API, it helps spot potentially harmful interactions between medicines. So, you get a warning before things become a problem.

Secure sign-in

User accounts and sign-in flow are handled via Firebase Authentication, so access is controlled in a more secure way.

Notifications in real time

For timely alerts about expiry dates and refills, it uses Firebase Cloud Messaging.

How to install

- Clone the repository  
- Navigate into the project folder  
- Install dependencies  
- Start the server using the command  
"npx expo start"
