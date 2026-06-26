# White Paper v2.0 — Scientific Structure

## 1. Abstract

Il Magnetically Captured Plasma Drive (MCPD) è un sistema di propulsione ibrido che combina un kick nucleare iniziale con un motore al plasma capace di catturare e accelerare il plasma interplanetario tramite campi magnetici ad alta efficienza.  
L’obiettivo è ridurre drasticamente la massa di propellente, ottenere spinta continua e raggiungere Δv cumulativi elevati in tempi di missione ridotti.

## 2. Background & Motivation

### Limiti della propulsione chimica
- Isp molto basso (300–450 s).  
- Richiede enormi quantità di propellente.  
- Non adatta a missioni interplanetarie rapide.

### Limiti della propulsione elettrica convenzionale
- Isp alto, ma thrust estremamente basso (mN–N).  
- Necessita di grandi pannelli solari.  
- Non scalabile per missioni con carichi pesanti.

### Necessità di sistemi ibridi ad alto Isp e thrust continuo
Serve un sistema che combini:
- thrust significativo,  
- Isp elevato,  
- funzionamento continuo,  
- ridotto consumo di propellente.

### Stato dell’arte
- VASIMR: ottimo Isp, ma richiede potenze enormi.  
- MPD thrusters: limitati da erosione degli elettrodi.  
- NTR: ottimo thrust, ma Isp limitato.  
- Concetti a fusione: ancora non maturi.

Il MCPD nasce per colmare questo vuoto tecnologico.

## 3. Concept Overview

### Architettura ibrida NTR + MCPD
- L’NTR fornisce il Δv iniziale.  
- Il MCPD fornisce spinta continua per tutta la crociera.

### Principio di cattura del plasma interplanetario
Il plasma del vento solare viene catturato tramite un funnel magnetico a larga apertura, evitando la necessità di trasportare propellente.

### Ruolo del campo magnetico e della compressione
- Il campo magnetico guida e confina il plasma.  
- La compressione impulsiva (theta‑pinch) aumenta temperatura e pressione.  
- L’ugello magnetico converte energia termica in spinta.

## 4. System Architecture

### Magnetic Plasma Intake (MPI)
Perché esiste: risolve il problema della mancanza di propellente catturando il plasma interplanetario.

Principio tecnico:
- Funnel magnetico con HTS.  
- Gradiente magnetico controllato.  
- Aumento densità 10–100×.

### Plasma Confinement Chamber (PCC)
Perché esiste: stabilizza il plasma catturato, che è turbolento e instabile.

Principio tecnico:
- Mini‑tokamak.  
- Controllo MHD attivo.  
- Pressione magnetica regolata.

### RF Heating Assembly (PHA)
Perché esiste: il plasma è troppo freddo, va riscaldato prima della compressione.

Principio tecnico:
- ECRH/ICRH.  
- Aumento temperatura a decine/centinaia di eV.  
- Uniformazione energetica.

### Capacitive Pulse Compression System (CPCS)
Perché esiste: serve aumentare enormemente la pressione del plasma per ottenere spinta significativa.

Principio tecnico:
- Banco di condensatori.  
- Scarica compressa in microsecondi.  
- Theta‑pinch ad alto dB/dt.

### Magnetic Nozzle Assembly (MNA)
Perché esiste: converte l’energia del plasma compresso in spinta direzionata.

Principio tecnico:
- Ugello magnetico divergente.  
- Controllo del detachment.  
- Variazione del vettore di spinta.

## 5. Physics Basis

### Equazioni MHD (forma semplificata)
Il comportamento del plasma è descritto dalle equazioni magnetoidrodinamiche:
- conservazione della massa  
- conservazione della quantità di moto  
- induzione magnetica  
- pressione magnetica vs pressione termica  

### Plasma capture efficiency
Dipende da:
- apertura del funnel  
- intensità del campo  
- velocità relativa plasma‑veicolo  

### Magnetic mirror confinement
Il PCC sfrutta il principio dello specchio magnetico per confinare gli ioni.

### ECRH/ICRH heating physics
Risonanza ciclotronica → trasferimento efficiente di energia.

### Theta‑pinch compression
Compressione radiale impulsiva → aumento di pressione e temperatura.

### Magnetic nozzle detachment
Il plasma deve staccarsi correttamente dal campo per generare spinta.

## 6. Performance Estimates

- Isp atteso: 4.000–6.000 s  
- Thrust continuo: 25–50 N  
- Δv cumulativo: 10–15 km/s  
- Transfer Terra–Marte: 90–150 giorni  

## 7. Simulation Plan

- Modello MHD 2D  
- Particle tracking  
- Field topology mapping  
- Simulazione del detachment dell’ugello  

## 8. Prototype Roadmap

- Test delle bobine HTS  
- Banco di prova RF  
- Mockup della camera toroidale  
- Dimostratore integrato  

## 9. Mission Applications

- Trasferimento rapido Terra–Marte  
- Sonde per pianeti esterni  
- Cargo deep‑space  
- Missioni di mappatura del Sistema Solare  

## 10. Open Research Questions

- Variabilità della densità del plasma solare  
- Ottimizzazione dell’intake magnetico  
- Scalabilità del riscaldamento RF  
- Affidabilità delle bobine superconduttive  

## 11. Conclusion

Il MCPD rappresenta una possibile architettura ibrida scalabile, capace di combinare alto Isp, thrust continuo e ridotto consumo di propellente, aprendo la strada a missioni interplanetarie rapide e sostenibili.

## 12. References

(vedi bibliografia tecnica)

