# Sys-Admin-Tools
Sys Admin Tools is a collection of powershell tools that make a sys admin's life just a little easier. 
<br>

### Populate_Teams_Data.ps1
Using a combination of O365 Powershell and Graph API. Intended to aid in the population of an O365 test environment by creating users and Teams. Recommended to run in a tenant with no users or Teams. Can be run multiple times. Not recommened for prod tenants. 
<br>

### HaveIBeenPwned_User_Audit.ps1
Uses a combination of Graph API and HaveIBeenPwned API. Requires a month or monthly subscription from HaveIBeenPwned for $3.50 a month. Audits O365 user accounts for breaches present in the HaveIBeenPwned database, and sends an email if there was a breach in the last 30 days.
<br>

### O365_License_Consumption_Audit.ps1
Leveraging both Graph API and O365 Powershell, this script will alert you when your license availability is below 2 for purchased licenses, and when users are not licensed with a defined set of required licenses. 
<br>

### Forward_Event.ps1
This script leverages Graph API to grab an event object from a source calendar and forward it to a target calendar based on a defined subject string.
<br>
