# T-UI Expert [archived]

This repository is archived! T-UI Expert features will be merged into orginal T-UI.
Please use the next T-UI version!


Telegram:
* [theme from the screenshot](https://t.me/T_uiThemes/50)


# Fixes:
* hotfix for double(or more) notifications
* prevent crash caused by the battery reciever
* (transparent) cursor color works again

## Fixes for root:
* make wifi cmd more reliable
* airplane mode works again
* tap to lock does not disable fingerprint anymore

# Features

### [Termux integration](https://github.com/v1nc/TUI-Expert/wiki/Termux-integration)

### Root commands:
* `airplane`   toggle airplane mode
* `battery`    toggle battery saver mode
* `cellular`   toggle cellular connection
* `nfc`        toggle nfc
* `reboot`
* `recovery`   reboot straight into recovery
* `rotate`     toggle rotating screen
* `shutdown`   power off your phone
* `sleeptimer` after given minutes, your phone shuts down
### Custom command output:
your command is executed periodically, the output is printed to the top of the terminal!
- `config -set custom_command wget -qO- wttr.in/your_city_name\?0T`
- `config -set custom_command_timeout 60`(refresh every 60s)

### Kill command:
instantly close apps, just type kill!

### More Settings:
* `numbering_notes` [true/false]: notes are numbered automatically
* `show_help` [true/false]: show/hide help command
* `show_call` [true/false]: show/hide call command
* `show_exit` [true/false]: show/hide exit command
* `exit_password` [string]: exit command asks for a password if specified
* `user_root` [true/false]: always use root if possible
