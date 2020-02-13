# Changelog
------
#### `v1.3.1`
- Fixed bug in STEM Schedule Setup, where Thursday Seminar used A-DAY schedule.

#### `v1.3.0`
- Edit now works when there is a space in the homework name
- Fixed bug where the assignment sorter only visually sorted the assignments
- Fixed bugs that puts items in displayHomework twice
- Improved how it gets the current period
- Improved how it gets the schedule
- Assignment sorter is now its own function instead of being part of the `clock` function
- Removed variable "`counter3`"
- No longer imports module "`datetime`" 5 times
- Can now input a day of the week as the "day" when creating new assignments
- No longer imports module "`os`" more than once
- Homework entry is now in one box
- Fixed bug where program would crash if "`hwFile.wlist`" did not exist
- Fixed bug where when "`homeworklist`" is empty, it still says that there is 1 assignment left
- Fixed bug where when trying to sort the homework, if the "`homeworklist`" was empty the program would crash

#### `v1.2.0`
- Added "[LATE]" tag to assignments due before the current time.
- Added date to the top of window
- Added sorter to prioritize late assignments
- Added "`Day`" to menubar to allow you to change what schedule its running
- Changed how the assignments are added
- "`Edit`" has been added under the homework menubar
- Made to where when entering assignments, if the time and AM/PM are left blank the default to 11:59 PMong

#### `v1.1.0`
- Added homework counter
- Fixed bug that prevents you from opening program after transparency set to an invalid input
- Grayed out "`Remove Assignment`" when there are no assignment

#### `v1.0.0 [INITIAL BUILD]`
- Added custom classes
- Created GUI
- Many others (too long to list)
