Samplerbox can be configured via files found on this partition.
Background information on http://homspace.xs4all.nl/homspace/samplerbox/index.html
..or in the webgui if you have the box already up & running.

In the root:
- config.txt
  Adapting is only necessary when using devices requiring own drivers
  HiFiBerry is given as commented examples

In this directory:
- configuration.txt
  Contains comments on various parameters
  Check and adapt it to your setup, wiring, preferences etc
- accesspoint.txt
  To set network (SSID) and password of the webgui via the wifi adapter
  Comments in the file will guide you
- midi_controllers.csv
  Here you tell samplerbox the specifics of your midi controller regarding
  the control change messages it sends via the knobs, buttons, drawbars, pedals.
  Other messages like (notes and program changes) are standard.
- midi_mapping.csv
  Here you tell how you want your knobs, buttons, drawbars, pedals to affect
  the available functions in samplerbox
- chords.csv and scales.csv
  The chords and scales to be generated by samplerbox
- README_CSV.txt
  The syntax and layout explanation of all these csv files
- fstab.txt
  To change the mountpoint of your USB stick if needed, see info on:
  http://homspace.xs4all.nl/homspace/samplerbox/SBbuild.html#fstab
  