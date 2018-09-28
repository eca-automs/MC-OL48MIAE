# MC-OL48MIAE

Schema quadro elettrico per ascensore serie `mcpx`. Impianto oleodinamico con emergenza.

Puoi trovare il repository dello schema su
<a href="https://github.com/eca-automs/MC-OL48MIAE" target="_blank">GitHub</a>.

### Scheda controllo
MCPX2015-SMD - PER16B-SMD

### Tipo impianto
Oleodinamico

### Manovra
Universale

### Operatore porte
Automatic trifase, automatico elettronico, manuale

### Avviamento / controllo motore
Diretto, stella-triangolo, soft-starter SMS-start

### Potenza massima motore / taglie compatibili

#### Avviamento diretto
Taglia|Potenza
---|---|---
S20|8CV-230VAC/15CV-400VAC
S30|10CV-230VAC/17CV-400VAC

#### Avviamento stella-triangolo
Taglia|Potenza
---|---|---
S40|14CV-230VAC/22CV-400VAC
S50|17CV-230VAC/28CV-400VAC

#### Avviamento soft-starter
Taglia|Potenza
---|---|---
S40|10CV-230VAC/20CV-400VAC
S50|13CV-230VAC/25CV-400VAC

### Allarme
12VDC, legge 13, allarme porte aperte fuori piano.

### Emergenza
Totale con riapertura porte tramite scheda SMS miae.
