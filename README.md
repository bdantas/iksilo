# iksilo
Tajpu Esperante per x-sistemo

ehxosxangxocxiujxauxde -> eĥoŝanĝoĉiuĵaŭde

# Postuloj
- UNIX-stila operaciumo (GNU/Linukso aŭ BSD) rulante X fenestrokrean sistemon
- Devigaj: *xdotool*, *xinput*, *setxkbmap*, *xmodmap*
- Nedeviga: *yad*

# Instalado
```
$ sudo apt install xdotool xinput x11-xkb-utils x11-xserver-utils yad
$ cd /tmp
$ wget https://github.com/bdantas/iksilo/archive/master.zip
$ unzip master.zip
$ sudo cp ./iksilo-master/iksilo /usr/local/bin/iksilo
$ sudo mkdir -p /usr/share/icons; sudo cp ./iksilo-master/iksilo.png /usr/share/icons/iksilo.png
$ sudo chmod a+x /usr/local/bin/iksilo
```
Notu: Se via operaciumo ne estas Debian-stila, ĝustigu la unuan paŝon

# Uzado
`iksilo start` por eki kaj `iksilo stop` por halti
