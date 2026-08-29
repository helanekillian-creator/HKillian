# Microsoft 365 Lab
## Objective
### This lab was created as a self-directed Microsoft 365 environment to gain practical, hands-on experience with the administration and support tasks commonly performed by an entry-level IT support technician. The objective was to create and configure a Microsoft 365 tenant, build a functional lab environment, create and manage user accounts and groups, perform basic account and password administration, and become familiar with the Microsoft 365 admin center and related services.
### Step 1: Creating a New User in Microsoft 365. In this step, I provisioned a new user account in the Microsoft 365 admin centre

![Adding a User](images/Screenshot%202026-08-18%20062548.png)

### Step 2: Assigning a Microsoft 365 License
In this step, I assigned the appropriate product licenses to the newly created user account to grant them access to cloud services.

![Assigning a product license](images/Screenshot%202026-08-18%20062607.png)

### Step 3: Configuring User Roles and Optional Settings
In this step, I configured the user's role settings, keeping them as a standard user with no administrative access to follow the principle of least privilege.

![Configuring User Roles](images/Screenshot%202026-08-18%20062627.png)

### Step 4: Creating a Microsoft 365 Group and Assigning Owners
In this step, I initiated the creation of a new security or distribution group and assigned an owner to manage the group's members and administrative settings.

![Assigning Group Owners](images/Screenshot%202026-08-18%20063031.png)

### Step 5: Adding Members to the Group
In this step of the configuration wizard, I added regular users as group members to grant them collaborative access to the group's shared resources and emails.

![Adding Group Members](images/Screenshot%202026-08-18%20063105.png)

### Step 6: Verifying Group Creation
In this step, I verified that the setup wizard completed successfully and the "Marketing" group was officially created in the tenant directory.

![Marketing Group Created Confirmation](images/Screenshot%202026-08-18%20063608.png)

### Step 7: Resetting a User Password
In this step, I initiated a password reset for a user account, configuring it to automatically create a password and require the user to change it upon their first sign-in.

![Resetting User Password](images/Screenshot%202026-08-18%20063732.png)

### Step 8: Verifying Password Reset Confirmation
In this step, I verified that the system successfully processed the request and confirmed the password reset was complete.

![Password Reset Confirmation](images/Screenshot%202026-08-18%20063752.png)

### Step 9: Revoking Active User Sessions in Entra ID
In this step, I navigated to the Entra ID admin center and initiated a global session revocation for a user account to forcefully sign them out of all active devices and applications for security compliance.

![Revoking User Sessions](images/Screenshot%202026-08-18%20093703.png)

### Step 10: Verifying Session Revocation Confirmation
In this step, I verified the action was successful by confirming the administrative alert notification showing that sign-in sessions were successfully revoked.

![Session Revocation Confirmation](images/Screenshot%202026-08-18%20093713.png)

### Step 11: Accessing Per-User Multifactor Authentication (MFA) Settings
In this step, I accessed the per-user MFA settings console within Entra ID to identify user accounts requiring multi-factor authentication enrollment.

![Accessing Per-User MFA Dashboard](images/Screenshot%202026-08-18%20095317.png)

### Step 12: Managing Per-User MFA Security Settings
In this step, I selected a user account within the per-user MFA settings and configured an administrative requirement forcing them to re-provide their authentication contact methods upon their next login.

![Managing MFA Settings](images/Screenshot%202026-08-18%20095419.png)

### Step 13: Final Verification of Created User Directory
To conclude the lab, I verified the Microsoft 365 Admin Center's Active Users directory to ensure all newly provisioned accounts were successfully created, properly licensed, and active within the tenant environment.

![Active Users Directory Evidence](images/Screenshot%202026-08-18%20062905.png)
