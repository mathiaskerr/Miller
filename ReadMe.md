# Task

## Problem task
* A user has gone outwith the Service Desk and got in touch with the team directly to let us know  that they are getting an issue when trying to browse to our Call Off app using their work phone
* There is a clear urgency to this issue, since they have not gone through Service Desk as per process, and it could mean that the entire application is down for all users
* What do you do to try and troubleshoot the issue?
* Do you interact with the user? If yes, then how and what do you say to them? 
* Do you let anyone else know about the issue?
* When you manage to close out the issue, what do you do regarding the user who logged the issue in the first place?
***

1. Assess Situation with available information. (has this happened before etc?)

2. Let my manager know what I know and that I will try to help out. Do this via appropriate contact method at the time.

3. Interact with the user whilst showing empathy for the situation. Gather further information about the issue such as if the problem is happening on multiple devices, networks or locations.

4. Talk user through some simple troubleshooting ie, turning device off and on again, re-installing app, clear cache and if it a browser version exists, try that one.
5. During this time I can also be doing any checks on my end to see if it is a system wide problem. If I am in office with other people or able to easily contact any colleagues during this process I could have them run some of these tests to find a quicker solution.

6. During this whole process or directly after I will be documenting the whole process as further investigation may be required or to help prevent this issue in the future.

7. If none of the above has been successful I would escalate appropriately by contacting the service desk, my manager and possibly the team responsible for the Call Off app. The service desk will be brought up to speed with what actions have already been taken. Their advice here might be very valuable as it might be something they have encountered before.

8. During this process I would be keeping the user informed and advise them to the best of my ability.

9. Once the issue is resolved I will contact the user and stay on the line to confirm the app is working. After I confirm that I will advise the user to follow the proper procedure by calling the service desk as this will lead to a quicker solution for them.

10. At the end of this I will reflect on what I have learned and share this with the team and service desk to see what can be done to improve this process.
***

# Wireframes

App task:

- The business has asked you to come up with an app to log health and safety violations found on site and in the office
- Each violation should be categorised in a way that makes it easy to report on - such as according to type and risk
- Photographic evidence is a must as well as being able to log something without having any signal

Please use a wireframe creator or app design creator such as Figma or Moqups to demonstrate your design and to explain your choices


Every screen other than the Log In screen will have a header with the name, nav bar and logo (I left that out for the wireframes as I think this looks better at this stage).

<div align="center">
<img src =first.png?raw=true >
</div>

1. Log In:
- App name and logo.
- Form for inputting user details
- Link to recover details if forgotten
- I would include pop ups if incorrect details have been put in


2. Home Screen:
- A header with the app name, logo and nav bar.
- A brief description of the app's purpose.
- Button to log a new violation.
- Button to view all logged violations.
- Button to generate reports.
- Footer with copyright information, contact details and a privacy policy link.

3. Nav Bar:
The navigation should be placed at the top of the screen and should include the following elements:
- Home
- Log New Violation
- View All Violations:
- Generate Reports
- Account Setting: to allow the user all appropriate changes.
- Accessability: to allow the user to make the app more readable or accessible 
- Contact: all appropriate contact information

<div align="center">
<img src =second.png?raw=true >
</div>

4. Log New Violation Screen:
- Large camera styled button that will take user straight to camera. Alternatively a button to use a picture from the device. 
- A form to log a new violation, including the following fields:
  - Date and time of violation (automatically generated initially but manual if needed. Use cameras date stamp?)
  - Type of violation (dropdown menu)
  - Risk level (dropdown menu)
  - Description / Comment (text field)
- A button to submit the violation. If the user tries to submit without any of the mandatory fields they will be prompted top fill these fields or add the picture.

4. View All Violations Screen:
- A list of all logged violations, including the following information:
  - Type of violation
  - Risk level
  - Description of violation
  - Thumbnail of uploaded photo
  - Date and time of violation
- Each violation wll be pressable and take the user to the Violation Details screen 
- Sort button to sort by various parameters (initially displayed chronologically)

5. Generate Report Screen:
- A form to generate a report, including the following fields:
  - Type of violation (dropdown menu)
  - Risk level (dropdown menu)
  - Date range (date picker)
- A button to generate the report.
- A preview of the generated report. (potential for interesting data visualisation here)


<div align="center">
<img src =third.png?raw=true >
</div>

7. Unable To Post
- This is a pop up that will show if the log cannot be posted due to not being connected to the network. The app will save the log and post it either when it next can or potentially the app can check for logs that have not been posted each time it starts and post then.  


8. Violation Details Screen:
- All the details of the selected violation, including the following information:
  - Type of violation
  - Risk level
  - Description/ Comment
  - Full-size uploaded photo
  - Date and time of violation
- A button to go back to the view violations screen.









