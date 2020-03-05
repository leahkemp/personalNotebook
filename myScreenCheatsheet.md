# Linux screen cheat sheet

## Commonly used

| Command                                       | Description                          |
|-----------------------------------------------|--------------------------------------|
| `screen -S <session_name>`                    | Start a new screen with session name |
| `screen -ls`                                  | List running screens                 |
| `echo $STY`                                   | Print current screen                 |
| `screen -x`                                   | Attach to a running screen           |
| `screen -r <session_name>`                    | Attach to a running screen with name |
| `screen -d <session_name>`                    | Detach a running screen              |
| <kbd>Ctrl</kbd> + <kbd>a</kbd> + <kbd>d</kbd> | Detach from the screen you are in    |

## Stopping a screen

| Command                         | Description                                                        |
|---------------------------------|--------------------------------------------------------------------|
| `$ screen -XS [session #] quit` | Kill a screen by number                                            |
| `killall screen`                | :heavy_exclamation_mark:Kill *ALL* screens:heavy_exclamation_mark: |
