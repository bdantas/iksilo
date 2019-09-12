# iksilo
Tajpu Esperante per la *x metodo*

Type in Esperanto using the *x method*

# Uzado/usage:
Metu la programeton en via PATH, igu ĝin rulebla. `$ iksilo start` por ekuzi. `$ iksilo stop` por haltigi.
Dum kiam rulas la programeto, vi povas tajpi uzante la *x metodon* (ekz., *cx* iĝas *ĉ*).

Put the script in your PATH, make it executable. `$ iksilo start` to start using. `$ iksilo stop` to stop using.
While script is running, you can type using the *x method* (e.g., *cx* becomes *ĉ*).

# Postuloj/requirements:
- GNU/Linux: Vi bezonas **X** kaj **xdotool**. *dzen2* estas nedeviga.
- OpenBSD: Vi bezonas **X**, **xdotool** kaj **coreutils**. *dzen2* estas nedeviga.
---
- GNU/Linux: You must be running **X** and must install **xdotool**. *dzen2* is optional.
- OpenBSD: You must be running **X** and must install **xdotool** and **coreutils**. *dzen2* is optional.

# Kiel ĝustigi la programeton por via operaciumo/adjusting the script for your OS:
- Ĉiuj operaciumoj: Uzu `$ xinput list` por trovi la id-numeron de via klavaro, metu la numeron ĉe la supro de la programo.
- GNU/Linukso kun coreutils: Neniu alia ŝanĝo estas bezonata.
- GNU/Linukso kun busybox: Forigu *stdbuf -oL*
- OpenBSD: Ŝanĝu *stdbuf -oL* al *gstdbuf -oL*
---
- All OSes: Run `$ xinput list` to get your keyboard id, put it at the appropriate spot near top of script.
- GNU/Linux with coreutils: No further adjustments needed.
- GNU/Linux with busybox: Delete *stdbuf -oL*
- OpenBSD: Change *stdbuf -oL* to *gstdbuf -oL*
