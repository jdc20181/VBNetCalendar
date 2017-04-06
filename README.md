# VBNetCalendar
A Calendar Control that is large. 


The Lib. Is a DLL, simply follow the directions in the Codebank Article [here](http://www.vbforums.com/showthread.php?845535-Large-Calendar-Control&p=5155523#post5155523)



# Version 1.0

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

# Over-Ride Properties - V1 only 

When Version 1.1 is released, much of this is not going to be needed. 

For Version 1, you may want to override the sizing properties. 

You can do something like this:

`Calv1.Labelname.Autosize = False`

`Calv1.Labelname.Height = X`

`Calv1.Labelname.Width = Y`

When V 1.1 is released, the control will be much more styled, and less plain. Until then you are required to override if you don't like the defaults. 

# Downloading Options 

2-options, DLL install or Download Project

DLL install instructions are given above. 

For Project - 

NO DLL's or .EXE is given in the project, it is the plain jane regular project, if you wish to reuse it such as in a DLL with modificatiosn (Take note of license Display is still required!) - You will need to add a second project, Copy/Paste the control in Calendar project into the new project, Delete Form1, then go to application properties and change it to a class project, this will make it a DLL. 
Then just follow the steps provided above. 

*YOU WILL NEED TO REBUILD THE PROJECT TO MAKE IT WORK ON INITIAL DOWNLOAD*


# CSharp Conversion

I am working on this day to day and it will be released soon!

See the [CSharpCalendar](https://github.com/jdc20181/CSharpCalendar) respo!
