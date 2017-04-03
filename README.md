# VBNetCalendar
A Calendar Control that is large. 


The Lib. Is a DLL, simply follow the directions in the Codebank Article [here](http://www.vbforums.com/showthread.php?845535-Large-Calendar-Control&p=5155523#post5155523)



#Version 1.0

 - Initial Release
 
 - Basic Calendar Control, that is large view. 


# License 

Licensed under [MIT](https://github.com/jdc20181/VBNetCalendar/blob/master/LICENSE)

Please review license file before using, you need to include the license and my name in a abouts/credits page in your application. 

# Upcoming Changes

  - Adding Border to labels
  
  - Removing "AutoSize"
  
  - Resizing for better view
  
  - Changing `ForeColor` to `BackColor` making it much more visible. 
  
  - Changed Color's of components - minus background for your use. 
  
# Using the DLL

You will need to add it to your toolbox, Tools > Choose ToolBox Items > Browse > Select CalV.DLL (There will be a version number)

Add it to your form, and to make it work you need to do the following:

`        CalV1X.ReloadCal(Date.Today, Date.Today.Day)` where X is the number - when you add a control its numbered so if you add more than one it isn't the same name. Each control will need to be called seperately. And you need to do it on Form_Load, otherwise it will not work properly. 
