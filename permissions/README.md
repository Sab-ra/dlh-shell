# Permissions Project

## Switch user to betty

File 0-iam_betty when excecute switches root user to betty user, if such exists.

## Identify current user

File 1-who_am_i when excecute shows who is the current user.

## List current user groups

File 2-groups when excecute lists all groups the curren user belongs to.

## Change hello file owner to user betty

File 3-new_owner changes file hello located in the same directory to use betty, when excecute

## Create an empty hello file

File 4-empty creates an empty file called hello, when excecute

## Grant execute hello permission

File 5-execute adds excecute permission to the owner of the file hello. Well, it actually does it without overwriting the entire permissions: chmod u+x hello. Oppa!

## Multiple permissions adjustment

E.g. ls -l: _rw_r_____ hello And we need to add excecute to user and group users, and add read to others:

```bash
# chmod ug+x, o+r hello
```

## Permissions for everyone

File 7-everybody allows to change user, group, and others permission with a single letter command for the type definition

## Fire from two hands

Change permissions like James Bond, taking them away from user and groups, and giving to others 8-James_Bond

## Make hello exactly -rwxr-x-wx

That will happen when 9-John_Dow excecute

## Mirror exact permissions from one file to another

Excecute 10-mirror_permissions

## Add execute permission to directory and dir within it

Execute 11-directories_permissions

## Make a directory and assign permissions in one go
Execute 12-directory_permissions

## Change group owner of a file

Execute 13-change_group

## Change owner and group user Recourcively
Excecute 14-change_owner_and_group
