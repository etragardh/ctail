# ctail
Wrapper around tail.<br />
Thanks to @viss for the idea. It's not new.<br />
The old ones are just not maintained and dont run on osx.<br />
I don'n know if they do any attempt to highligt possible attacks?

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
Include parameter for search/grep<br />
Inlcude parameter for highlight specifik keyword (ie single ip adress, GET requests etc)<br />
Ability to create own styling from config file<br />

![ctail colored tail](https://github.com/etragardh/ctail/blob/main/assets/ctail.png?raw=true)
