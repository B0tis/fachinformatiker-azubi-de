---
title: TCP - Verbindungsabbau
---

# TCP - Verbindungsabbau

Der TCP - Verbindungsabbau wird erzeugt um einen Dienst anzubieten. Dabei wird Socket bereit gestellt mit IP und Port Nummer (Socket).

## Verbindungsaufbau

1.  Client sendet ein **SYN-Paket** (English: synchronize).
    Sequenznummer wird z.B. die 100 genommen.
2.  Server sendet das **ACK-Paket** (English: acknowledge) Paket
    zurück + einer eins, also 101. Daraufhin schickt der Server auch
    noch das **SYN-Paket** mit einer Nummer z.B. 500.
3.  Client beantwortet nun dem Server mit dem **ACK-Paket** Paket und
    der Nummer 501.
