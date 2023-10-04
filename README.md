## TIME MANAGEMENT PROJECT by Agustina Fernández

# Video Demo: https://youtu.be/tAmJE-hKvHg 

# Deploy: https://agustinafernandez01.github.io/Time-management-Project/

# Description: 

This project was born out of necessity. I am a naturally disorganized person, so I constantly require tools to help me manage my time more effectively. When I discovered the Pomodoro method for studying and working, I achieved great results. Additionally, I've always been in the habit of maintaining to-do lists on paper or in notebooks. However, the idea of consolidating all these tools into one cohesive time management system made perfect sense to me. That's how the idea for the time management project came along.

First, I began by programming the timer that would follow the Pomodoro technique. To do this, I created a basic HTML file, which would serve as my index, and a main file that would allow me to execute the timer's actions. 
I decided that each stage of the method would have a different color to clearly indicate which part of the session we were in. I added buttons that allowed users to navigate between the method's stages independently, as well as a start/stop button that controlled all the timers. 

Additionally, at the top of the screen, there's a progress bar that fills up as the time decreases, and in the browser tab, I display the remaining time in the session along with a message that says "Back to Work" or "Take a break," depending on whether it's a work/study session or a break. Finally, if the user grants permission, on-screen notifications will appear above whatever they are doing, and there will even be an alarm sound to indicate that the stage has ended.

After completing the timer, I moved on to create the To-Do List. This feature allows users to add, delete, and edit tasks they want to remember. The form for adding a new task is controlled and doesn't allow the submission of a task without at least a title. Users can also add a date to keep track of deadlines and provide a description for more specificity. Each new task is rendered as a card and is ordered from oldest to newest.

I wanted this part to be genuinely useful, so I linked it to the browser's local storage. This way, when you refresh the page or exit and return, your tasks will still be there, waiting for you.

Finally, I wanted this webpage to be accessible beyond just viewing it from my computer's server. To achieve this, I deployed the project using GitHub Pages.


