##Shortcuts

To use this version of LoopFollow plese download the following iOS Shortcuts:
https://www.icloud.com/shortcuts/a354366d5d104ba09659443aa3c0b208
https://www.icloud.com/shortcuts/23411d569e884dcd90a11669aaa33300
https://www.icloud.com/shortcuts/1d30f7f61d0d4d53b5afc5e824da2834
https://www.icloud.com/shortcuts/b364d56f958648b4a43801e740e6e189

## Loop Follow 

Using so many different apps as a parent or caregiver of a T1D can be very cumbersome. Add in the extra details from Looping
and it can be a challenge flipping back and forth between apps. Each app has different strengths and weaknesses.
- Spike is great for alarms. 
- Spike and Sugarmate are great for the calendar complication on Apple Watch. 
- Nightscout X or Nightscout in Safari are needed for intricate details from NS.
- IFTTT and Pushover are  needed for Not Looping alerts.

And there are some functions I've always wished for and not found anywhere such a one-time temporary alert
for those nights when Loop is stuck on high and you open loop with a correction. This lets you set a higher
low alert for the BG you want to wake up to and close Loop.

Build Instruction Video: https://youtu.be/sdF5v2eGGyA

Special thanks to Spike-App, NSApple, and Nightguard for helping me figure out how to do a lot of the code for this.

If you want to contribute, the biggest needs today are to make the code cleaner and more efficient, get some major details like Bolus/Basal graph and mg/DL vs mmol added, and create the basis for a watch app.

### General feature list
- scrollable/scalable graph display with BG, basal, bolus, and carb details plus Loop status, Loop Prediction, and the General NS Care portal info.
- option to override DND and system volume for all alerts.
- snoozes per alert, presnooze, edit existing snooze, and snooze all alert settings.
- the standard Low/High, Urgent Low/High, and missed reading alerts. High will have a persistence option that’s still to do. Eg high for x minutes.
- fast drop/rise alerts with BG limits. Eg Trigger fast drop only when under a BG where it’s an issue.
- sage/cage reminder alerts for x hours before change.
- Not Looping with Bg limits alert. So you can trigger the alert only if under or over a BG range.
- Missed Bolus alert.
- calendar entries to use watch complication with BG, arrow, delta, cob, iob and minutes ago (if old reading).
- background silent audio to keep iOS from killing the app. It has a selectable refresh rate that should help reduce battery usage. This is why it can’t go in the App Store for just a simple download.

### Contributing, Building, and Branches
- New code will be pushed to the Dev branch as soon as it has been added. It might be very rough around the edges. Once it has been thoroughly tested, it will be merged to Master. If you are even remotely adventurous, please build Dev to help test the new features as they are added.
- If you want to contribute, please PR on Dev unless it is an important bug fix to address in Master

### Open Source DIY
- This is a DIY open source project that may or may not function as you expect. You take full responsibility for building and running this app and do so at your own risk.
