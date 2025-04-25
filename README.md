# Using-the-Autopsy-retrieve-the-deleted-files

```
Developed by:
Name: Alluguri Srikrishna Teja
Register.no: 212222040006
```
# AIM:
To use Autopsy in Kali Linux to retrieve and analyze deleted files from a disk image.

# DESIGN STEPS:
## Step 1:
Open Autopsy and create a new case with appropriate case details.

## Step 2:
Add a disk image as a data source and let Autopsy analyze the content.

## Step 3:
Navigate to the "Deleted Files" section in Autopsy and examine or recover the deleted files.

# PROGRAM: 
The Steps to recover the deleted files by using the Autopsy.

# Step 1: Launch Autopsy.
```
autopsy
```
it opens your browser at: http://localhost:9999

# Step 2: 

Click "Create New Case".

Enter a Case Name (e.g., FileRecoveryTest).

Enter any optional details (e.g., Examiner).

Choose a Case Directory (e.g., /home/kali/Documents/AutopsyCases).

Click "Finish".

# Step 3: 

Select "Add Data Source".

Choose "Disk Image or VM File".

Browse and select your image file: e.g., /home/kali/Downloads/disk.dd

Choose the Time Zone (e.g., UTC or your local time).

Click Next, then Finish.

Autopsy will now ingest and analyze the image file.

# Step 4: Navigate to Deleted Files

After analysis completes:

Go to the left pane → File Types or Data Artifacts.

Navigate to:

```
Views → Deleted Files
```

Or: 

```
File Types → Unallocated Space / Deleted
```

Autopsy will list deleted files that were found in unallocated space.


# Step 5: Recover the Deleted Files

Click on a deleted file you want to recover.

View the file preview on the right (if supported, e.g., images or text).

```
Right-click on the file → Extract File.
```
Choose a location to save the recovered file (e.g., /home/kali/Recovered/).

Repeat for other files.

# OUTPUT: 

Recovered Deleted File List and Details

<img width="400" alt="image" src="https://github.com/user-attachments/assets/b9974993-4993-4557-a08b-2d201c212351" />

<img width="400" alt="image" src="https://github.com/user-attachments/assets/565b9667-1a04-4609-9351-f0de1bbf8853" />

<img width="400" alt="image" src="https://github.com/user-attachments/assets/effa67c0-4a5b-46ea-95b1-764a562b6401" />

# MD5 Current And Orginal was Not Passed


<img width="400" alt="image" src="https://github.com/user-attachments/assets/f1627130-bee2-4096-a52f-6ad12e83c296" />

# MD5 Current And Orginal was Passed


<img width="400" alt="image" src="https://github.com/user-attachments/assets/47c5a928-2781-4e5c-a7c1-7db5b93dfdef" />


# RESULT:

Deleted files were successfully retrieved and analyzed using Autopsy.










