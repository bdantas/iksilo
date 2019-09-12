# iksilo
Type in Esperanto using the *x method*
Tajpu Esperante per la *x metodo*

# Usage:
Put the script in your PATH, make it executable. `$ iksilo start` to start using. `$ iksilo stop` to stop using.
While script is running, you can type into most applications using *x method* (e.g., *cx* becomes *ĉ*).

# Requirements:
- GNU/Linux: You must be running **X** and must install **xdotool**. *dzen2* is optional.
- OpenBSD: You must be running **X** and must install **xdotool** and **coreutils**. *dzen2* is optional.

# Adjusting the script for your OS:
- All OSes: Run `$ xinput list` to get your keyboard id, put it at the appropriate spot near top of script.
- GNU/Linux with coreutils: No further adjustments needed.
- GNU/Linux with busybox: Delete *stdbuf -oL*
- OpenBSD: Change *stdbuf -oL* to *gstdbuf -oL*
