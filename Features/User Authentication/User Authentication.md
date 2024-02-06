![LoginPage](https://github.com/JakePatolilic/vsulib-ms/assets/114040840/e2a4742f-facc-4106-bbdc-a2a6b1a6d24f)
# User Authentication
This is used by the library staff assigned to this activity in order to enter the data of the registered user so they can use the system.
## Input
- The user shall provide the system with the necessary information to use the software.

## Process
- The library staff user shall enter the registered username.
-	The library staff user shall enter the password for that username.
-	The library staff user has the choice to log-in using g-mail.

## Output
-	The library staff user shall be able to use the inventory or maintenance system.

## Data Dictionary
| Element ID               | Element Text                    | Element Type | Data Type | Required? | Rules                   |
|--------------------------|---------------------------------|--------------|-----------|-----------|-------------------------|
| SystemNameTextDispaly    | Library Electronic Equipment Inventory Maintenance System | Text         | String    |           |                         |
| AdminHeader              | Admin                           | Header       | String    |           |                         |
| AdminUsernameTextbox     | Enter your username             | Textbox      | String    | Yes       |                         |
| AdminPasswordTextbox     | Password                        | Password     | String    | Yes       | Masked                  |
| LoginButton              | Log in                          | Button       | Button    |           |                         |
| LoginInvalidUsername     | Invalid username and password.  | Text         | String    |           | Hidden                  |
| LoginForgotPassword      | Forgot your password?           | Link         | Button    |           | Hidden                  |
| UserHeader               | User                            | Header       | String    |           |                         |
| UserUsernameTextbox      | Enter your username             | Textbox      | String    |           |                         |
| UserPasswordTextbox      | Password                        | Password     | String    | Yes       | Masked                  |
| GmailButton              | Gmail icon                      | Link         | Button    |           |                         |
| NoAccountText            | Don’t have any account?        | Text         | String    |           |                         |
| UserCreateAccount        | Create Account                  | Link         | Button    |           |                         |
| CreateAccountHeader      | CreateAccount                   | Header       | String    |           |                         |
| CreateAccountNameTextbox | Enter your name                 | Textbox      | String    | Yes       | Name must not be empty  |
| CreateAccountPasswordTextbox | Password                   | Password     | String    | Yes       | Masked                  |
| CreateAccountButton      | Create Account                  | Button       | Button    |           |                         |
| ViewPasswordButton       | Eye icon                        | Button       | Button    |           |                         |

