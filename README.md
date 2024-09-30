**Digital Clock Application**

**Overview:**

The Digital Clock Application is a web-based clock that dynamically updates and allows users to view the current time in different time zones. It uses Java (Spring Boot) for the backend and HTML, CSS, and JavaScript for the frontend. 

**Why This Project:**

I developed this project as an exercise in integrating Java backend logic with responsive frontend web technologies. The goal was to create a practical tool that dynamically displays the current time and allows users to switch between time zones easily. 


**Features**: 
- Real-Time Clock: Time is displayed and updated in real-time, synchronized with the start of each second.
  
- Timezone Selection: Users can select from various time zones.
  
- Dynamic UI: Background color of the clock changes every 60 seconds, creating a little visual effect.
  
- Backend: Built using Java(Spring Boot) with Thymeleaf for server-side rendering.

**How It Works**:
- The "script.js" handles updating the clock in real-time by using the system’s local time and adjusting it based on the selected time zone.
  
- The "timeWorker.js" starts by recording the current time when the application loads. It then calculates the difference between the current time and the time when the script started, effectively counting how much time has passed. This calculation ensures that the coc is updated at the precise start of each second, syncing with real-world time. 

**Usage**: 
- Install Dependencies since this is a Maven-based project, so ensure you have Maven installed.
- Once it is you can run the "DigitalClockApplication.java" file and it will boot up on your localhost:8080 URL in your web browser. 
- If you want to run from the terminal just make sure your directory path is correct and run the following command which should boot the same thing: ".\mvnw.cmd spring-boot:run" which I have commented in the DigitalClockApplication.java file. 

**Additional information**:
- Any questions feel free to email me at omar.i.talaat@gmail.com

