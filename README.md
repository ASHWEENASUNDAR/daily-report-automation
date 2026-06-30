**Daily Report Automation**

**1. Overview**
This project automates the daily report distribution process using Google Apps Script.
Instead of manually attaching the report and sending emails every day, the script automatically locates the report, generates the email, attaches the correct file, and sends it to the intended recipient.
If the report is unavailable, the script sends an error notification with instructions for manual action.

**2. Business Problem**
The daily report was previously prepared and emailed manually every day.

**(i) This repetitive process:**
Required manual effort
Risked attaching incorrect files
Could delay report delivery if forgotten

**(ii) Solution**
Developed a Google Apps Script automation that:
Automatically searches for the daily report
Generates a dynamic email subject
Attaches the report
Sends the report automatically
Detects missing reports
Sends an informative notification when the report cannot be found

**3. Features** 
(i) Automatic email generation 
(ii) Dynamic subject line
(iii) Automatic file attachment 
(iv) Error handling
(v) Missing file notification 

**4. Technologies**
(i) Google Apps Script
(ii) Gmail Service
(iii) Google Drive

**5. Business Benefits**
(i) Reduced repetitive manual work
(ii) Improved reporting consistency
(iii) Reduced human error
(iv) Increased reliability through exception handling

**6. Screenshots**

**Successful email notification:**

<img width="657" height="471" alt="image" src="https://github.com/user-attachments/assets/db20d383-f3af-4f47-bc2c-d3961d1cb36c" />

**Error notification email:**

<img width="690" height="193" alt="image" src="https://github.com/user-attachments/assets/57c2b424-4f48-4d3d-9257-673e4c9c2a51" />

**Script editor:**

<img width="1901" height="841" alt="image" src="https://github.com/user-attachments/assets/22f4de2d-b9a3-46be-92c3-8433e7bc20f6" />

**Flow diagram:**
Find file
        │
        ├── Found?
        │      │
        │      ├── Yes
        │      │      ↓
        │      │ Send report
        │      │
        │      └── No
        │             ↓
        │      Notify yourself
        │      Explain the reason
        │      Tell user what to do

6. **Future Enhancements**
(i) Multiple recipients
(ii) HTML email formatting
(iii) Automatic report generation
(iv) Logging and audit trail
(v) Scheduled execution.
