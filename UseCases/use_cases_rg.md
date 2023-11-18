---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Use Case 1: Create Account

**Description**: This use case describes how a user creates a new account.

**Goal**: To successfully create a user account.

**Main Actor**: User

**Secondary Actor**: System

**Trigger**: User opens the Penny Pulse application.

**Relationships**: None

**Pre-condition**: User must not already have an account.

**Input**: User's required details (name, email, password).

**Post-condition**: A new user account is created.

**Output**: Confirmation email.

**Normal Path:**
+ User opens Penny Pulse application.
+ User selects 'Sign Up' or 'Create Account' option.
+ User enters required details and submits the form.
+ System registers the new user and sends a confirmation email.

**Alternatives Paths:**
+ If the username is already taken, the system prompts the user to choose a different username.
    
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Use Case 4: Manage Savings (Create Saving Envelope, Set up Automatic Savings)**

**Description**: This use case describes how a user can manage their savings, including creating a saving envelope and setting up automatic savings.

**Goal**: To successfully manage savings.

**Main Actor**: User

**Secondary Actor**: System

**Trigger**: User navigates to 'Savings' section.

**Relationships**: N/A

**Pre-condition**: User must be logged into their account.

**Input**: User's savings details (saving envelope name, amount, automatic saving rule).

**Post-condition**: User's savings data is updated.

**Output**: Confirmation of savings data changes.

**Normal Path:**
+ User logs into Penny Pulse application.
+ User navigates to 'Savings' section.
+ User creates a new saving envelope and sets up an automatic saving rule.
+ System starts the automatic saving process based on the user's settings.

**Alternatives Paths:**
+ If the user tries to set up an unfeasible rule (for example, save more money than they have), the system prompts the user to adjust their input.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
