# Student Productivity Helper

Student Productivity device created as a final project from UCSD.

### **Problem**

Our device is trying to help students stay productive with a distraction-free device that has all the features on their computer, but without any method to get distracted. It keeps the student focused with a Pomodoro timer, telling them what they should be working on based on their google calender, and reminding them of their habits throughout the day. Our target audience is younger students (grades 6 - 12) because they are more likely to be distracted and a simple device would make it easy for them to focus. Our solution solves the needs of the user by giving them a distraction-free method to focus and complete their work in a timely manner.

### **Design Process**

We choose to split our device into three seperate functions: pomodoro timer, calender support, and habit tracker. Each function has its own class. For the calender, we used a google API to make it easy to access events and display them. For the other two, we simply just created two completely custom classes. We used some techniques we learned throughout the quarter like using datetime objects and string parsing. We initally also had seperate main files to test. Then, once we verified that each function worked on its own, we combined it into 2 files. the first file housed all the classes. The second file was the main file and ran the code.

### **Features**

1. **Google Calender Support** - The device uses the google calender API to fetch your events for the next 24 hours. Then, when the event is live, it will buzz the motor and start the blue led to catch your attention that an event has changed. The OLED displays the start and end time of the event so you know how long you need to work for.
2. **Pomodoro Timer** - The timer will start a 30 minute focus timer, giving you messages at every 5 minutes how many minutes are left. After the timer is over, it will start a 15 minute break.
3. **Habit Tracker** - This will ask for your habits on first use. It will save any habits you want into a csv file for future uses. As the habits come throughout the day, it will display it on the oled for 2 minutes, and start the yellow LED. When the user is finished with the habit, they should press the right button and the LED will stop.

### Youtube link: https://youtu.be/3sDKym4WTyI
