# Maximizing Participation in Activities   


### Objective   
The goal of this project is to apply the greedy algorithm to maximize the number of non-overlapping activities you can participate in during a given time frame.

### Problem
You are provided with a list of activities, each defined by a start time and an end time. The challenge is to select the maximum number of activities that can be attended without any overlaps in their schedules.

### Implementation Steps
- List Activities with Start and End Times:

Create a list of activities with their respective start and end times. For example:   
Activity A: 9:00 - 10:00   
Activity B: 9:30 - 10:30   
Activity C: 10:00 - 11:00   
Activity D: 10:30 - 11:30   
Activity E: 11:00 - 12:00   
   
- Sort Activities by End Time:
  
   
- Select Activities Using the Greedy Approach:


   
### Expected Output   

``` java
Input List of Activities:
Activity A: 9:00 - 10:00
Activity B: 9:30 - 10:30
Activity C: 10:00 - 11:00
Activity D: 10:30 - 11:30
Activity E: 11:00 - 12:00
Sorted List of Activities by End Time:


Sorted Activities:
- Activity A: 9:00 - 10:00
- Activity B: 9:30 - 10:30
- Activity C: 10:00 - 11:00
- Activity D: 10:30 - 11:30
- Activity E: 11:00 - 12:00


Selected Activities:
- Activity A: 9:00 - 10:00
- Activity C: 10:00 - 11:00
- Activity E: 11:00 - 12:00
```
