# CUCCIOLO-MECCANICO

Cucciolo.Meccanico è un rover 12V controllato via Wi-Fi, costruito come progetto personale di robotica mobile e prototipazione hardware/software.

Il progetto usa Arduino UNO R4 WiFi, driver motore IBT-2/BTS7960, motoriduttori DC 12V, componenti stampati in 3D e una semplice interfaccia web per il controllo manuale.

Stato del progetto

* controllo web funzionante
* movimento avanti/indietro validato
* prima sterzata validata
* mozzi PLA prototipali testati
* debug reale su attrito, peso batteria e sterzata skid-steering
* prossimo step: hub metallici D-shaft, parti in PETG e cablaggio più pulito

Tecnologie usate

* Arduino UNO R4 WiFi
* C/C++
* Wi-Fi control
* IBT-2 / BTS7960 motor driver
* motori DC 12V
* stampa 3D
* Bambu Lab A1
* Bambu Studio
* OpenSCAD / Tinkercad
* cablaggio 12V

Funzioni attuali

* comando avanti
* comando indietro
* comando sinistra/destra
* stop
* controllo velocità via interfaccia web
* test a terra e a ruote sollevate

Roadmap

v0.6 — Affidabilità meccanica

* hub metallici per albero D-shaft
* ristampa parti stressate in PETG
* fissaggio cavi e driver
* test continuativo di guida

v0.7 — Sensori base

* sensore distanza frontale
* stop automatico anti-ostacolo
* monitoraggio batteria

v0.8 — Telemetria

* log eventi
* stato motori
* stato alimentazione

Obiettivo

Costruire una piattaforma mobile semplice, modulare ed espandibile per sperimentare robotica, automazione, sensori, controllo remoto e prototipazione fisica.