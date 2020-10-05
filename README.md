# polybar-volume-slider
<img src="https://i.ibb.co/gT30CNK/image.png" alt="image" border="0"><br>
A volume slider for polybar on i3wm using pulseaudio.

## Functions
-1 default click to mute is still available
-1 change the volume by scrolling up / down with mouse hovering the slider

## Code
Replace the audio module inside your polybar configuration file with code below.
You can change the coloe by replacing all the ${colors.primary}
```
[module/audio]
type = internal/pulseaudio

format-volume = <ramp-volume> <bar-volume>

label-volume-foreground = ${colors.primary}
format-muted-foreground = ${colors.primary}
label-muted-foreground = ${colors.primary}
label-muted =  

ramp-volume-0 = 
ramp-volume-1 = 墳
ramp-volume-2 = 
ramp-volume-foreground = ${colors.primary}

bar-volume-width = 10
bar-volume-foreground-0 = ${colors.primary}
bar-volume-foreground-1 = ${colors.primary}
bar-volume-foreground-2 = ${colors.primary}
bar-volume-foreground-3 = ${colors.primary}
bar-volume-foreground-4 = ${colors.primary}
bar-volume-foreground-5 = ${colors.primary}
bar-volume-foreground-6 = ${colors.primary}
bar-volume-gradient = false
bar-volume-indicator = 
bar-volume-indicator-font = 4
bar-volume-indicator-foreground = ${colors.primary}
bar-volume-fill = 
bar-volume-fill-font = 4
bar-volume-empty = 
bar-volume-empty-font = 4
bar-volume-empty-foreground = ${colors.primary}

```

## Dependencies
<a href ="https://www.nerdfonts.com/cheat-sheet">Nerd Fonts</a> <br>
<a href ="https://wiki.ubuntu.com/PulseAudio">pulseaudio</a>
