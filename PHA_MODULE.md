# PHA – RF Heating Assembly (ECRH/ICRH)
## Plasma Heating Assembly del MCPD

Il Plasma Heating Assembly (PHA) è il modulo che riscalda il plasma confinato nel PCC tramite tecniche RF ad alta efficienza (ECRH per gli elettroni, ICRH per gli ioni).  
Il suo compito è portare il plasma a un regime energetico utile per la compressione magnetica nel CPCS.

---

## 1. Relazione con il Principio Fondativo MCPD

Poiché la massa di plasma raccolta dal MPI aumenta proporzionalmente alla velocità del vettore:



\[
\dot{m} \propto v
\]



e poiché la densità del plasma nel PCC è proporzionale alla massa raccolta:



\[
n_{PCC} \propto \dot{m}
\]



l’energia termica generata dal PHA è:



\[
E_{PHA} = n_{PCC} \cdot T_{RF}
\]



Da cui deriva:



\[
E_{PHA} \propto v
\]



Il PHA diventa quindi **più efficace man mano che il veicolo accelera**, perché riscalda una quantità maggiore di plasma.

---

## 2. Architettura

- Antenne RF direzionali  
- GeneratorI ad alta frequenza  
- Guide d’onda  
- Sistema di controllo della fase  
- Sensori di temperatura del plasma  

---

## 3. Funzionamento passo per passo

1. Le antenne emettono onde RF.  
2. Gli elettroni assorbono energia (ECRH).  
3. Gli ioni assorbono energia (ICRH).  
4. La temperatura sale a decine/centinaia di eV.  
5. La distribuzione energetica si uniforma.  
6. Il plasma caldo viene inviato al CPCS.

---

## 4. Motivazione tecnica

- Il plasma catturato è troppo freddo.  
- Serve portarlo a un regime energetico utile.  
- Il pinch richiede plasma già caldo e denso.

---

## 5. Integrazione nel sistema MCPD

PCC → PHA → CPCS

Il PHA è il ponte energetico tra il confinamento (PCC) e la compressione (CPCS):  
trasforma il plasma da “confinato” a “energeticamente attivo”, in modo coerente con il principio fondativo MCPD.
