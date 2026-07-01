<!-- ========================= -->
<!--   MCPD – TWITTER CARD     -->
<!-- ========================= -->
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="MCPD – Magnetically Captured Plasma Drive">
<meta name="twitter:description" content="Progetto di propulsione nucleare-plasmatica ideato da Salvatore Esposito Faraone.">
<meta name="twitter:image" content="https://esfasal561.github.io/MCPD/assets/img/mcpd-cover.png">

<!-- ========================= -->
<!--   MCPD – BANNER ANIMATO   -->
<!-- ========================= -->
<div style="
  width:100%;
  padding:40px 0 32px 0;
  background:
    radial-gradient(circle at 15% 20%, rgba(0,180,255,0.25), transparent 55%),
    radial-gradient(circle at 85% 30%, rgba(255,80,0,0.25), transparent 55%),
    radial-gradient(circle at 50% 80%, rgba(0,255,160,0.18), transparent 55%),
    linear-gradient(120deg, #05070a, #0d0d10, #05070a);
  background-size: 200% 200%;
  animation: plasmaFlow 12s ease-in-out infinite;
  text-align:center;
  border-radius:14px;
  margin-bottom:28px;
  box-shadow:0 0 26px rgba(0,0,0,0.55);
  position:relative;
  overflow:hidden;
">

  <!-- MSS -->
  <div style="
    position:absolute;
    inset:0;
    background-image: repeating-linear-gradient(
      90deg,
      rgba(0,255,120,0.08) 0px,
      rgba(0,255,120,0.08) 2px,
      transparent 6px,
      transparent 12px
    );
    mix-blend-mode:screen;
    opacity:0.5;
    animation: mssOscillation 14s ease-in-out infinite;
  "></div>

  <!-- PCC + MNA -->
  <div style="
    position:absolute;
    inset:0;
    background-image: repeating-linear-gradient(
      115deg,
      rgba(0,255,200,0.08) 0px,
      rgba(0,255,200,0.08) 1px,
      transparent 3px,
      transparent 7px
    );
    mix-blend-mode:screen;
    opacity:0.7;
    animation: fieldLines 18s linear infinite;
  "></div>

  <!-- PHA -->
  <div style="
    position:absolute;
    inset:0;
    background-image:
      radial-gradient(circle at 0% 50%, rgba(0,140,255,0.18), transparent 55%),
      radial-gradient(circle at 100% 50%, rgba(0,140,255,0.18), transparent 55%);
    opacity:0.55;
    animation: rfWaves 9s ease-in-out infinite;
  "></div>

  <!-- CPCS -->
  <div style="
    position:absolute;
    left:50%;
    top:50%;
    width:220px;
    height:220px;
    transform:translate(-50%, -50%);
    border-radius:50%;
    background: radial-gradient(circle, rgba(255,255,255,0.22) 0%, transparent 60%);
    opacity:0;
    animation: compressionFlash 7s ease-out infinite;
  "></div>

  <!-- PCC -->
  <div style="
    position:absolute;
    left:50%;
    top:50%;
    width:320px;
    height:320px;
    transform:translate(-50%, -50%);
    border-radius:50%;
    border:1px solid rgba(0,255,200,0.35);
    box-shadow:
      0 0 32px rgba(0,255,200,0.35),
      inset 0 0 22px rgba(0,255,200,0.25);
    opacity:0.9;
    animation: torusPulse 11s ease-in-out infinite;
  "></div>

  <div style="position:relative; z-index:2;">
    <h1 style="color:#e6e6e6; font-family:Consolas, monospace; font-size:30px; margin:0;">
      MCPD – Magnetically Captured Plasma Drive
    </h1>
    <p style="color:#bfbfbf; font-family:Consolas, monospace; font-size:16px; margin-top:10px;">
      MPI · PCC · PHA · CPCS · MNA · MSS — Hybrid Nuclear–Plasma Propulsion Concept
    </p>
  </div>
</div>

<style>
@keyframes plasmaFlow { 0%{background-position:0% 50%;} 50%{background-position:100% 50%;} 100%{background-position:0% 50%;} }
@keyframes fieldLines { 0%{transform:translateX(0px);} 100%{transform:translateX(-40px);} }
@keyframes rfWaves { 0%{opacity:0.25;transform:scale(1);} 50%{opacity:0.7;transform:scale(1.05);} 100%{opacity:0.25;transform:scale(1);} }
@keyframes compressionFlash { 0%{opacity:0;transform:translate(-50%,-50%) scale(0.6);} 40%{opacity:0.55;transform:translate(-50%,-50%) scale(1);} 100%{opacity:0;transform:translate(-50%,-50%) scale(1.2);} }
@keyframes torusPulse { 0%{transform:translate(-50%,-50%) scale(0.95);opacity:0.8;} 50%{transform:translate(-50%,-50%) scale(1.05);opacity:1;} 100%{transform:translate(-50%,-50%) scale(0.95);opacity:0.8;} }
@keyframes mssOscillation { 0%{opacity:0.25;} 50%{opacity:0.55;} 100%{opacity:0.25;} }
</style>

---

# MCPD – Magnetically Captured Plasma Drive
### Hybrid Nuclear–Plasma Propulsion Concept

---

Il **Magnetically Captured Plasma Drive (MCPD)** è un concetto di propulsione nucleare–plasma sviluppato da **Salvatore Esposito Faraone**, basato sulla cattura, stabilizzazione, riscaldamento e compressione del plasma tramite sistemi magnetici avanzati.

---

<div style="text-align:center; margin-top:30px;">
  <img src="https://esfasal561.github.io/MCPD/assets/img/mcpd-cover.png" alt="MCPD Cover" style="max-width:85%; border-radius:12px; box-shadow:0 0 22px rgba(0,0,0,0.45);">
</div>

---

<div style="text-align:center; margin-top:40px;">
  <img src="assets/img/mcpd-poster-7stage.png" alt="MCPD Poster – 7 Stage Nuclear Integration" style="max-width:100%; border-radius:12px; box-shadow:0 0 28px rgba(0,0,0,0.55);">
</div>


---

<div style="text-align:center; margin-top:40px;">
  <img src="assets/img/mcpd-vettore-doppio-8k.png" alt="Blueprint Vettore Interplanetario Doppio MCPD" style="max-width:100%; border-radius:12px; box-shadow:0 0 28px rgba(0,0,0,0.55);">
</div>

---

<div style="text-align:center; margin-top:40px;">
  <img src="assets/img/Copilot_20260629_191145.png" alt="Vista Esplosa 3D Moduli MCPD" style="max-width:100%; border-radius:12px; box-shadow:0 0 28px rgba(0,0,0,0.55);">
</div>

---

# MCPD – Technical Whitepaper

## 1. Executive Summary
- Obiettivo del MCPD
- Visione generale del sistema a 7 stadi
- Applicazioni: propulsione interplanetaria, deep‑space, cargo orbitale
- Vantaggi rispetto a MPD, VASIMR, Hall thrusters

## 2. Architettura del Motore
### 2.1 Panoramica dei 7 stadi
- MPI – Magnetic Plasma Intake
- PCC – Plasma Confinement Chamber
- FHM – Fusion Heating Mechanisms (ciclotrone lineare)
- NRM – Nuclear Reactor Module
- PHA – RF Heating Assembly
- CPCS – Capacitive Pulse Compression System
- MNA – Magnetic Nozzle Assembly
- MSS – Magnetic Support Structure

### 2.2 Flusso del plasma
- Percorso energetico dal prelievo alla spinta
- Interazione sequenziale dei moduli

## 3. Fisica del Plasma
### 3.1 Parametri fondamentali
- densità
- temperatura
- beta del plasma
- lunghezza di Debye
- frequenze caratteristiche

### 3.2 Confinamento magnetico nel PCC
- geometria delle bobine
- stabilità MHD
- criteri di confinamento

### 3.3 Interazione plasma–campo nel FHM
- moto ciclotronico
- spirale lineare
- assorbimento RF

## 4. Ciclotrone Lineare (FHM)
### 4.1 Principio di funzionamento
- risonanza ciclotronica
- armoniche
- accelerazione ionica

### 4.2 Costruzione fisica
- canale del plasma
- bobine magnetiche
- cavità RF
- schermature
- raffreddamento

### 4.3 Frequenze operative (B = 5 T)
- elettroni: 140–700 GHz
- protoni: 76–380 MHz
- deuterio: 38–190 MHz

### 4.4 Sequenza modulare FHM‑A / FHM‑B / FHM‑C
- pre‑ionizzazione
- accelerazione ciclotronica
- stabilizzazione energetica

## 5. Modulo Nucleare (NRM)
### 5.1 Concetto del mini‑reattore
- ruolo energetico
- sicurezza
- schermature

### 5.2 Interfaccia plasma–reattore
- flusso termico
- gestione radiazioni
- materiali avanzati

## 6. Riscaldamento RF (PHA)
### 6.1 ECRH (Electrons)
- 140–700 GHz
- cavità millimetriche

### 6.2 ICRH (Ions)
- 38–380 MHz
- antenne a guida d’onda

### 6.3 Accoppiamento RF–plasma
- efficienza
- modulazione di fase
- armoniche superiori

## 7. Compressione Impulsiva (CPCS)
### 7.1 Capacitive Pulse Compression
- principio
- sequenza di scarica
- aumento densità energetica

### 7.2 Integrazione con PHA
- sincronizzazione
- controllo temporale

## 8. Ugello Magnetico (MNA)
### 8.1 Geometria del campo
- divergenza controllata
- accelerazione finale

### 8.2 Efficienza di spinta
- Isp teorico
- Isp operativo
- confronto con MPD e VASIMR

## 9. Materiali e Struttura
### 9.1 Materiali ad alta temperatura
- ceramiche
- carburi
- superleghe

### 9.2 Schermature
- termiche
- magnetiche
- radiative

### 9.3 Raffreddamento
- liquido
- gas
- radiazione

## 10. Controllo e Diagnostica
### 10.1 Sensori
- densità
- temperatura
- campo magnetico
- RF

### 10.2 Sistema di controllo
- modulazione RF
- controllo del campo
- stabilità del plasma

## 11. Simulazioni e Modellistica
### 11.1 MHD
### 11.2 PIC (Particle‑In‑Cell)
### 11.3 CFD termica
### 11.4 Modelli di spinta

## 12. Roadmap di Sviluppo
### 12.1 Team necessario
- fisici dei plasmi
- fisici nucleari
- ingegneri RF
- ingegneri termici
- ingegneri strutturali

### 12.2 Fasi
- Fase 1: modellistica
- Fase 2: prototipi dei moduli
- Fase 3: integrazione
- Fase 4: test in vuoto
- Fase 5: validazione orbitale

## 13. Appendici
- formule
- parametri
- schemi
- glossario tecnico

---

# 🚀 Navigazione MCPD

### 🔷 Moduli del Sistema Propulsivo
- [Overview del Sistema](PROJECT_OVERVIEW.md)
- [Magnetic Plasma Intake (MPI)](MPI_module.md)
- [Plasma Confinement Chamber (PCC)](pcc_Magnetic-confinement.md)
- [RF Heating Assembly (PHA)](PHA_RF-Heathing.md)
- [Capacitive Pulse Compression System (CPCS)](CPCS_pulse-compression.md)
- [Magnetic Nozzle Assembly (MNA)](MNA_magnetic-nozzle.md)
- [Magnetic Support System (MSS)](MSS_module.md)
- [Nuclear Reactor Module (NRM)](NRM.html)

---

<div style="border:1px solid #555;padding:12px;margin:12px 0;background:#0b0b0b;color:#e0e0e0;">
  <h3 style="margin-top:0;">Nuclear Reactor Module (NRM)</h3>
  <p>
    Il <strong>Nuclear Reactor Module (NRM)</strong> è la sorgente energetica primaria del MCPD.
    Alimenta tutti i moduli magnetici, il PHA (CRT + ECRH/ICRH) e il CPCS, rendendo possibile
    il funzionamento dell’intera pipeline propulsiva.
  </p>
  <p style="margin-bottom:0;">
    <a href="NRM.html" style="color:#7fd1ff;">
      ➜ Apri la pagina dedicata al Nuclear Reactor Module
    </a>
  </p>
</div>

---

# 📘 Documentazione Principale
- [Project Overview](PROJECT_OVERVIEW.md)
- [White Paper v2.0](WHITEPAPER_MCPD_v2.md)
- [Scientific Abstract](SCIENTIFIC_ABSTRACT_MCPD.md)
- [Executive Summary](EXECUTIVE_SUMMARY.md)

---

# 🧩 Architettura del Sistema
- [System Architecture Diagram](MCPD_ARCHITECTURE_DIAGRAM.md)
- [Propulsion & Energy Modules Index](INDEX_PROPULSION_MODULES.md)
- [Plasma Dynamics & Exhaust Nozzle](PLASMA_DYNAMICS_EXHAUST_NOZZLE.md)
- [Nuclear Reactor Module (NRM)](NRM.html)

---

# 🔬 Fondamenti Scientifici
- [Nuclear–Plasma Hybrid Model](NUCLEAR_PLASMA_MODEL.md)
- [Magnetic Field Topology](MAGNETIC_FIELD_TOPOLOGY.md)
- [Fusion Heating Methods](FUSION_HEATING.md)

---

# 🧭 Roadmap & Sviluppo
- [Roadmap MCPD](ROADMAP_MCPD.md)
- [Milestones Tecniche](MILESTONES.md)
- [Future Research Directions](FUTURE_RESEARCH.md)

---

## English Documentation
- [MCPD vs Nuclear Fusion Propulsion](MCPD_vs_Fusion_EN.md)
- [Comparative Diagram](MCPD_Comparative_Diagram_EN.md)

---

<div style="text-align:center; margin-top:40px; font-size:14px; color:#666;">

  
  © 2026 — Progetto MCPD · Salvatore Esposito Faraone
</div>
