---
title: LPIC-1 Manpages-Sammlung
header-includes:
- \usepackage{manpages}
---

\subsection*{Vorbemerkung}

Dieses Buch ist eine Sammlung von manpages, die für die Prüfung LPIC-1 relevant sind. Die Auswahl basiert dem Buch »LPIC-1. Sicher zur erfolgreichen Linux-Zertifizierung« von Harald Maaßen, 3., aktualisierte Auflage 2012.

Es handelt sich *nicht* um eine erschöpfende Materialsammlung, sondern lediglich
um *die* Punkte, zu denen Manpages existieren (also beispielsweise keine
Systemverzeichnisse und nur wenige Konfigurationsdateien). Manpages, die fehlen,
weil die entsprechenden Pakete auf dem  Rechner nicht installiert sind, auf dem
dieses Dokument erzeugt wurde, werden als fehlend im Inhaltsverzeichnis
kenntlich gemacht.

# Allgemeine Pakete

\man{ls}
\man{less}

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

## 102.1 Festplattenaufteilung planen

\man{fdisk}

## 102.2 Einen Bootmanager installieren

**Unklar, welche Pakete hier noch reinsollen**

\man{update-grub}
\man{update-grub2}

## 102.3 Shared Librarys verwalten

\man{ldd}
\man{ldconfig}

## 102.4 Debian-Paketverwaltung verwenden

\man{sources.list}
\man{dpkg}
\man{dpkg.cfg}
\man{apt}
\man{apt-get}
\man{aptitude}
\man{dselect}
\man{alien}

## 102.5 RPM und YUM-Paketverwaltung verwenden

\man{rpm}
\man{rpm2cpio}
\man{yum.conf}
\man{yum}
\man{yumdownloader}
