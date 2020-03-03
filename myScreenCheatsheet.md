# Linux screen cheatsheet

## Commonly used

| Command                    | Description                          |
|----------------------------|--------------------------------------|
| `screen -S <session_name>` | Start a new screen with session name |
| `screen -ls`               | List running screens                 |
| `echo $STY`                | Print current screen                 |
| `screen -x`                | Attach to a running screen           |
| `screen -r <session_name>` | Attach to a running screen with name |
| `screen -d <session_name>` | Detach a running screen              |
