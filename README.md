# notes

# MacOS

Fix annoying Apple Music auto launch on media key press

```bash

launchctl bootout "gui/$(id -u "${USER}")/com.apple.rcd"
launchctl disable "gui/$(id -u "${USER}")/com.apple.rcd"


```
