# Admin Helper

This is a Bash script for an admin helper tool that provides various system administration tasks through a terminal-based menu interface.

## Overview

This script provides an interactive menu-based interface for performing common system administration tasks such as adding users, modifying users, listing users and groups, adding groups, modifying groups, disabling/enabling user accounts, and changing user passwords.

## Usage

To use the script, execute it in a terminal. It will present a menu with several options for system administration tasks. Follow the prompts to select an option and perform the desired task.

### Options Available:

- **Add User**: Add a new user to the system.
- **Modify User**: Modify an existing user's properties, such as username, home directory, or group membership.
- **List Users**: Display a list of all users currently configured on the system.
- **Add Group**: Create a new group on the system.
- **Modify Group**: Modify an existing group, such as changing its name or GID (Group ID).
- **List Groups**: Display a list of all groups currently configured on the system.
- **Disable User**: Disable (lock) a user account.
- **Enable User**: Enable (unlock) a previously disabled user account.
- **Change Password**: Change the password for a user account.
- **Exit**: Exit the script.

## Prerequisites

- This script requires `whiptail` to be installed, which is typically available on most Unix-like systems.
- Some tasks may require sudo privileges to execute. Ensure the script is executed with appropriate permissions.

## Installation
 
1. Clone this repository to your local machine:
   
 ```
git clone https://github.com/yasminelabady/Admin-Helper

```

 
2. Run the application locally :
 
```
vim admin-helper
chmod +x admin-helper
./admin-helper
```
 


