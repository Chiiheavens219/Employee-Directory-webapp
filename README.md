# Employee-Directory-webapp
A brief hands-on how to create a web app using a Virtual Machine (EC2 instance) in AWS.

# Conception - Creating Users and Groups

## Task

### Created an IAM User

I created an IAM user from the root account 

Created a group and labelled it Admin and then assigned Administrator access to the IAM User.

## Created 3 Users and 3 groups

I created user-1, user-2 and user-3

I further created 3 groups with permissions assigned to them which are:

S3 Support with ReadOnlyAccess

EC2 Support with ReadOnlyAccess

EC2 Admin with ViewStopStartAccess

user-1 and user-2 were assigned managed policies

user-3 was assigned an inline policy


## Testrunning the 3 users created

I tried signing in with the different users to ensure that they can access the permissions attached to them.

It was confirmed that they can only access the permissions granted to them.


