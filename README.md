# What is it?
It is a tool which will help you to Pack your Current operating System (Windows) into install.wim file.

# What is install.wim file?
install.wim is a file which locate Sources folder into Windows Installation disk. It includes whole C: drive files in maximum compression. While installing windows, installation media copies all files from install.wim to C: drive.

# Advantages
1. When next time you will install windows, then current season will be restored.
2. You will get those softwares which you installed into current operating system.

# Disadvantages
1. A user account will be created automatically which you used earlier.
2. If you upload your modified os into any social meadia or blog post then, who will download, they can access your personal information (such as chrome history, password)

# How to Repack OS into install.wim file?
For Repacking Windows into install.wim file you need to follow below instructions.
or need to watch the video : https://www.youtube.com/watch?v=TvJkUdYp15w


(If you want to Repack Current Operating System then goto Step 13)

1. Download a fresh copy of windows
--Windows 7  : https://www.stopback.tk/2020/01/windows-7-full-version-untouched-iso_9.html
--Windows 10 : https://www.microsoft.com/en-in/software-download/windows10

2. Clean setup WinToolkit. (which you found into 'Components')
--Extract DISM 10.exe
--Install DISM
(You can use WHDownloaded.exe for download windows & Office Updates)

3. Extract Windows iso file in a specific directory using WinToolkit

4. Modify this fresh OS using winToolkit (If you don't want to modify os then you can skip this step)
--Just change setting, change those setting which you can't change manually into Online Windows.

5. After modifying this os, open extracted path.

6. Remove any wintoolkit file in this folder.

7. Connect your PC with a flash drive and format it (File system : NTFS)

8. After formatting flash drive, copy all files and folders into your flash drives root directory.

9. Now restart your PC with your pen drive.

10. Now install that windows.

==================== After Windows Installed ====================

11. When windows ask to create first user.
--Type username 'Admin'
--Type Computer name 'YourPC'
--Do not type any password.
--Skip Product key.
--Set time & timezone to original GMT time

12. Do not active windows using any loader, keygen.

13. Setup your windows in your choice.(like pagefile)
--Install applications (like Google Chrome)

14. when your all task complete, reconnect your flash drive from where you installed your current os.

15. copy 'imagex' folder to your pendrive's root directory

16. Now boot your computer along with your flash drive.

17. When Windows installation setup opened. Press 'Shift+F10' into your keyboard, it will launch command prompt.

Caution: It is the main part of your setup, in this position your all drive letter will be chaged, you need to detect your drives using 'cd' and 'dir' commands. If you do anything wrong, you may need to reinstall operating system.
