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
---

<div style="background:#0d0d0d; padding:25px; border-radius:10px; color:#e6e6e6;">

## 4.1.1 Funnel Magnetico Dinamico – RMF‑Enhanced Plasma Capture

### **Overview del Concetto**
Il *Funnel Magnetico Dinamico* (FM‑DYN) è un’estensione avanzata del modulo MPI.  
Utilizza **campi magnetici rotanti (RMF)** per generare **correnti indotte nel plasma esterno**, amplificando il campo magnetico primario e creando una struttura di cattura più estesa ed efficiente.

Questo permette di ottenere un funnel magnetico **più grande della geometria fisica delle bobine**, aumentando la quantità di plasma catturato e riducendo le perdite laterali.

---

### **Principio di Funzionamento**

#### **1. Generazione del Campo Base**
Le bobine HTS del MPI creano un campo magnetico conico orientato verso la direzione di avanzamento.  
Questo è il funnel primario.

#### **2. Applicazione del Rotating Magnetic Field (RMF)**
Un set di bobine RMF genera un campo magnetico rotante.  
L’interazione RMF–plasma induce **correnti toroidali** nel plasma esterno.

Queste correnti generano un campo magnetico secondario che:
- amplifica il campo base,
- ne estende la geometria,
- stabilizza il flusso di cattura.

#### **3. Formazione del Funnel Magnetico Dinamico**
Il plasma esterno diventa parte attiva della struttura magnetica, creando un funnel:
- più largo in ingresso,
- più stretto nel collo,
- più stabile,
- con maggiore densità di particelle convogliate verso la PCC.

---

### **Benefici Tecnici**

- **Aumento dell’area di cattura:** funnel più grande della bobina fisica.  
- **Riduzione della potenza richiesta:** correnti indotte sostengono parte del campo.  
- **Stabilizzazione del flusso:** riduzione instabilità MHD.  
- **Compatibilità totale:** si integra con MPI → PCC → PHA → CPCS → MNA.

---

### **Considerazioni Energetiche**
Il FM‑DYN richiede:
- potenza moderata (ordine dei kW),
- controllo fine della frequenza RMF,
- sincronizzazione con il campo base del MPI.

---

### **Implicazioni per la Roadmap MCPD**
L’introduzione del FM‑DYN abilita:
- funnel magnetici più efficienti,
- moduli di cattura scalabili,
- maggiore densità di plasma nella PCC,
- miglioramento dell’efficienza complessiva del motore.

</div>

---


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

