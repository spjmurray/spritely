# Spritely

A tiny Ruby script to render PNG sprites to your terminal

## Description

Accepts a PNG file on the command line and prints it out as 32 bit coloured
unicode characters on the screen.  Handles alpha channels automatically, just
ensure the only valid values are 0 or 255.  Weird things may happen otherwise.

Typical uses are to call the script from /etc/update-motd.d to make logins
a little bit nicer.
