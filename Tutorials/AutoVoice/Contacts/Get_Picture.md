# Get picture of your contacts by using AutoVoice
This tutorial will explain, how to retrieve the picture of a specific contact.
We can use a command like this: **show me a picture of John.**

## Requirements:
- An android phone
- Tasker
- AutoVoice
- Autocontacts

### Step 1: AutoVoice & AutoContacts
Be sure that AutoVoice and AutoContacts are correctly installed. Also be sure, that all your contacts are listed in the database.
Before you start, refresh your contacts:
- **Open AutoContacts**
- Click on **Force Refresh Contacts**

### Step 2: Creating the profile
First, let's make a new profile, called **AV Contacts - Picture**
- Create a new trigger/context: **Event > Plugin > AutoVoice > Recognized**
- Choose the **The Hard Way**
- Command: **picture of foto van (?<name>.+)**
- **Enable Regex**

### Step 3: Creating the task
Now we make our task, called **AV Contacts - Picture**

