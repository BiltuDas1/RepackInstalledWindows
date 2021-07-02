[![SL Scan](https://github.com/BiltuDas1/RepackInstalledWindows/actions/workflows/shiftleft-analysis.yml/badge.svg)](https://github.com/BiltuDas1/RepackInstalledWindows/actions/workflows/shiftleft-analysis.yml)
[![Donate](https://img.shields.io/badge/Buy%20me%20a-Coffee-blue.svg)](https://www.buymeacoffee.com/stopback)
# What is install.wim file?
install.wim is a file which locate Sources folder into Windows Installation disk. It includes whole C: drive files in maximum compression. While installing windows, installation media copies all files from install.wim to C: drive.

# Advantages
1. When next time you will install windows, then current season will be restored.
2. You will get those softwares which you installed into current operating system.

# Disadvantages
1. A user account will be created automatically which you used earlier.
2. If you upload your modified os into any social media or blog post then, who will download, they can access your personal information (such as chrome history, password)

# How to Repack OS into install.wim file?
For Repacking Windows into install.wim file you need to follow below instructions.  
or need to watch the video : https://www.youtube.com/watch?v=TvJkUdYp15w


(If you want to Repack Current Operating System then goto [Step 12](#current-os))

1. Download a fresh copy of windows  
--Windows 7  : https://www.stopback.tk/2020/01/windows-7-full-version-untouched-iso_9.html  
--Windows 10 : https://www.microsoft.com/en-in/software-download/windows10  
--Rufus      : https://rufus.ie/en/

2. Clean setup WinToolkit. (which you found into 'Components' folder)  
--Extract DISM 10.exe  
--Install DISM  
(You can use WHDownloaded.exe for download windows & Office Updates)

3. Extract Windows iso file in a specific directory using WinToolkit

4. Modify this fresh OS using winToolkit (If you don't want to modify os then you can skip this step)  
--Just change setting, change those setting which you can't change manually when Windows is installed.

5. After modifying this os, open extracted path.

6. Remove any wintoolkit file in this folder.

7. Connect your PC with a flash drive and format it (File system : NTFS)

8. After formatting flash drive, copy all files and folders into your flash drives root directory.

9. Now restart your PC with your pen drive.

10. Now install that windows.

==================== After Windows Installed ====================

11. Setup your windows in your choice.(like installing Google Chrome)

<p id='current-os'>12. when your all task complete, reconnect your flash drive from where you installed your current os.</p>

13. copy 'imagex' folder to your pendrive's root directory

14. Now boot your computer along with your flash drive.

15. When Windows installation setup opened. Press 'Shift+F10' into your keyboard, it will launch command prompt.

***Caution: It is the main part of your setup, in this position your all drive letter will be chaged, you need to detect your drives using 'cd' and 'dir' commands. If you do anything wrong, you may need to reinstall operating system.***

16. Type 'C:' and then 'dir' (Without quotes)

17. If you find 'Program Files','Windows' folder in the list then Mark the drive as [System Drive]

18. If you couldn't find Program Files','Windows' folder then type 'D:' and then 'dir' (Without quotes) and continue the step 17.

19. Now find the flash drive's Drive letter using above steps and mark the drive as [Flash Drive]

20. If you has any other Partition then you need to find Drive letter of it, because We will save install.wim file in that partition (Also you can save it into your flash drive). Mark the drive as [Output Drive]

21. Now we've got [System Drive], [Flash Drive], [Output Drive]. YOu need to goto into [Flash drive] by typing Drive letter and use 'CD Imagex' Command.

22. Type 'imagex /capture [System Drive] [Output Drive]\install.wim "Windows"' (Without quotes) and Wait few minutes (Sometime it takes few hours, depend on Processor speed and [System Drive] files).

23. If imagex completed creating install.wim file then reboot your PC and eject Flash Drive.

24. Now your install.wim file is ready, Try to open the file into WinToolkit and If it opened properly without any error then your file is ready to use. Copy and replace the file into your installation media 'Sources' folder.

25. Now Install the OS using this Installation media. Hurray! You successfully REpacked your system. Now you can use it any PC.
