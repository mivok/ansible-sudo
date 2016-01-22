# Sudo role

This role supports sudo files being built from variables.
Please see the default/main.yml for examples.


## Variables

 * sudo_userdefaults:
   This is the set of sudo settings each user will get.
 * sudo_users - A list of users who have sudo access. Use '%foo' to specify
   that users in a given group have sudo access.
   This also supports overriding the sudo_userdefaults on a per user basis.
 * sudo_hostalias:
   This lets you create host aliasses.
 * sudo_useralias:
   This lets you create user aliasses.
 * sudo_cmndalias:
   This lets you create command aliasses.
 * sudo_runasalias:
   This lets you create runas aliasses.
