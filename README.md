# Django/Python Front End Live Project



Personal Code Summary for the second team live project I was a part of at Prosper IT Consulting



## Introduction

During my time at The Tech Academy, I was assigned to a two-week sprint working on software to be used as a way to "manage a collection of construction jobs. Admins will be able to create and distribute a weekly schedule assigning users to certain jobs. Users will be able to keep track of which job they are assigned to for the week. There will also be the ability for admins to post company news and announcements, and chat functionality for the users to socialize."

My contributions to this second sprint of the project included adding back-end functionality.  I fixed a bug that allowed the admin to delete them selves, I enabled the app to capture from the database which users were suspended, I created a partial view that allows users to be separated by "active" or "suspended", I enabled a Job object to be deleted along with all of it's attached objects from different tables of the database, and I added a list of all users to the admin Dashboard view.

Listed below are the stories I worked on, a brief description of their expectations, and the code I created to complete them.

## User Stories

- [Remove Ability To Suspend and Change Role for Self](#remove-ability-to-suspend-and-change-role-for-self)
- [Capture Suspended](#capture-suspended)
- [Separate Users by Type](#separate-users-by-type)
- [Deleting a Job with Attached Objects](#deleting-a-job-with-attached-objects)
- [User List in Dashboard Admin View](#user-list-in-dashboard-admin-view)

## 



### Remove Ability To Suspend and Change Role for Self