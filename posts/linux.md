# Linux commands

**How to view disk usage summary of a directory:**

```
du [folder]
``` 

**How to view a grand total for a directory:**

```
du -c [folder]
```

**How to view disk usage in human readable format:**

```
du -h [folder]
```

**How to view the file size of a directory:**

```
du -s [folder]  # Print a grand total size of the folder
du -sh [folder]  # -h option is a human readable format
```
**How to zip a folder:**

```
zip -r zipfile.zip directory
```
**How to change extension of multiple files using linux terminal**

```
# changing extension from .png to .jpg
for i in *.png; do mv -- "$i" "${i%.log}.jpg"; done
```
