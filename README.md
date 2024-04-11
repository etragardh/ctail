# ctail
like tail but colored based on severity
This is a work in progress =)

**Install**
```
gh repo clone etragardh/ctail
chmod +x ctail/ctail
ln -s ctail/ctail /usr/local/bin
```

**Usage**
```
ctail -n 20 access.log
```

Your log now has colors =)

### Todo
Include parameter for search/grep
Inlcude parameter for highlight specifik keyword (ie single ip adress, GET requests etc)
