# Wireframe — Student Daily Planner & Streak Tracker

## Program Flow Overview

START → Main Menu → Choose Option → Perform Action → Return to Main Menu → Exit → END


## Screen 1 — Main Menu

============================================
     STUDENT DAILY PLANNER & STREAK TRACKER
============================================
      Current Streak: 5 Days
      Longest Streak: 12 Days

      Today: 2026-11-26

      1. View Today's Checklist
      2. Add New Task
      3. Mark Task as Done
      4. Edit Task
      5. Delete Task
      6. View History & Statistics
      7. Start Study Timer
      8. View Reminders
      9. Add Reminder
      0. Exit
============================================
Enter your choice: _

Flow: User enters a number and presses Enter.
Performs the selected action, then returns here.


## Screen 2 — View Today's Tasks

--------------------------------------------
     TASKS — 2026-11-26
--------------------------------------------
 ID  | Task                         | Done  | Priority
-----|------------------------------|-------|---------
 1   | SocSci - Read Chapter 3      | Yes   | High
 2   | Bio - Complete Lab Report    | No    | High
 3   | Chem - Answer Problem Set     | No    | Normal
--------------------------------------------
 Progress: 1/3 tasks completed (33%)

 Enter task number to toggle status, or 0 to go back: _

Flow: Enter task number -> Mark as done/not done -> Auto-save -> Refresh list
Enter 0 -> Return to Main Menu


## Screen 3 — Add New Task

--------------------------------------------
     ADD NEW TASK
--------------------------------------------
 Task Title: _______________________
 Priority: (H)igh / (N)ormal / (L)ow: _

 [S]ave     [C]ancel
 Enter choice: _

Flow: Enter task details -> S to save -> Task added -> Return to Main Menu
C to cancel -> Discard -> Return to Main Menu


## Screen 4 — History & Statistics

--------------------------------------------
     HISTORY & STATISTICS
--------------------------------------------
 Current Streak: 5 Days
 Longest Streak: 12 Days

 This Week:
 Total Tasks: 18
 Completed: 15
 Completion Rate: 83%

 Study Time:
 Today: 45 minutes
 This Week: 5 hours 30 minutes
 Daily Average: 47 minutes

 Press Enter to go back...

Flow: Reads all stored data and calculates summary values
Press Enter to return to Main Menu


## Screen 5 — Reminders

--------------------------------------------
     UPCOMING REMINDERS
--------------------------------------------
 #   | Item                         | Due Date
-----|------------------------------|-----------
 1   | SocSci Chapter 3 Quiz        | Nov 27
 2   | Bio Lab Report Due           | Nov 28
 3   | Chem Long Quiz               | Nov 30
--------------------------------------------

 [1] Mark Complete     [2] Add New     [0] Back
 Enter choice: _

Flow: Select action -> Update saved data -> Refresh list
Enter 0 to return to Main Menu
