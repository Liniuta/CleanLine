# CleanLine
## CleanLine is a tool that cleans the system of unnecessary files and slightly improves system performance, made in Python.
## This tools works only on **Linux-based** systems
### To-Do List:
- [x] Create a repository.
- [ ] Add more cleaning options.
- [ ] Fix bugs, if i found some.
### Usage:
**Open a terminal, make or navigate to your desired folder and _run_ this**:
``` 
git clone https://github.com/Liniuta/CleanLine 
```
**After this, make sure you are root user, if not, _run_ in terminal:**
```
sudo bash
```
***NOTE: This tool have a function, which checks if user is root or no.***

**Now you can run the tool, simply just _run_**
```
chmod +x clean-line.py
```
**And finally:**
```
python clean-line.py
```
**Things which this tool clean:**
- APT (Advanced Package Tool) cache.
- Journalctl logs.
- Files and folders from recycle bin.
- Thumbnails cache
