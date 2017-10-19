---
title: LPIC-1 Manpages-Sammlung
header-includes:
- \usepackage{manpages}
---

\subsection*{Vorbemerkung}

Dieses Buch ist eine Sammlung von manpages, die für die Prüfung LPIC-1 relevant sind. Die Auswahl basiert dem Buch »LPIC-1. Sicher zur erfolgreichen Linux-Zertifizierung« von Harald Maaßen, 3., auktualisierte Auflage 2012.

Es handelt sich *nicht* um eine erschöpfende Materialsammlung, sondern lediglich
um *die* Punkte, zu denen Manpages existieren (also beispielsweise keine
Systemverzeichnisse und nur wenige Konfigurationsdateien). Manpages, die fehlen,
weil die entsprechenden Pakete auf dem  Rechner nicht installiert sind, auf dem
dieses Dokument erzeugt wurde, werden als fehlend im Inhaltsverzeichnis
kenntlich gemacht.

# Topic 101: Systemarchitektur

## 101.1 Hardware-Einstellungen ermitteln und konfigurieren

\man{uname}
\man{lsmod}
\man{modinfo}
\man{insmod}
\man{rmmod}
\man{modprobe}
\man{depmod}
\man{modules.dep}
\man{modules.conf}
\man{modprobe.conf}
\man{modprobe.conf.local}
\man{lspci}
\man{lsusb}
\man{usbmgr}
\man{hotplug}
\man{sysfs}
\man{udev}
\man{hald}
\man{dbus}

## 101.2 Das System starten

\man{dmesg}
\man{less}
\man{}

## 101.3 Runlevel wechseln und das System anhalten oder neu starten

\man{ps}
\man{pstree}
\man{inittab}
\man{init}
\man{init.d}
\man{update-rc.d}
\man{runlevel}
\man{shutdown}
\man{halt}
\man{reboot}
\man{poweroff}
\man{sysctl}
\man{systemctl}

# Topic 102: Linux-Installation und -Paketverwaltung
