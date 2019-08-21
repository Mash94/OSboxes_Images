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
## OpenCV
```
sudo apt update
sudo apt install python3-opencv
```
```
python3 -c "\
import cv2
print(cv2.__version__)"
```
## Visual Code

```
sudo apt update
sudo apt install software-properties-common apt-transport-https wget
wget -q https://packages.microsoft.com/keys/microsoft.asc -O- | sudo apt-key add -
sudo add-apt-repository "deb [arch=amd64] https://packages.microsoft.com/repos/vscode stable main"
sudo apt update
sudo apt install code
```
