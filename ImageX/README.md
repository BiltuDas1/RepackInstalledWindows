# ImageX Commands
ImageX /append

Appends a volume image to an existing image (WIM) file

  image_path - The path of the volume image to be captured.
  
  image_file - The path of the existing WIM file.
  
  image_name - The unique name for the image being appended to the WIM file.
  
  description - The text that provides additional reference information.


Accepted FLAGS:

  /BOOT
  
  Marks a volume image as bootable. Available for Windows PE images only.


  /CHECK
  
  Enables WIM integrity checking. If not provided, existing checks are removed.


  /CONFIG configuration_file.ini
  
  Enables use of a configuration file for exclusion and compression options.


  configuration_file.ini - The path to the configuration file.

  /NORPFIX
  
  Disables reparse point path fixup.

  /SCROLL
  Scrolls output for redirection.

  /TEMP
  Specifies the path where temporary files are stored.

  /VERIFY
  Enables file resource verification.

Example:
  imagex /append d: d:\imaging\data.wim "Drive D"
