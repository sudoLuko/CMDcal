# CMDcal

## Summary

CMDCal is a small, command-line operated, appointment scheduling application built in a single Bash file. It makes use of the [Dialog](https://linux.die.net/man/1/dialog) library for the GUI, and saves all appointment data in a plain-text file called 'save.txt'. I built this for my CS224 class (currently in college) and am putting it here for street cred!

### Features
- Schedule an appointment (date, time, reason) //add pic of calander
- View/Edit/Delete appointments //add pic of view appointments screen
- View today's appointments //add pic
- Fun 'Logout' screen consisting of a random [cowsay](https://github.com/schacon/cowsay) character!


Feel free to download and change as much as you'd like! Code is commented per requirments of my professor.


### Quirks
- Does not allow spaces in 'Appointment Details' window. Spaces will confuse loading data from 'save.txt' into windows. If this happens to you, remove all data from save.txt or remove incorrect entry. 
- Takes you back to homescreen after you have completed an action. (ex. You have just deleted an appointment -> instead of staying in 'Current Appointments' window, you are taken back to 'Main Menu')
