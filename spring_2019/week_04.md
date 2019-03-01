## Last Week's Accomplishments

> This past week, I implemented a feature where once a user creates an account, an email verification link will be sent to
> the user's email address. Once the email address of a user's account is verified, it will be marked as so in the database
> for that user. I also cleaned up the code in the CreateAccount UIViewController and added a few documentation. Previously,
> the user was directed to the hub after registering their account despite not having logged into their new account.
> I refactored the code for registration so that when the user creates an account, the account gets added to the database,
> user is logged into their new account, email verification is sent to their email address, then user is directed to the hub.

## This Week's Plan

> Fix the issue where if the fields in the registration form is not entered correctly (not all fields are filled in, 
> passwords don't match, etc), closing the alert message redirects the user back to the Log In view.

## Anything Blocking?

> Debugging is tedious for Swift in XCode
