# MCPD – Ground Test Bench
### Documento di collaudo a terra del Magnetically Captured Plasma Drive

---

## 1. Scopo e Filosofia del Banco Prova MCPD

Il banco prova MCPD ha l’obiettivo di validare a terra l’intero sistema di propulsione Magnetically Captured Plasma Drive prima del suo impiego in ambiente spaziale.  
A differenza dei test convenzionali sui motori, il banco prova MCPD riproduce l’intera architettura del vettore, includendo:

- Intake magnetico (MPI)  
- Catena energetica (NRM → FHM → PHA)  
- Confinamento (PCC)  
- Compressione (CPCS)  
- Accelerazione magnetica (MNA)  
- Stabilizzazione (MSS)

La filosofia del collaudo è:

**Costruire il sistema completo a terra, alimentare l’intake con plasma reale e misurare la risposta del vettore modulo per modulo.**

Il banco prova non simula il volo: riproduce realmente il comportamento del MCPD, con plasma vero, campi magnetici reali e potenze scalate.

---

## 2. Architettura Fisica del Banco Prova MCPD

Il banco prova è installato in un ambiente controllato, progettato per ospitare l’intero sistema MCPD in configurazione “full‑stack”.

### 2.1 Struttura del laboratorio
- Hangar tecnico con schermatura elettromagnetica  
- Camera a vuoto parziale  
- Sistema di estrazione del plasma esausto  
- Zona di sicurezza per operatori

### 2.2 Configurazione dei moduli
I moduli MCPD sono installati in sequenza reale:

1. MPI – Magnetic Plasma Intake  
2. PCC – Plasma Confinement Chamber  
3. FHM – Fusion Heating Mechanisms  
4. PHA – RF Heating Assembly  
5. CPCS – Capacitive Pulse Compression System  
6. MNA – Magnetic Nozzle Assembly  
7. MSS – Magnetic Support System  
8. NRM – Nuclear Reactor Module (versione simulata)

### 2.3 Sorgente di plasma terrestre
Il banco prova utilizza una sorgente controllata di plasma (RF, arco, mini‑tokamak o sorgente ionica) con parametri regolabili:

- densità  
- temperatura  
- flusso  
- energia cinetica

Il plasma viene convogliato verso l’intake tramite linea dedicata.

---

## 3. Metodologia di Test

La metodologia di collaudo è progressiva, modulare e scalabile.

### 3.1 Principio generale
Il banco prova riproduce a terra le condizioni operative del MCPD, alimentando l’intake con plasma reale e osservando la risposta del sistema:

- cattura del plasma  
- confinamento  
- riscaldamento  
- compressione  
- accelerazione magnetica  
- stabilità dei campi

### 3.2 Fasi del test

#### Fase 1 – Attivazione dei moduli
Accensione completa del sistema MCPD e verifica della stabilità dei campi magnetici.

#### Fase 2 – Alimentazione dell’intake
La sorgente terrestre fornisce plasma reale all’MPI.  
Si misurano:
- efficienza di cattura  
- stabilità del confinamento  
- variazioni di temperatura

#### Fase 3 – Incremento progressivo del flusso
Il flusso di plasma viene aumentato gradualmente.  
Si osservano:
- risposta del PCC  
- compressione nel CPCS  
- velocità del plasma nel MNA  
- stabilità del MSS

Da questi dati si ricava la **spinta equivalente** del sistema.

---

## 4. Parametri Misurati e Criteri di Validazione

### 4.1 Profilo di spinta di riferimento
Il banco prova utilizza come riferimento il profilo di spinta del razzo nucleare che ospiterà il MCPD.  
Per ogni istante \( t \) si definiscono:

- spinta prevista \( T_{\text{nuc}}(t) \)  
- velocità prevista \( v_{\text{rocket}}(t) \)

### 4.2 Traduzione in flusso di plasma
Per ogni punto del profilo di velocità:

- si calcola la massa di plasma che l’intake intercetterebbe realmente  
- questo valore diventa il flusso da fornire al banco prova

Il banco prova alimenta l’intake con il plasma che il vettore “vedrebbe” avanzando nello spazio, in forma scalata.

### 4.3 Parametri misurati
Per ogni step:

- flusso di plasma in ingresso all’MPI  
- quota di plasma catturata  
- densità e temperatura nel PCC  
- compressione nel CPCS  
- velocità del plasma nel MNA  
- spinta equivalente:
  

\[
  T_{\text{eq}} = \dot{m}_{\text{acc}} \cdot v_{\text{exhaust}}
  \]


- impulso specifico equivalente:
  

\[
  I_{sp,\text{eq}} = \frac{T_{\text{eq}}}{\dot{m}_{\text{acc}} \cdot g_0}
  \]



### 4.4 Criteri di validazione
Il sistema è considerato validato se:

- la spinta equivalente segue il profilo \( T_{\text{nuc}}(t) \)  
- l’intake mantiene efficienza entro i limiti  
- il confinamento è stabile  
- la compressione è coerente con i modelli  
- la velocità del plasma accelerato è conforme alle previsioni  
- non emergono instabilità critiche

---

## 5. Legge di Incremento del Flusso di Plasma

Il flusso di plasma fornito all’intake segue una legge di proporzionalità diretta:

**Più spinta equivalente viene misurata all’ugello magnetico, maggiore è il flusso di plasma iniettato.**

Per ogni step:

1. Si misura la spinta equivalente \( T_{\text{eq}}(t) \)  
2. Si calcola il nuovo flusso:
   

\[
   \dot{m}_{\text{in}}(t+1) \propto T_{\text{eq}}(t)
   \]


3. Si alimenta l’intake con il nuovo flusso

Questo ciclo rende il banco prova auto‑coerente e rappresentativo del comportamento reale del vettore.

---

# Documento completato.
