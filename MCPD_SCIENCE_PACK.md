# MCPD – Science Pack  
## Modello Scientifico, PCC Aggiornato e Diagramma Energetico del Pinch  
### Autore: Salvatore Esposito Faraone

---

# 1. Plasma Confinement Core (PCC) – Versione Scientifica

Il Plasma Confinement Core (PCC) è il modulo responsabile del confinamento magnetico del plasma catturato dal MPI.  
Opera come un tokamak lineare, ottimizzato per:

- stabilizzare il flusso  
- aumentare la densità  
- ridurre instabilità MHD  
- preparare il plasma per il riscaldamento RF

Il PCC è il punto in cui il plasma raccolto (che cresce proporzionalmente alla velocità del vettore) viene trasformato in un flusso stabile e ad alta densità.

## 1.1 Relazione con il Principio Fondativo MCPD

Il PCC non genera plasma:  
**trasforma il plasma raccolto dal MPI in un flusso confinato ad alta densità.**

La densità del plasma nel PCC è:



\[
n_{PCC} = k \cdot \dot{m}
\]



dove:

- \(k\) = coefficiente di confinamento magnetico  
- \(\dot{m}\) = massa di plasma raccolta dal MPI  

Poiché:



\[
\dot{m} \propto v
\]



allora:



\[
n_{PCC} \propto v
\]



Il PCC diventa quindi più efficiente man mano che il veicolo accelera.

---

# 2. MCPD Scientific Model  
## Modello matematico del flusso, della densità e della spinta

Il MCPD è governato da tre relazioni fondamentali:

---

## 2.1 Raccolta del plasma (MPI)



\[
\dot{m} = \rho \cdot A \cdot v
\]



---

## 2.2 Densità del plasma nel PCC



\[
n_{PCC} = k \cdot \dot{m}
\]



---

## 2.3 Energia del plasma riscaldato (PHA)



\[
E_{PHA} = n_{PCC} \cdot T_{RF}
\]



dove:

- \(T_{RF}\) = temperatura ottenuta tramite riscaldamento RF/ICRH

---

## 2.4 Compressione magnetica (CPCS – Theta Pinch)

La compressione magnetica aumenta la densità del plasma:



\[
n_{CPCS} = n_{PCC} \cdot C_{\theta}
\]



dove:

- \(C_{\theta}\) = coefficiente di compressione del pinch

---

## 2.5 Spinta generata dal MNA

La spinta del MCPD è:



\[
F = \dot{m} \cdot v_{exhaust}
\]



dove:

- \(v_{exhaust}\) = velocità del plasma espulso dall’ugello magnetico

Poiché:



\[
\dot{m} \propto v
\]



allora:



\[
F \propto v
\]



Il MCPD è quindi un motore a **spinta crescente con la velocità**.

---

# 3. Diagramma Energetico del Pinch (CPCS)

Il CPCS è il modulo che trasforma il plasma riscaldato in impulsi di spinta.

Di seguito il diagramma energetico ASCII:

```
                Plasma dal PHA (alta temperatura)
                               │
                               ▼
                ┌──────────────────────────────┐
                │  CPCS – Theta Pinch          │
                │  Compressione Magnetica       │
                └──────────────┬──────────────┘
                               │
                               ▼
                Energia del plasma:
                E_total = E_thermal + E_magnetic

                Densità compressa:
                n_CPCS = n_PCC · C_θ

                Temperatura aumentata:
                T_CPCS = T_RF · G_θ

                Dove:
                C_θ = coefficiente di compressione
                G_θ = coefficiente di guadagno termico
                               │
                               ▼
                ┌──────────────────────────────┐
                │  MNA – Magnetic Nozzle       │
                │  Conversione in Spinta       │
                └──────────────┬──────────────┘
                               ▼
                         Plasma Exhaust
```

---

# 4. Sintesi del Modello Scientifico

Il MCPD è governato da una catena di relazioni fisiche:

1. **Raccolta proporzionale alla velocità**  
   \(\dot{m} \propto v\)

2. **Confinamento proporzionale alla raccolta**  
   \(n_{PCC} \propto \dot{m}\)

3. **Energia proporzionale alla densità**  
   \(E_{PHA} \propto n_{PCC}\)

4. **Compressione proporzionale alla densità**  
   \(n_{CPCS} \propto n_{PCC}\)

5. **Spinta proporzionale alla massa raccolta**  
   \(F \propto \dot{m}\)

Da cui deriva la dinamica fondamentale:



\[
v \uparrow \Rightarrow \dot{m} \uparrow \Rightarrow n_{PCC} \uparrow \Rightarrow n_{CPCS} \uparrow \Rightarrow F \uparrow \Rightarrow v \uparrow
\]



Un ciclo di accelerazione auto‑rinforzante.

---

# Firma

**Autore: Salvatore Esposito Faraone**  
Stalettì (CZ), Italia — 28 giugno 2026
