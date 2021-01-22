
# AdminLTE Dark Theme
 AdminLTE Dark theme for Pi-Hole WI v5.3.1
 
 The design idea was originally from @DoctorMidnight - https://discourse.pi-hole.net/t/dark-admin-theme/647 I have just re-created it to work on the latest AdminLTE version
 
I have also added more information to the tab menu - If you don't want this - then don't copy the header.php or the footer.php file
 
<p align="center">
    <a href="https://pi-hole.net/">
        <img src="https://pi-hole.github.io/graphics/Vortex/Vortex_with_Wordmark.svg" width="150" height="260" alt="Pi-hole">
    </a>
    <br>
    <strong>Network-wide ad blocking via your own Linux hardware</strong>
    <br>
    <br>
</p>

---
 
 ## Warning
 Please don't immediately put this onto your production environment - Its always best to test first on a development enviroment to make sure there are no issues.
 
 I take no responsibility for any damage or loss of data caused.

---

## Installation

Easy to install; Just copy all the files in the admin folder to the following directory /var/www/html/admin

---

## Removal

To Uninstall - just run this in ssh and choose the update option
 
```
curl -sSL https://install.pi-hole.net | bash
```
---

## Screenshots
Login Page:
    <a href="https://pi-hole.net/">
        <img src="https://github.com/deannreid/AdminLTE-Dark-Theme/blob/main/screenshots/login.PNG" alt="Pi-hole">
    </a>
Main Page:
    <a href="https://pi-hole.net/">
        <img src="https://raw.githubusercontent.com/deannreid/AdminLTE-Dark-Theme/main/screenshots/main%20page.PNG" alt="Pi-hole Dark Web interface">
    </a>

Settings Page:     <a href="https://pi-hole.net/">
        <img src="https://github.com/deannreid/AdminLTE-Dark-Theme/blob/main/screenshots/settings.PNG" alt="Pi-hole">
    </a>
    
---

## Credits
- @Developers of Pi-Hole - https://pi-hole.net/ 
- @Developers of AdminLTE - https://github.com/ColorlibHQ/AdminLTE
- @DoctorMidnight - https://discourse.pi-hole.net/t/dark-admin-theme/647 - for the original idea.
