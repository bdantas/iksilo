# iksilo
Tajpu Esperante per x-sistemo

ehxosxangxocxiujxauxde -> eĥoŝanĝoĉiuĵaŭde

# Postuloj
- UNIX-stila operaciumo (GNU/Linukso aŭ BSD) rulante X fenestrokrean sistemon
- Devigaj: *xdotool*, *xinput*, *setxkbmap* (ofte inkluzivita en *x11-xkb-utils*), *xmodmap* (ofte inkluzivita en *x11-xserver-utils*)
- Nedeviga: *yad*

# Instalado
```
$ sudo apt install xdotool xinput x11-xkb-utils x11-xserver-utils yad
$ cd /tmp
$ wget https://github.com/bdantas/iksilo/archive/master.zip
$ unzip master.zip
$ cd iksilo-master
$ sudo cp iksilo /usr/local/bin
$ sudo chmod a+x /usr/local/bin/iksilo
$ sudo cp iksilo.png /usr/share/icons
```
Notu: Se via operaciumo ne estas Debian-stila, ĝustigu la unuan paŝon

# Uzado
`iksilo start` por eki kaj `iksilo stop` por halti
