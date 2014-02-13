Pomodoro
=====


This is a simple pomodoro app based on the sample Timer app.

When the app starts, the pomodoro immediately begins in a live card. When 
tapping the live card, a menu displays allowing a few actions:

- Pause: pause the pomodoro.  Shouldn't really be used, from what I
      understand about pomodoros
- Resume: resume a paused pomodoro
- Mulligan: resets to the beginning of the last pomodoro (from both
      within the work time and within the rest time)
- Stop: remove the pomodoro live card from the timeline

A 25 minute work block followed by a 5 minute rest block counts as a single
pomodoro, and when the next pomodoro starts, the pomos completed count is
incremented.

The voice trigger is:

"ok glass, start a pomodoro"


### TODO's

There are a few bits that I'd like to add at some point:

- Replace "Pomos Completed: #" with a tomato image for each pomo completed,
  maybe followed by a dashed outline of a tomato
- Customize the menu icons
- Change the sounds that play when the timer hits 0
- Allow the user to change the length of work and break times
- Schedule longer breaks into a sequence of pomos

## Comments

Java is not really my thing, so any feedback is greatly appreciated.  This
can be in the form of github issues, pull requests, tweets [@freethejazz](http://www.twitter.com/freethejazz),
emails to my twitter handle @ that big G email provider, complaints written
on $20 dollar bills mailed to me in Chicago, etc.  
