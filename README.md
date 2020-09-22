# Apex-Assignments

Assignment 1:

    Create a field on Account called “is_gold”, checkbox, default off.
    When Amount field on Opportunity  is greater than $20k, mark is_gold to TRUE.
    
Assignment 2:

    Create a field on Contact called Profile, text, 255.
    When an Account is updated and the Website is filled in, update all the Profile field on all Contacts to:
    Profile = Website + ‘/’ + First Letter of First Name + Last Name
    
Assignment 3:

    Create a field on Account called “Only_Default_Contact”, checkbox, default off.
    When a new Account is created, create a new Contact that has the following data points:
    First Name = “Info”
    Last Name = “Default”
    Email = “info@websitedomain.tld”
    Only_Default_Contact = TRUE
    When the Account has more than 1 Contact, update Only_Default_Contact to FALSE.
    
Assignment 4:

    Write a trigger that counts the number of completed tasks on an account record and 
    display the count in a custom field on Account record
