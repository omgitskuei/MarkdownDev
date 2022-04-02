# MacroEditor V.2, Project Info
---
An applet with polished GUI written in Java that automates mouse actions with Java Robot.
Author: Omgitskuei
Last Updated: 2022/04/01
Status: In development

### Problem
---
Guild Wars 2 gameplay often drops materials collectively called "T5 trophies". These rewards clog
up inventory space. They're made more spatially efficient as well as more valuable if
promoted from T5 to T6 trophies. The primary reason this isn't done more often by
players is because the promotion process is a mindless and tedious chore of repetitively clicking
through menus.

### Goal
---
Design a program with GUI (graphical user interface) that allows users to intuitively
create new automation routines related to the mouse. 
This includes automatically:
1) moving the mouse, 
2) clicking the mouse, 
3) waiting a user specified number of seconds before the next action, if any.

### Scope
---
The program should have a number of GUI components that let the user customize their automation routine:
- The program should have a JTextArea that is Not editable for displaying the current 
queued actions in the routine.
- The program should have a Clear all actions and/or Remove last action JButton.
- The program should have an Execute routine JButton.
- The program should have separate buttons for adding new Mouse Moves, new Mouse Clicks, and new Waits.

The program should be able to interact with the file system.
- The program must be configurable from a config file without having to change the code-base.
- Save the routine to a text file (.txt).
- Open a text file and run the routine from the text file, if it is parsed correctly.

### Future design spaces
---
The program can be expanded to:
- Support adding keyboard actions to the routine.

### Change logs
---
2022/04/02 - Added more menu bar icons to /resources
2022/03/29 - Refactored MacroEditor V1 into V2, separated monolith single Java file into smaller helper, util classes