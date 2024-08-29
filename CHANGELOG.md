# Change Log
All notable changes to this project will be documented in this file.

## Sprint 1 - 30-09-2022
### Added
- Login Page, Logout page
- Verify otp, resend otp, forgot password, change password, reset password
- Navbar, User Profile details
- Create, View, Edit, Search, Delete Company
- Create, View, Edit, Search, Delete Merchant
- Create, View, Edit, Search, Delete Agent
- Create, Search, Disable User
- User association with Company/Merchant/Agent
- Transaction list, search and details

## 03-10-2022
### Added
- Help tag - user guide download based on their role
- Agent list dropdown to the primary contact of merchant
- PLSGPROD-47 - UI with API integration for Advance transaction search

### Updated
- Removed required field for agent dropdown to the primary contact of merchant
- Implemented refresh button to get the transactions list
- Descriptions to functions and removed unused state variables

## 06-10-2022
### Updated
- CSS reusable styles and responsiveness to the pages
- Url changes for user association
- One api endpoint for get and search functionality

## 07-10-2022
### Updated
- Loading indicators for asynchronous calls
- Dropdown values for transaction type and transaction status
- URL pattern for profile photo

## 12-10-2022
### Added
- Terminate Merchant Profile

### Updated
- Alt values to the Images

## 13-10-2022
### Added
- UI for user audit report with export to excel file functionality

## 14-10-2022
### Added
- PLSGPROD-52 - UI with API integration to get profile details as per login user 

## 19-10-2022
### Added
- Called API to get transactions when advance search form is cleared

## 26-10-2022
### Added
- PLSGPROD-135 - resend email confirmation for users

### Updated
- Principal Owner details for Merchant and Agent info

## 28-10-2022
### Added
- PLSGPROD-137 - edit user details

## 02-11-2022
### Added
- PLSGPROD-108 - Automatic logout functionality

## 03-11-2022
### Updated
- User status for company/merchant/agent/user
- Email confirmation link to company/merchant/agent

## 04-11-2022
### Added
- PLSGPROD-102 - User audit report functionality with integrations
- PLSGPROD-104 - Re-subscribe to emails from the portal functionality
- PLSGPROD-113 - Transactions under company/merchant/agent

## 09-11-2022
### Updated
- otp time counter value from 2 to 5 mins

## 10-11-2022
### Added
- Browser compatibility - Google chrome, Microsoft edge, Firefox

## 14-11-2022
### Added
-  PLSGPROD-136 - User and group permission functionality with API Integrations

## 15-11-2022
### Added
-  PLSGPROD-157 - Resend Email Confirmation for company/merchant/agent

## 17-11-2022
### Added
-  PLSGPROD-150 - User status - Pending, Not Associated, Active, Deleted, Locked
-  Company/Merchant/Agent status - Pending, Active, Deleted

## 18-11-2022
### Added
-  PLSGPROD-151 - Conditional navbar menu items for the logged in user based on the permissions API response

## 21-11-2022
### Updated
-  PLSGPROD-136 - Implemented individual user permissions for CRUD operations based on the permissions API response

## 30-11-2022
### Added
-  PLSGPROD-186 - Implemented API for showing users mapped to the group.

## 30-11-2022
### Updated
-  PLSGPROD-171 - User type dropdown based on entity(company/merchant/attendant)

## 01-12-2022
### Added
-  PLSGPROD-172 - Implemented View button to see all sections data in Readable format.

## 07-12-2022
### Added
-  PLSGPROD-189 - Implemented entities in the same navigation while creating new user.

## 08-12-2022
### Added
-  PLSGPROD-184 - Create, View, Edit, Delete attendant UI and API integration

### Updated
-  PLSGPROD-188 - Creating a new user along with assigning group or permissions in one API call.
-  PLSGPROD-180 - Implemented getting the default access permission rights.

## 15-12-2022
### Added
-  PLSGPROD-191 - Implemented Export CSV data for companies/merchants/attendants 

## 20-12-2022
### Added
-  PLSGPROD-206 - Super Admin will be able to create other super admins

## 26-12-2022
### Added
-  PLSGPROD-201 - Designed UI frames and integrated API for POS License for Super Admin

## 28-12-2022
### Added
-  PLSGPROD-202 - Designed UI frames and integrated API for POS License for Company Admin
-  PLSGPROD-203 - Integrated API for POS License for Merchant Admin

## 05-01-2023
### Added
-  PLSGPROD-198 - Gateways configuration by Super Admin
-  PLSGPROD-199 - Gateways configuration by Company Admin
-  PLSGPROD-200 - Gateways configuration by Merchant Admin
## 20-01-2023
### Added
-  PLSGPROD-204 - Designed UI frames for Online POS and integrated API for the same for Merchant and Attendant login
