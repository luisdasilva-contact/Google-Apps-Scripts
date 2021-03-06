### Time In Meetings
Time_in_Meetings.gs is used in Google Sheets to display information on the Google Calendar events of users in your organization. <sup>1</sup>

### NOTE: 
Syntax for Calendar API has recently been updated. Code included in this program may not function correctly until the next update.

##### Instructions: 


1. In a Google Sheets file, for each of the Google Calendars you want information on, enter one email per cell. 
2. Go to Tools --> Script Editor. A blank, default function will appear if no code has been written yet; if there is existing code, in the Script Editor, 
go to File --> New -->  Script File. Clear any blank, default functions, copy the code from the Time_in_Meetings.gs file, then paste it into your new 
script file. 
3. Press CTRL+S/CMD+S to save the .gs file. Name the project whatever you'd like. 
4. Go to Resources --> Advanced Google Services. Next to Calendar API and Google Sheets API, ensure that the latest versions are selected respectively, and turn them on. 
5. Back in the Advanced Google Services window, click OK. Save any other changes you have made to the script. You may now close your script window. 
6. Refresh the Google Sheet window. After loading, you should now have a new toolbar item titled "Time in Meetings".
7. Select the emails you'd like to find information on, click Time in Meetings, then click Find Time for Selected. A window will pop up asking for authorization. Accept it.<sup>2</sup>
8. If meeting data is available, it will appear in a new tab titled Time_in_Meetings_data. 

<sup>1</sup> _This script has built-in filters. Meetings that feature no attendees are not included, and attendees who have declined the event are not included as having been at the meeting. Please continue with this in mind._

<sup>2</sup> _The scopes the program will ask for include "see, edit, create, and delete spreadsheets". The program will not create or delete spreadsheets, but rather, edit only the sheet with this script attached._
