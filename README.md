# Apex Linux Terminal

Ein isoliertes, performantes **Rootfs-Terminal (6,4 GB)** für Linux-Systeme (Zorin OS, Linux Mint u. a.). Es basiert auf einer eigenständigen Dateisystem-Struktur und lässt sich ohne Root-Rechte direkt über `proot` ausführen.

---

## Features

- **Rootless & Isoliert:** Läuft direkt im User-Space mittels `proot` ohne invasive Systemänderungen.
- **Portabel:** Kann als `.tar.zst`-Archiv auf beliebig vielen Linux-Systemen entpackt und sofort genutzt werden.
- **Saubere Systemintegration:** Keine Manipulationen der globalen Shell-Konfigurationen (`~/.bashrc`).

---

## Ordnerstruktur

```text
Apex-Linux-Terminal/
├── bin/                 # Ausführbare System-Binärdateien
├── etc/                 # Konfigurationsdateien (os-release, resolv.conf etc.)
├── lib/ / lib64/        # Systembibliotheken
├── usr/                 # Erweiterte Programmpfade
├── home/                # Lokaler Benutzerbereich im Rootfs
└── README.md            # Dokumentation
