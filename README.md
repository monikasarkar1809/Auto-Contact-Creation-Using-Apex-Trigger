# Salesforce Auto Contact Creation

## Project Overview

This project demonstrates how to automatically create a Contact record whenever a new Account is inserted in Salesforce using Apex Trigger and Handler Class.

## Technologies Used

- Salesforce Apex
- Apex Trigger
- Developer Console

## Business Requirement

Whenever a new Account is created:
- A Contact should be automatically created.
- Contact First Name = Account Name
- Contact Last Name = "contact"
- Phone = *******
- Contact should be linked to the Account.

## Apex Handler Class

AccountHandler.cls
Handles Contact creation logic.

## Trigger

AccountHandlerTrigger.trigger

Executes after Account insertion and calls the handler class.

## Output

After creating an Account record, a related Contact record is automatically generated.

## Screenshots

### 1. Apex Handler Class
Shows the AccountHandler class responsible for creating Contact records automatically.
https://drive.google.com/file/d/1V2eBJMpri_lIJ9oN4FFAABIN9zg2BWGN/view?usp=sharing

### 2. Apex Trigger
Shows the Account trigger that calls the handler class after an Account is inserted.
https://drive.google.com/file/d/1dyLIX-Z3bD11VpmA7yoDJKIIYaAEagcF/view?usp=sharing

### 3. Output
Shows the automatically created Contact record linked to the newly created Account.
https://drive.google.com/file/d/1cR5JiBa3qgIuzrcrBUSZOvEmbY6idERo/view?usp=sharing
## Author

Monika Sarkar
Salesforce Administrator | Salesforce QA
