# zenity
🚸 Zenity dialog to create login screen, user list, user add, user delete
### What is Zenity?
zenity is a program that will display GTK+ dialogs, and return (either in the return code, or on standard output) the users input. This allows you to present information, and ask for information from the user, from all manner of shell scripts.

Read more at: https://www.commandlinux.com/man-page/man1/zenity.1.html

## Creating login screen
![alt text](https://github.com/AnonMrNone/zenity/blob/main/images/login_screen.png)

## List logable users
![alt text](https://github.com/AnonMrNone/zenity/blob/main/images/list_users.png)

To get the user details you can also use a small shell script. If you run this script, you can have a similar output.

Command:  sudo cat /etc/passwd | grep "/bash" | sed  's/:/ /g' > users

[Output](https://github.com/AnonMrNone/zenity/blob/main/zenity/test)

## Creating new users
![alt text](https://github.com/AnonMrNone/zenity/blob/main/images/newuser1.png)
![alt text](https://github.com/AnonMrNone/zenity/blob/main/images/newuser2.png)

[Code](https://github.com/AnonMrNone/zenity/blob/main/zenity/newuser)

## Delete users
![alt text](https://github.com/AnonMrNone/zenity/blob/main/images/deluser1.png)
![alt text](https://github.com/AnonMrNone/zenity/blob/main/images/deluser2.png)
![alt text](https://github.com/AnonMrNone/zenity/blob/main/images/deluser3.png)

[Code](https://github.com/AnonMrNone/zenity/blob/main/zenity/deluser)



