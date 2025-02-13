Python Week 3

# User Stories

Is a simpler way for you to plan out you Python project, the specifics. They depict a small scenarios from a user's perspective and emphasize the user's goal and motivation.

User stories are simple, brief and informal and perfect for jotting down on index cards.

![image](https://github.com/MisterWest11/Python-Week-1-4/assets/152319557/501c0336-4b4c-464b-b0fb-671ae5b7a3bd)

they follow a format "As a (user/role), I want (goal) so that (reason/benefit)."

e.g.    "As a digest recipient, I want to receive an email every morning with current and useful information so that I know what's going on in the world and learn something new each day."

User stories focus on the user's goal and reasons rather than specific interface details.

# Use Cases

Use cases include a title, actor(user or system), and a scenario that describes how a goal is achieved.

![image](https://github.com/MisterWest11/Python-Week-1-4/assets/152319557/9514c0d4-288b-425a-9152-af38b2c93859)


User stories and Use cases maybe seem similar, but they capture different info. User stories focus on who, what and why of a task. 

Use cases focus on who, what and how of achieving that goal/task.

![image](https://github.com/MisterWest11/Python-Week-1-4/assets/152319557/d79a348a-5887-4d91-9afa-6a1335f61986)


# Projects Requirements

Functional requirements describe what the application should do or should not do. Written in as sentences starting with "the application must..."

These requirements act as a checklist to ensure the application meeets all necessary requirements.

![image](https://github.com/MisterWest11/Python-Week-1-4/assets/152319557/0d5122de-f04e-451a-ad54-d90152915304)


We also have non-functional requirements that describe how the application should accomplish its tasks. 

They focus on maintainability, reliability, and usability. e.g. The application should have a configurable GUI for the admin to interact with.


# Architecture



# GUI Design Planning

In this chapter, we will focus on creating a User Interface using Python's TKinter module.

A GUI is a program with a visual interface that uses elements like buttons, menus, and windows for users to interact with.

Think of it as a user-friendly way to control your program instead of typing commands.
Creating GUIs in Python:

Python offers several libraries for building GUIs, with Tkinter being a popular choice for beginners.

Tkinter comes built-in with Python, so no additional installation is required.
Basic GUI Components:

**Main Window:** The primary container that holds all other GUI elements.

**Widgets:** Interactive elements like buttons, labels, text boxes, and menus. Each widget has specific functionalities.

**Events:** User actions like clicking a button or entering text generate events that your program can respond to.

**Event Loop:** A never-ending loop that listens for events from the user and triggers the corresponding code.

Building a Simple GUI with Tkinter:

Import Tkinter: Begin by importing the tkinter module.

Create the Main Window: Use *Tk()* to create the main window object.

Add Widgets: Use methods like *button()*, *label()*, and *entry()* to add widgets to the window. Configure them with properties like text and size.

Define Event Handlers: Write Python functions to define what happens when the user interacts with a widget (e.g., clicking a button).

Start the Event Loop: Use *mainloop()* to start the event loop, which keeps the GUI running and responsive to user input.


![image](https://github.com/MisterWest11/Python-Week-1-4/assets/152319557/91fb6df6-f6e0-4f15-9ff9-65da07ba0573)


to add window on computer screen, *.mainloop()*

to change/edit size of window, *.geometry()*
