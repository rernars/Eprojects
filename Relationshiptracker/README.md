Retrieves and Displays Elapsed Time Since a Specific Date on a 128x64 OLED Screen Using NTP Server Data

![image](https://user-images.githubusercontent.com/59098807/222956208-4e0515f4-0e65-4734-beb0-da7968fd124c.png)
![image](https://user-images.githubusercontent.com/59098807/222956284-fe23ae8d-04fe-44ba-add6-36b0acd03b29.png)
![image](https://user-images.githubusercontent.com/59098807/222956187-65e9e918-8ca6-4a14-9bde-6eca6f271b73.png)
![image](https://user-images.githubusercontent.com/59098807/222956323-e74bb5f1-e4c2-4391-80d1-0c19b15b9645.png)

This program is designed for an ESP8266-based system that uses an OLED display and an NTP time source. It initializes the OLED display with specified pins and settings, then attempts to connect to one of the predefined WiFi networks, displaying the local IP address upon successful connection. Using an NTP client, it retrieves the current time from an NTP server and adjusts for the local time zone. The program calculates the number of days and months that have passed since a specific date and stores this information. It then displays the calculated days and months on a 128x64 OLED screen, showing the number of days and months that have passed since the start date. Additionally, the program sends a WhatsApp message via the CallMeBot API when a new month begins, sending the message to two predefined phone numbers. In the main loop, the time is regularly updated, and the OLED display is refreshed accordingly. If a new month is detected, a notification is sent. This program effectively combines WiFi connectivity, NTP time retrieval, OLED display updates, and HTTP requests to create an informative and user-friendly display and notification system.

Use Cases:

- Relationship Tracker: Track the duration of a relationship by displaying the number of days and months since the relationship began, and receive monthly reminders to celebrate milestones.
- Event Countdown Timer: Track the number of days and months until a significant event, such as a birthday or anniversary.
- Project Timeline Tracker: Monitor the progress of long-term projects by displaying the elapsed time since the project start date.
- Personal Milestone Reminder: Keep track of personal milestones, such as fitness goals or study schedules, by displaying the time passed since the start date.
