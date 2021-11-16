# Keylogger
Keylogger implementation using Python which logs keystrokes and sends regular reports to a specified mail

pip3 install keyboard

command to execute

python3 keylogger.py

This module allows you to take full control of your keyboard, hook global events, register hotkeys, simulate key presses and much more.

To recieve log reports by mail, set up a mail id and set allow less secure apps on and disable 2fa.
enter the mail is and password in the stipulated field. You can also change the SEND_REPORT_EVERY parameter. it is set to 60sec
The keylogger
Listens to keystrokes in the background.
Whenever a key is pressed and released, we add it to a global string variable.
Every N minutes, report the content of this string variable either to a local file or to the specified mail. you can set it by commenting the report_method u dont want.
as of now set for email only.
