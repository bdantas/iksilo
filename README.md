# iksilo
Tajpu Esperante per x-sistemo

ehxosxangxocxiujxauxde -> eĥoŝanĝoĉiuĵaŭde

# Postuloj:
- UNIX-stila operaciumo (GNU/Linukso aŭ BSD) rulante X fenestrokrean sistemon
- Devigaj: *xdotool*, *xinput*, *setxkbmap*, *xmodmap*
- Nedeviga: *dzen2*

Notu: En kelkaj operaciumoj (ekz. Debian, Ubuntu kaj aliaj Debian-idoj) *setxkbmap* estas ene de *x11-xkb-utils* kaj *xmodmap* estas ene de *x11-xserver-utils*

# Instalado:
```
sudo apt install xdotool xinput x11-xkb-utils x11-xserver-utils dzen2
cd /tmp
wget https://github.com/bdantas/iksilo/blob/master/iksilo
unzip master.zip
sudo cp ./iksilo-master/iksilo /usr/local/bin/iksilo
sudo chmod a+x /usr/local/bin/iksilo
```
Notu: La unua paŝo supre estos malsama por vi se via operaciumo ne estas Debian, Ubuntu aŭ iu Debian-ido

# Uzado:
`iksilo start` por eki kaj `iksilo stop` por halti
