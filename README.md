# ctail
Wrapper around tail.
Thanks to "viss" for the idea. It's not new.
The old ones are just not maintained and dont run on osx.

**Install**
```
gh repo clone etragardh/ctail
chmod +x ctail/ctail
sudo ln -s ${PWD}/ctail/ctail /usr/local/bin
```

**Usage**
```
ctail -n 20 access.log
ctail -f access.log
```

Your log now has colors =)

### Todo
Include parameter for search/grep
Inlcude parameter for highlight specifik keyword (ie single ip adress, GET requests etc)
Ability to create own styling from config file

![ctail colored tail](https://github.com/etragardh/ctail/blob/main/assets/ctail.png?raw=true)
