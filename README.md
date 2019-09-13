# iksilo
Tajpu Esperante per la *x metodo*

Type in Esperanto using the *x method*

# Uzado/usage:
Metu la programeton en via PATH, igu ĝin rulebla. `$ iksilo start` por ekuzi. `$ iksilo stop` por haltigi.
Dum kiam rulas la programeto, vi povas tajpi uzante la *x metodon* (ekz., *cx* iĝas *ĉ*).

Put the script in your PATH, make it executable. `$ iksilo start` to start using. `$ iksilo stop` to stop using.
While script is running, you can type using the *x method* (e.g., *cx* becomes *ĉ*).

# Postuloj/requirements:
- GNU/Linux aŭ OpenBSD: Vi bezonas **X** kaj **xdotool**. Mi rekomendas *dzen2* sed ĝi ne estas deviga.
---
- GNU/Linux or OpenBSD: You need **X** and **xdotool**. *dzen2* is recommended but not required.

# Kiel ĝustigi la programeton por via operaciumo/adjusting the script for your OS:
- Uzu `$ xinput list` por trovi la id-numeron de via klavaro, metu la numeron ĉe la supro de la programo.
- Krom tio, vi bezonas ŝanĝi nenion. La programeto funkcias almenaŭ en GNU/Linukso kun coreutils, GNU/Linukso kun BusyBox kaj OpenBSD. (Verŝajne ĝi funkcius en iu ajn UNIX-stila operaciumo kiu uzas X, ĉar la programeto bezonas nur ŝelon kaj *xdotools*.)
---
- Run `$ xinput list` to get your keyboard id, put it at the appropriate spot near top of script.
- Other than that, you don't need to change anything. The script works at least in GNU/Linux with coreutils, GNU/Linux with BusyBox and OpenBSD. (It probably would work in any UNIX-like OS running X, since all it needs is a shell and *xdotools*.)
