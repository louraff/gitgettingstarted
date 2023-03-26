# git getting started
Step 1
---
Clone this repository:
```bash
git clone {theurlofthisrepo} 
```
Step 2
---
Cd into this repo:
```bash
cd gitgettingstarted
```
Step 3
---
Run my JavaScript file:
```bash
node gitgettingstarted.js
```
Step 4
---
Make a change to the file and save it then run the following commands to the remote repo:
```bash
git checkout -b mycoolfeature
git add . 
# lets check that out chages are 'staged' 
git status
git commit -m "here's my cool feature" 
git push 
```
