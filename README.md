# OSboxes_Images and Ubuntu 18.04
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
## Installing pip for Python 3

Ubuntu 18.04 ships with Python 3, as the default Python installation. Complete the following steps to install pip (pip3) for Python 3:

Start by updating the package list using the following command:
```
sudo apt update
```
Use the following command to install pip for Python 3:
```
sudo apt install python3-pip
```
The command above will also install all the dependencies required for building Python modules.
Once the installation is complete, verify the installation by checking the pip version:
```
pip3 --version
```
## Jupyter Notebook
```
python3 -m pip install --upgrade pip
python3 -m pip install jupyter
```
### Run Jupyter

```
jupyter notebook
```
