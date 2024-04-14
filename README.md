# ctail
Wrapper around tail.<br />
Thanks to [@viss](https://github.com/viss) for the idea. It's not new.<br />
The old ones are just not maintained and dont run on osx.<br />
I don'n know if they do any attempt to highligt possible attacks?<br />
This is the [original](https://github.com/cornet/ccze)<br />

**Install**
```
cd ~/
gh repo clone etragardh/ctail
chmod +x ctail/ctail
sudo ln -s ${PWD}/ctail/ctail /usr/local/bin
```

**Usage**
```
ctail -n 20 access.log
ctail -f access.log
```

Your log now has colors =)<br />

**Update**
Go to `ctail` directory (`~/ctail` if you followed installation instructions)
```
cd ~/ctail
git pull
```

## Warnings
And it might warn you about some dangerous requests blinking in red.

`scans`/hackwp/wpscan/dirbuster etc<br />
`php`/php in uploads or other places<br />
`sensitive data`/.env/.log/.git etc<br />

## Who did visit you
It might also help you separte users.<br />
`YOU`/local<br />
`SCR`/scripts<br />
`BOT`/Googlebot etc<br />

### Todo
Include parameter for search/grep<br />
Inlcude parameter for highlight specifik keyword (ie single ip adress, GET requests etc)<br />
Ability to create own styling from config file<br />
Separate config based on input log format / logfile / logged service<br />

![ctail colored tail](https://github.com/etragardh/ctail/blob/main/assets/ctail.jpg?raw=true)

## Support
<p><a href="https://www.buymeacoffee.com/etragardh"> <img align="left" src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="50" width="210" alt="etragardh" /></a></p>
