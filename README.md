# Backups Ansible role

This is the Ansible role I use to periodically backup all the content of what's in my servers in S3.

## Required variables

 - `application_name` Application name to create backups for.
 - `backups_bucket_name` Name of the S3 bucket that will hold the backups.
