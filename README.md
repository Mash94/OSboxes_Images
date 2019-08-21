# OSboxes_Images
A little list of steps to follow to change some important parameters as UserName, password user, password root

Press F12
Press SHIFT

Recovery Mode
Root
```
mount -o remount,wr /
```
```
passwd <username>
```
change it
```
passwd root
```
  change it
```  
sudo usermod -l <newname> -d /home/<newname> -m <oldname>
```
```
sudo apt update
sudo apt install python3-opencv
```
```
python3 -c "\
import cv2
print(cv2.__version__)"
```
