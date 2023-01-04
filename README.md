Initiation to swift and first project

A to-do list mobile app that features:

Requirements

    The application should open with a splash screen
    There should be three categories at the top of the screen:
        Pending
        Completed
        Overdue
    If the to-do list is empty, show an empty state message: “No items to display. Please press “Add” to add new items.”
    Show a fixed navigation bar at the bottom of the screen with an “Add” button, which allows the user to create a new task
    Clicking the “Add” button will show a screen with the following elements:
        Title (text input field)
        Description (text input field)
        Deadline (iOS or Android default date and time selector)
        Confirm button
        Cancel button
    Each new task should have a deadline later than the current time. Adding a task will save it to the file storage in the text file.
    Users can perform different actions by selecting single or multiple items:
        “Pending” category
            One item selected: the user can press “Delete,” “Edit,” or “Complete”
            Multiple items selected: the user can press “Delete” or “Complete”
        “Overdue” category
            One item selected: the user can press “Delete,” “Edit” or “Complete”
            Multiple items selected: the user can press “Delete” or “Complete”
        “Completed” category
            One item selected: the user can press “Delete” or “Edit”
            Multiple items selected: the user can press “Delete” or “Edit”
    When the user presses on the “Edit” button, a screen should pop up with:
        Title (text input field with pre-filled data)
        Description (text input field with pre-filled data)
        Deadline (iOS or Android default date and time selector with pre-filled data)
        Confirm button
        Cancel button
        Complete button
    10 minutes before the deadline of a task, users will receive a push notification to remind them of the task
    
    Made by Aaron & Quentin

