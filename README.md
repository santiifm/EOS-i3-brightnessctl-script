# EOS-i3-brightnessctl-script
The native EndeavourOS i3 brightness controller didn't work with my thinkpad t14 so I replaced xbrightness with brightnessctl for better compatibility.

Usage: Just drop it into your ~/.config/i3/scripts folder and call it like "bindsym XF86MonBrightnessUp exec --no-startup-id ~/.config/i3/scripts/volume_brightness.sh brightness_up" if you would for example want to
bind your laptop's brightness up fn function key.
