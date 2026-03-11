# Terminal Portfolio Update [MIR_OS]
- TYPE: Adding clicking accessibility to assist those who don't know how to use a terminal
- TARGET: Terminal Portfolio
- STATUS: DEPLOYED

# THE OBJECTIVE
* After a trial an initial beta with some users. It was found that a terminal is difficult for those not in the tech field to use. The goal now is to make the website accessible to those that are not very well verse with tech commands.

# THE_ROADBLOCK
* A roadblock came in the definition of the file system. Resolving a path became a big issue. Say we start in the root folder, then went to the project folder, and then we want to try and get a file from the root folder. It would throw an error as that command does not exist in the current working directory.

* Pathing is going to stay a big issue for this project unless the whole structure is completely refractored.

# THE_EXECUTION
* [PATH_RESOLUTION] Created path_resolver to handle pathing from other directories. Say if you were in /projects and want to access a file in /roots. path_resolver would be able to resolve the absolute path to correctly route the user.
* [CLICKABLE_UIs] Turned all the directories/files/executables into clickable UIs

# NEXT_STEPS
Auto suggestion is still a topic to deal with, however another big issue is the pathing + the clutter on the screen. Right now the screen is littered with ls as whenever a new one is created the old one remains. Will have to look into that in the future.