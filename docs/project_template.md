# Project Proposal: Student Daily Planner & Streak Tracker

## 1. Title
Student Daily Planner & Streak Tracker

## 2. Brief Description
The Student Daily Planner & Streak Tracker is a console-based application that helps students organize daily tasks, track completion progress, and stay motivated through a streak system. Users can add tasks, mark them as complete, view their task history, track study time, and set reminders. All data, including task history, completion streaks, study logs, and reminders is permanently stored in JSON files, allowing the application to display meaningful insights such as completion rates, productivity trends, and longest active streaks over time.

## 3. Problem Statement
Students often struggle to keep track of assignments, study goals, and deadlines. Paper planners are easily lost or forgotten, and digital apps can be distracting or inaccessible. Without a clear record of completed work, it is difficult to monitor productivity patterns or maintain consistent study habits. There is a need for a simple, offline tool that permanently stores task history, visualizes progress through completion streaks, and generates personal productivity insights — all without requiring internet access or complex setup.

## 4. Outline of Features

| Feature | Description | Programming Concepts | Persistent Data Usage |
|---|---|---|---|
| Add Daily Task | Create new tasks with priority levels | Functions, input validation | Creates new task entries in JSON |
| View Today's Tasks | Display checklist for the current day | Loops, lists | Reads and displays stored task records |
| Mark Task Complete | Toggle task status; update daily completion status | Conditionals | Updates task status; recalculates streak |
| Edit or Delete Task | Modify or remove existing tasks | Functions, list operations | Updates or removes entries from stored data |
| Streak Tracking | Automatically calculate and update current and longest streaks | Date operations, conditionals | Reads completion history; updates profile values |
| History & Statistics | View past completion records, rates, and trends | Iteration, descriptive statistics | Analyzes all historical task data |
| Study Timer & Log | Time study sessions and record daily duration | Time operations | Stores daily study minutes in JSON |
| Reminders | Add and view upcoming tasks and deadlines | Date comparison | Stores and retrieves reminder entries |
| Save & Load Data | Automatically persist data on exit; restore on launch | File handling, JSON | Enables persistent data across sessions |

## 5. Persistent Data Structure

All data is stored in /data/student_data.json

### Profile Data
- current_streak - Number of consecutive days with completed tasks
- longest_streak - Highest streak value achieved
- last_completed_date - Last date tasks were marked complete
- total_tasks_completed - Running total of all completed tasks

### Daily Tasks Data
- date - Date of the task list
- tasks - List of task entries (task_id, title, is_done, priority)
- study_minutes - Total study time logged for that day

### Reminders Data
- title - Reminder description
- due_date - Deadline date
- is_complete - Completion status

## 6. Wireframe
See separate file: *wireframe.md*

## 7. Task Schedule & Team Assignments
See separate file: *team_schedule.md*

Version: 1.0 - First Draft
Last Updated: 2026-11-23
