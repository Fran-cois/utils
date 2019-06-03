# Read / Write ntfs drive on mac os 

```
brew cask install osxfuse
brew install ntfs-3g
```

```
sudo mkdir /Volumes/NTFS
```

# Get the ntfs drive.
```
diskutil list
```

```
sudo diskutil umount /dev/diskXsY

sudo /usr/local/bin/ntfs-3g /dev/diskXsY /Volumes/NTFS -olocal -oallow_other
```




