# PhononVideoPlayer
VideoPlayer (Qt4)

# VideoSchneiden
cut Video (Qt4)

# QT5_Videoplayer
VideoPlayer (Qt5)

##creating an executable on Linux:
```
pyinstaller QT5_VideoPlayer.py
```
when errors about missing Qt5 Files use:
```
pyinstaller -y --distpath="." -p "/usr/lib/python3/dist-packages/PyQt5/" QT5_VideoPlayer.py
```
[Download 32 bit compiled Linux App](https://www.dropbox.com/s/66lw4rithsk1789/QT5_VideoPlayer.zip?dl=1)
