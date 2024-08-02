# Managing-Data

For this Assignment you are going to create Some local accounts, Local groups, and Folders and then Manage those objects. It is recommended that you watch the lecture in the Module 7 section to complete this assignment. 

In your Windows VM:

Start Powershell and run the cmdlet [Start-transcript]
Create 10 New Local users with Descriptions and no passwords
Create 10 folders, 5 on your desktop and 5 in your documents folder
Create a plain text file called contact.txt on your desktop (using powershell)
Add 5 names and 5 email address to the file
Change all email address from @domain.com to @company.com 
Set the passwords for all 10 users [-AsSecureString]
Run the cmdlet [Stop-transcript]
Go to file location where the .txt is stored
Rename the file to "FirstName-LastName-Assignment7b.txt"
Upload the transcription file to this Assignment section before the Deadline
I have linked to Microsoft documentation on how Start-Transcript and Stop-Transcript work below:

Start-Transcript
Link: https://docs.microsoft.com/en-us/powershell/module/microsoft.powershell.host/start-transcript?view=powershell-7 (Links to an external site.)

Stop-Transcript
Link: https://docs.microsoft.com/en-us/powershell/module/microsoft.powershell.host/stop-transcript?view=powershell-7 (Links to an external site.)

Note: Unless you specify where the file is stored, [Start-Transcript] stores the transcripts in the $Home\My Documents directory as \PowerShell_transcript.<time-stamp>.txt files.

