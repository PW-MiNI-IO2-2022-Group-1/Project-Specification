# Project Specification

## Online API docs (updated 09.03.2022)
[https://battnik90.stoplight.io/docs/io](https://battnik90.stoplight.io/docs/io)

## Changes
### 09.03.2022
**Specification changes (PDF file):**
* Updated activity diagram - removed searching for available doctor (obsolete), added checking whether selected offer is still available.
* Removed chapter about algorithm to assign patient to doctor (obsolete).
* Updated supported OS section - backend should be working on either Windows or Linux.

**API changes (both online and files in this repository):**
* Updated "Login as admin" function and "Admin" object (added fields for admin's name and surname in order to have stucture unified with patient and doctor).
* Created functions "Create new vaccination slot" and "Delete vaccination slot" (to manage time slots by doctor)
* Updated "Get vaccination slots (schedule)" function to show both upcoming visits (slots reserved by patients) and planned time slots (created but not reserved).
* Created function "Show list of available vaccines" (to allow patient to choose vaccine during registration for selected time slot) 
* Updated "Reserve vaccination slot" - added field for chosen vaccine.
* Updated "Vaccine" object - removed serial number for simplicity. 
