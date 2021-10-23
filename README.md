# MobileArchitectAndProgramming

**Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?**
This app is intended to track events for users and display those apps. Users may add, edit, and delete apps and can select to have the app provide notifications when the date of each event is coming up. It can be used to help its users keep track of their daily schedule.

**What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?**
In order to support the user needs, the app needed a screen to allow users to log in or create an account in the app, a screen to display events in a grid format, and a screen to change notification settings. Typical users of this app would want to be able to quickly access the app and view the events to make any changes needed. I minimized the amount of screens needed in the app to access the events. 

**How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?**
I used an SQLite database within the app to hold usernames and passwords. I also trialed an SQLite database to hold events. 

**How did you test to ensure your code was functional? Why is this process important and what did it reveal?**
I used an Android device emulator to test that the code was functional. I made sure that each button and editable text box worked the way it was intended and that each screen of the app could be accessed. I found that one screen within the app was not functioning the way it should be. I am addressing this issue and working to fix it. 

**Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?**
I had to overcome a challenge when coding the app. I was not sure how to go about making the screen of the app that displays events and allows users to add, edit, or delete them functional. I trialed an SQLite database and I also trialed creating an Event class and an EventService class which can be called to display, add, edit, and delete events. 

**In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?**
I think I successfully designed the UI of the app well. I kept the screens simple and followed accessibility requirements set by Android. 
