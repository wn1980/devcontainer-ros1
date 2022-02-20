# ros1-devcontainer

## X applications
To run X apps, e.g., `rviz`, type this commands in host terminal:
```
$ xhost local:root
```
## Display setting
Add this setting in `devcontainer.json`
```
"containerEnv": {
    "DISPLAY": "unix:0"
},
```
## GPU setting
Add this setting in `devcontainer.json`
```
"runArgs": ["--runtime=nvidia"] or "runArgs": ["--gpus all"]
```