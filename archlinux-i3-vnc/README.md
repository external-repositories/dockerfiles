### Info
This is an Archlinux image with only the basic packages needed to get a usable i3 VNC setup. It is best to use this as a base image but if i3-gaps, xterm, and dmenu are useful to you by themselves, then by all means!

### Flags
The image takes the following flags at run time:

`-u|--username` (optional, default: desktop)
`-p|--vnc-password` (optional, default: randomly generate) -  see docker logs for output
`-g|--geometry` (optional, default: 1024x768)

### Run Example for image based on this one
Images based off of this would run something like: 
```
docker run -d <image_name> -u myuser -p mypassword -g 1920x1080
```
