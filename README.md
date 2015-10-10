# Using Intents
Hour2Application for Android in 24, 4th Edition

MainActivity shows example intents for
- Starting an Activity called SecondaryActivity
- Showing a location
- Showing a web page

SecondaryActivity can also be started via the implicit intent Action.SEND

In hour 2, you learn all about intents.  Android intents are used ti initiate actions 
like showing a web page or starting an activity.  

Hour 2 shows how to start an activity and to pass data to that activity.

ERRATA:

Listings 2.3 and 2.5 in the book have the same error.
```
Intent = getIntent();
```
should be 
```
Intent intent = getIntent();
```


