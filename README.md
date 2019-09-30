# iksilo
Tajpu Esperante per x-sistemo

ehxosxangxocxiujxauxde -> eĥoŝanĝoĉiuĵaŭde

# Postuloj:
- UNIX-stila operaciumo (GNU/Linukso aŭ BSD) rulante X fenestrokrean sistemon
- Devigaj: *xdotool*, *xinput*, *setxkbmap*, *xmodmap*
- Nedeviga: *dzen2*

# Instalado:
```
$ sudo apt install xdotool xinput x11-xkb-utils x11-xserver-utils dzen2
$ cd /tmp
$ wget https://github.com/bdantas/iksilo/blob/master/iksilo
$ unzip master.zip
$ sudo cp ./iksilo-master/iksilo /usr/local/bin/iksilo
$ sudo chmod a+x /usr/local/bin/iksilo
```
Notu: La unua paŝo ĉi-supre estas por Debian, Ubuntu kaj aliaj Debian-idoj; se via operaciumo estas iu alia, ŝanĝetu la unuan paŝon

# Uzado:
`$ iksilo start` por eki kaj `$ iksilo stop` por halti
