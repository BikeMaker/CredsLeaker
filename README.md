# CredsLeaker
This script will display a powershell credentials box that will ask the user for his credentials.

![Credentials Box](https://raw.githubusercontent.com/Dviros/CredsLeaker/master/Screens/Box.png)

The box cannot be closed (only by killing the process) will keeps checking the credentials against the DC.
When validated, it will close and leak it to a web server outside.

![Credentials Leak](https://raw.githubusercontent.com/Dviros/CredsLeaker/master/Screens/Leak.png)

# How To:
1. Start a web server.
2. Type your server IP and port in the ps1 script.
3. Execute the batch file.

# TODO:
- Box title should be changed.
- Different windows versions has different credential boxes. Needs to be pulled from WINAPI.

# Donations will be highly appreciated
![Monero Donation](https://i.imgur.com/AMK3OCh.png)
