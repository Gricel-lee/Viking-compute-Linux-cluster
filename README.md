# Viking-compute-Linux-cluster
Notes on how to use Viking, the compute Linux cluster use by the University of York.

# Installation
For Windows, install PuTTy and TightVNC Viewer.

# Run files
## Where to store them
All files MUST be run from "scratch folder"

![image](https://user-images.githubusercontent.com/63869574/140072672-926d5f6a-51e7-4fa9-a24d-cf0e81f20e69.png)

Consider that (https://wiki.york.ac.uk/display/RCS/VK1%29+How+to+access+Viking)
![image](https://user-images.githubusercontent.com/63869574/140072626-d129265e-7054-468d-8c85-f3dbf6ea2e78.png)

## How to copy files to Viking
For Windows, it needs WinScp https://winscp.net/eng/download.php. When installing, select import from PuTTy
![image](https://user-images.githubusercontent.com/63869574/140094327-1d5b9b99-f253-46c1-906e-a9786ddfb95f.png)

Open WinScp and edit the Login sessions adding user name and password, then save:
![image](https://user-images.githubusercontent.com/63869574/140094740-5147ea4a-7662-4844-a8d8-60e4f40cea4f.png)

Follow the direction from to drag and drop files from your PC to Viking:
https://wiki.york.ac.uk/display/RCS/Copying+files+from+another+host+or+desktop+to+interactive+Linux+servers

For other OS follow:
https://wiki.york.ac.uk/pages/viewpage.action?pageId=218794149#VK7)CopyingandmovingyourdatatoViking.-Windows

## Save data to drive
You would need the the Linux Intel/AMD - 64 version of rclone https://rclone.org/downloads/
https://wiki.york.ac.uk/pages/viewpage.action?pageId=218794149#VK7)CopyingandmovingyourdatatoViking.-Windows

You will need to sign in an create a new project on:
https://console.cloud.google.com/apis/

by following the instructions:
https://rclone.org/drive/#making-your-own-client-id
