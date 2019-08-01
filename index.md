
# Dream and Consciousness

![Dream](/photos/DreamConsciousness.jpg)

i had deep dreams today. When i woke up i realized i was having a heavy dream. I could observe that the dream that i had today had some components of earlier dream. The dream had some influence of present events. The visuals and environment in the dream gets constructed as i progress in it. The characters in the dream could change from one scene to other. The consiousness fails to observe this change and continues as though everything is continious and nothingbis oit of place. When i woke up from the dream i could observe this change of characters and dicontinuity because of logic. In the dream there is a theme and logic is ignored. It amy be something like boiling of emottions that overlooks logic. Is there a part of brain that needs to be kept engaged this way so that body can relax and recover. The restoring of balance and cleansing could be carried out during this time.

# Microsoft Robocopy
![Robocopy](/photos/Robocopy.jpg)
Robocopy is tool that allows users to copy data on windows machines. The tool copies file data, attributes, timestamps, acl's which include  both DACL(discretionary access control list) and SACL system access control list. Robocopy does incremental copy of data as well. if you are copying data from cifs network shares then you need to authenticate and access the share atleast once before starting a copy operation. There is no option to pass username and password to the robocopy command.

There is a version of robocopy that supports mutithreaded copy. This version as per documentations in only available on Windows Server 2008 R2 and Windows 7 or later. This multithreaded version of windows is not compatible with older version of windows. check the help for robocopy command if you see a /MT option listed in the help then it supports the multithreaded copy. The multithreaded robocopy is faster at copying data if you have lot of small files in a directory. The performance single threaded versus multithreaded robocopy will be more or less comparable if we have fewer large files in a directory. The multithreaded robocopycopy may be a shade slower than regular single threaded robocopy for fewer large files in directory.

Robocopy's backup mode will allow (/B backup mode) will allow it to override file and folder permission settings (ACLs).Robocopy fails to copy files  which are locked by applications even in the backup mode. its best advised to run robocopy on a snapshot of data or when files are not being modified.
