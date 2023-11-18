--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Use Case 2: Log In

*Description:* This use case describes how a user logs into the system.

*Goal:* To access the user's personal account and its functionalities.

*Main Actor:* User

*Secondary Actor:* System

*Trigger:* User chooses 'Log In' option.

*Relationships:* None

*Pre-condition:* User must already have an existing account.

*Input:* User's username and password.

*Post-condition:* User gains access to their account.

*Output:* User's dashboard or main interface.

*Normal Path:*
+ User opens the Penny Pulse application.
+ User selects 'Log In' option.
+ User enters their username and password.
+ System verifies the entered credentials.
+ User successfully logs into the application.

*Alternatives Paths:*
+ If the entered username or password is incorrect, the system prompts the user to enter the correct credentials.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Use Case 3: Manage Account Data

*Description:* This use case describes how a user manages their account data, including changing password, updating personal details, and deleting the account.

*Goal:* To manage and update account data as per the user's requirements.

*Main Actor:* User

*Secondary Actor:* System

*Trigger:* User navigates to 'Account Settings' or 'Profile' section.

*Relationships:* Includes 'Change Password', 'Update Personal Details', 'Delete Account'.

*Pre-condition:* User must be logged into their account.

*Input:* Changes made to the user's account data.

*Post-condition:* User's account data is updated or account is deleted as per user's actions.

*Output:* Updated account information or confirmation of account deletion.

*Normal Path:*
+ User logs into the Penny Pulse application.
+ User navigates to 'Account Settings' or 'Profile' section.
+ User selects the required action (change password, update personal details, or delete account).
+ System updates or deletes the user's account information accordingly.

*Alternatives Paths:*
+ If the user chooses to delete the account, a confirmation prompt appears to ensure that the user wants to proceed with the deletion.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Use Case 5: Manage Subscriptions and Bills

*Description:* This use case describes how a user manages their subscriptions and bills, including adding, updating, and deleting subscriptions and bills.

*Goal:* To manage subscriptions and bills as per the user's requirements.

*Main Actor:* User

*Secondary Actor:* System

*Trigger:* User navigates to 'Subscriptions and Bills' section.

*Relationships:* None

*Pre-condition:* User must be logged into their account.

*Input:* User's subscriptions and bills details.

*Post-condition:* The user's subscriptions and bills data is updated.

*Output:* Updated subscriptions and bills data.

*Normal Path:*
+ User logs into the Penny Pulse application.
+ User navigates to 'Subscriptions and Bills' section.
+ User adds, updates, or deletes subscriptions and bills.
+ System updates the user's subscriptions and bills data accordingly.

*Alternatives Paths:*
+ If the user attempts to add a subscription or bill that already exists, the system prompts the user to update the existing record instead of creating a new one.
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Use Case 7: Manage Financial Challenges 

*Description:* This use case describes how a user can participate in a savings challenge or split an expense with another user.

*Goal:* To engage in financial challenges and split expenses among users.

*Main Actor:* User

*Secondary Actor:* System

*Trigger:* User navigates to 'Challenges' section.

*Relationships:* None

*Pre-condition:* User must be logged into their account.

*Input:* User's decision to participate in a challenge or split an expense.

*Post-condition:* The user's challenges data is updated and the other user is notified about the split expense.

*Output:* Updated challenges data and notification to the other user.

*Normal Path:*
+ User logs into the Penny Pulse application.
+ User navigates to 'Challenges' section.
+ User participates in a savings challenge or splits an expense with another user.
+ System updates the user's challenges data and sends a notification to the other user for their share of the expense.

*Alternatives Paths:*
+ If the user attempts to split an expense with a user who does not have an account, the system prompts the user to invite that person to create an account.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
