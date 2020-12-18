# AutoJoinClass
Automatically joins classes/meetings on a user inputted schedule.


Parallel Arrays Explained

use class_days for the days classes/meetings are on
use class_times for the times of each class/meeting (24 hr clock)
use class_links for the links of each class/meeting
These 3 are parallel arrays, so for each class/meeting add 1 value to each array
For example, if there were meetings on Tuesday and Thursday the arrays would look as follows:
class_days = ["Tuesday", "Thursday"]
class_times = [08:00:00, 14:30:00] (Tuesday class/meeting at 8am, Thursday class/meeting as 2:30pm)
class_links = ["tuesdayclass.com", "thursdayclass.com"]
