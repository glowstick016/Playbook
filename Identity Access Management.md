# Identity Access Management 

## Implementign a new user:
  1. Image a computer for the user from a Golden Image
  2. Implement the required programs that aren't on the golden image 
  3. Setup any other processes that the user might need (like backup processes, etc.)
  4. List the system under the user's name in a secure database
  5. Implmeent the right credentials for the user (preferably with a group policy)
  6. Meet-up with the new-hire and walk them through any setup processes that they would need to do themselves. 
    - Signing onto WiFi with their credentials
    - Singing them into database services (google drive, O365, etc.)
    - etc.
  7. Give a quick explination to the user on what their rights on the computer are 


## Removing a user:
  1. Remove the user credentials from systems and/or user's account depending on the situation
  2. Go through the files and split them into the following categories:
    - Our files 
    - Their files 
    - Trash files
  3. Send out the files as needed 
  4. Clean up the old user's hardware and put into storage
    - Reimage the laptop to wipe it
    - Collect the monitor, keyboard, etc that they used
  5. Remove their system and name from our machine database


## Organize Users:
  1. Implement group based policies
    - PAM for Linux 
    - AD for Windows 
  2. Assign groups based on needed permissions
    - General worker
    - Elevated workers (IT)
    - System Accounts
    - System Admin Accounts
    - Admin Accounts 
  3. Assign secure systems to keep the Admin account safe
    - Secure long password 
    - 2FA+ 
    - Password changes often especially when the team changes 
    - Limited amount of people know the password 
    - Log whenever the account is used
