# CMDcal

## Summary

CMDcal is a small, command-line operated, appointment scheduling application built in a single Bash file. It makes use of the [Dialog](https://linux.die.net/man/1/dialog) library for the GUI, and saves all appointment data in a plain-text file called 'save.txt'. I built this for my CS224 class (currently in college) and am putting it here for street cred!

This program was built on linux. No gurantees it will run anywhere else.

### Features
- Schedule an appointment (date, time, reason) //add pic of calander
 	![alt text](https://github.com/lukeolson0/CMDcal/blob/main/img/calendar.jpg?raw=true)
- View/Edit/Delete appointments //add pic of view appointments screen
 	![alt text](https://github.com/lukeolson0/CMDcal/blob/main/img/stuff.jpg?raw=true)
- View today's appointments //add pic
 	![alt text](https://github.com/lukeolson0/CMDcal/blob/main/img/today.jpg?raw=true)
- Fun 'Logout' screen consisting of a random [cowsay](https://github.com/schacon/cowsay) character
  ![alt text](https://github.com/lukeolson0/CMDcal/blob/main/img/turkey.jpg?raw=true)


Feel free to download and change as much as you'd like! Code was commented per requirments of my professor.


### Quirks
- Does not allow spaces in 'Appointment Details' window. Spaces will confuse loading data from 'save.txt' into windows. If this happens to you, remove all data from save.txt or remove incorrect entry. 
- Takes you back to homescreen after you have completed an action. (ex. You have just deleted an appointment -> instead of staying in 'Current Appointments' window, you are taken back to 'Main Menu')
