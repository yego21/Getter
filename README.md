# Getter
Python script that automatically zips and e-mail files from windows PC.

This script is ready to use, just enter your email parameters in line 132 of the code where you want to send the files as email, then you can repack using pyinstaller if you want to use it as executable.

Recommended pyinstaller command ----> pyinstaller.exe --noconsole --onefile getter.py

This is optimized and tested using gmail SMTP server only, you can otherwise use any other email SMTP, but this script is set to follow gmail's rules such as attachment file size and suspicious file permissions.  Lines 25-26 displays all the file types that will be scanned and zipped for email. Gmail may also flag your account and suspend it temporarily if you overuse this script. Use appropriately.
