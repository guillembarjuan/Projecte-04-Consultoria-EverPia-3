# 📁 Projecte 04 – EverPia 3: El desafiament final

Benvingut al quart i últim projecte de la trilogia **EverPia**. Després de setmanes convivint amb el ritme imprevisible d’una consultora tecnològica, arriba el moment de demostrar tot el que hem après. Ja no som els juniors que van entrar per la porta amb por i il·lusió: ara tenim eines, criteri, documentació pròpia i una manera de mirar els problemes que només es guanya treballant molt i en silenci.

> *“Aquesta intensitat et fa créixer. Aquesta pressió et defineix. Aquesta experiència accelerada et converteix en professional.”*

Aquest projecte és la nostra **carta de presentació professional**. Hem hagut de donar resposta a encàrrecs reals dins l’ecosistema d’EverPia: gestió d’emergències, backup i recuperació, implementació de serveis d’accés remot, desplegament de servidors NFS i CUPS, disseny d’un e-commerce amb Figma, i treball col·laboratiu amb GitHub mitjançant forks i pull requests.

---

## 📌 Índex

1. [Descripció del projecte](#-descripció-del-projecte)
2. [Metodologia de treball](#-metodologia-de-treball)
3. [Tasques realitzades](#-tasques-realitzades)
4. [Productes finals](#-productes-finals)
5. [Estructura del repositori](#-estructura-del-repositori)
6. [Tecnologies i eines](#-tecnologies-i-eines)
7. [Aprenentatges clau](#-aprenentatges-clau)
8. [Competències treballades](#-competències-treballades)
9. [Enllaços d’interès](#-enllaços-dinterès)
10. [Autor](#-autor)

---

## 📋 Descripció del projecte

**EverPia 3** és la culminació de la nostra experiència a la consultora. Ens enfrontem a reptes tècnics i organitzatius que integren tots els mòduls del curs: Seguretat Informàtica (0226), Serveis de Xarxa (0227), Sistemes Operatius en Xarxa (0224), Aplicacions Web (0228), Sostenibilitat (1708), Itinerari d’Ocupabilitat (1710) i Projecte Intermodular (1713).

El projecte s’estructura en quatre setmanes i ens posa en el rol de tècnics que han de:
- **Garantir la resiliència del sistema** mitjançant plans de còpies de seguretat (DRP) i imatges de recuperació.
- **Desplegar serveis corporatius** com NFS (servidor de fitxers), CUPS (servidor d’impressió) i accés remot (SSH, RDP, eines d’assistència).
- **Treballar col·laborativament** amb GitHub utilitzant forks, branques i pull requests.
- **Dissenyar un prototip d’e-commerce** complet (Landing Page + Checkout) amb Figma i presentar-lo professionalment al client.
- **Reflexionar sobre sostenibilitat** aplicant criteris d’economia circular al sector TIC.

---

## 🧭 Metodologia de treball

Tot el projecte s’ha gestionat amb la metodologia **Kanban** mitjançant **Microsoft Planner**, amb columnes: *Backlog, Per fer, En curs, En revisió, Fet*. Cada setmana es fa una revisió de l’estat del tauler per part del professorat.

🔗 **Enllaç al tauler Kanban del projecte (P03):**  
[https://planner.cloud.microsoft/webui/v1/plan/AHhl8IcsL0eMlXGDYdz3bpYACCHz](https://planner.cloud.microsoft/webui/v1/plan/AHhl8IcsL0eMlXGDYdz3bpYACCHz?tid=c7b5981a-7820-4ac8-ae65-03515ea81317)

---

## ✅ Tasques realitzades

A continuació es mostren les principals tasques desenvolupades, extretes del document d’instruccions:

| ID | Tasca | Descripció | Tipus |
|----|-------|-------------|-------|
| T00 | Presentació del projecte i creació del Kanban i el repositori | Creació del Planner i repositori GitHub inicial. | Grup |
| T01 | DRP: còpies de seguretat. Estudi cas client | Anàlisi d’un cas real (Muntatges i Serveis Tècnics SL) i definició d’una política de còpies (regla 3-2-1). | Cooperatiu (1-2-4) |
| T02 | DRP: còpies de seguretat. Cas pràctic | Implementació de còpies amb Duplicati (Windows) i Duplicity + cron (Linux). | Individual |
| T03 | Pla de recuperació davant desastres: imatges del sistema | Comparativa d’eines (comercials vs comunitat) i creació/restauració d’imatges amb Rescuezilla. | Individual |
| T04 | Accés remot (teoria) | Introducció als mètodes d’accés remot (SSH, RDP, assistència). Prova de validació. | Grup |
| T05 | Accés remot. Connexió via SSH | Guia d’ús de SSH des de Linux i Windows, generació de claus públiques/privades. | Individual |
| T06 | Accés remot. Escriptori remot (RDP) | Configuració de RDP a Windows i Zorin OS, connexió entre diferents SO. | Individual |
| T07 | Accés remot. Serveis d’assistència remota | Anàlisi comparativa de TeamViewer, AnyDesk, Google Remote Desktop i RustDesk. Creació de guies per a tècnic i client. | Parelles |
| T08 | Auditoria de Qualitat i Estandardització de Servidors (SOP) | Pràctica de configuració estàndard d’Ubuntu Server (xarxa, actualitzacions, permisos) i prova pràctica. | Individual |
| T09 | Servidor fitxers Linux. NFS | Configuració d’un servidor NFSv3 i un client Linux. Control d’accés mitjançant exports i permisos. | Individual |
| T10 | Servidor impressió Linux. CUPS | Instal·lació de CUPS, impressora virtual cups-pdf, configuració web i proves des de client Zorin. | Individual |
| T11 | Introducció a Figma | Aprenentatge de les eines bàsiques de Figma per al disseny d’interfícies. | Individual |
| T12 | Fonaments del Disseny Web Comercial | Classes magistrals sobre Landing Page i procés de Checkout. | Grup |
| T13 | Disseny d’un E-commerce en Figma | Creació d’un prototip navegable complet (Landing Page + Checkout) per a un producte assignat. | Parelles |
| T14 | Sostenibilitat. Prova escrita | Examen de conceptes de sostenibilitat i ODS. | Individual |
| T15 | Com de circular és la meva família professional? | Reflexió sobre l’economia circular aplicada al sector informàtic. | Individual |
| T16 | Crea el teu pla d’empresa TECH | Estudi de mercat, segmentació, màrqueting mix, i vídeo final (projecte emprenedor). | Grup |

---

## 🏁 Productes finals

Els productes avaluables del projecte són quatre. Cada un està documentat dins la seva carpeta corresponent al repositori.

| Codi | Nom del producte | Enllaç a la carpeta |
|------|------------------|---------------------|
| **P01** | GitHub. Treballant de forma col·laborativa: forks i pull request | [`Producte01`](./Producte01) |
| **P02** | Presentació i Projecció de la Maqueta web al Client | [`Producte02`](./Producte02) |
| **P03** | Kanban del projecte | [`Producte03`](./Producte03) |
| **P04** | Fitxes d’Economia Circular | [`Producte04`](./Producte04) |

> **Nota:** Les carpetes `Producte01` a `Producte04` contenen els seus respectius README.md amb la descripció detallada i evidències.

---

## 📁 Estructura del repositori

El repositori està organitzat de la següent manera (segons la imatge proporcionada):

```
Projecte-04-Consultoria-EverPia-3/
│
├── README.md                    # Aquest fitxer
│
├── Producte01/                  # P01 – Forks i pull requests
├── Producte02/                  # P02 – Presentació maqueta Figma
├── Producte03/                  # P03 – Kanban del projecte
├── Producte04/                  # P04 – Fitxes d’Economia Circular
│
├── tasca01/                     # DRP estudi cas client (política 3-2-1)
├── tasca02/                     # DRP pràctic (Duplicati, Duplicity, cron)
├── tasca03/                     # Imatges del sistema (Rescuezilla)
├── tasca04/                     # Accés remot (teoria)
├── tasca05/                     # SSH
├── tasca06/                     # RDP
├── tasca07/                     # Assistència remota (comparativa i guies)
├── tasca08/                     # Auditoria i estandardització (SOP)
├── tasca09/                     # NFS
├── tasca10/                     # CUPS
├── tasca11/                     # Figma bàsic
├── tasca12/                     # Fonaments Landing + Checkout
├── tasca13/                     # E-commerce en Figma
├── tasca14/                     # Sostenibilitat (prova escrita)
├── tasca15/                     # Economia circular
└── tasca16/                     # Pla d’empresa TECH (dossier + vídeo)
```

Tota la documentació tècnica està redactada en **Markdown**, amb imatges a subcarpetes `img` i text alternatiu per a l’accessibilitat.

---

## 🛠️ Tecnologies i eines utilitzades

- **Metodologia àgil:** Kanban amb Microsoft Planner.
- **Control de versions:** Git i GitHub (forks, pull requests, branques).
- **Backup i recuperació:** Duplicati (Windows), Duplicity + cron (Linux), Rescuezilla (imatges de sistema).
- **Accés remot:** SSH (clau pública/privada), RDP (Windows i Zorin), TeamViewer, AnyDesk, Google Remote Desktop, RustDesk.
- **Servidors Linux:** NFS (Network File System), CUPS (impressió), configuració estàndard (SOP).
- **Disseny i prototipat:** Figma (landing page, checkout, prototip navegable).
- **Sostenibilitat:** Economia circular, ODS, criteris ASG.
- **Emprenedoria:** Estudi de mercat, segmentació, màrqueting mix, vídeo promocional.

---

## 💡 Aprenentatges clau

- **Dominar el flux de treball professional de GitHub:** fer un fork d’un repositori central, crear una branca, obrir una pull request i fer-ne la revisió com a Team Leader. Aquesta habilitat és essencial en entorns col·laboratius.
- **Implementar un pla de còpies de seguretat (DRP):** dissenyar una política 3-2-1, utilitzar Duplicati per a còpies al núvol (Google Drive) i Duplicity amb cron per a servidors Linux.
- **Crear i restaurar imatges de sistema amb Rescuezilla:** comparativa d’eines comercials i de comunitat, i elaboració d’una guia tècnica per a la restauració ràpida de servidors.
- **Configurar serveis d’accés remot segurs:** SSH (amb clau pública/privada) i RDP (des de Windows i Linux). Avaluar eines d’assistència remota i crear guies per a tècnics i clients.
- **Desplegar un servidor NFS i un servidor CUPS:** compartir directoris i impressores en xarxa, controlar permisos amb `/etc/exports` i la interfície web de CUPS.
- **Dissenyar un prototip d’e-commerce professional amb Figma:** construir una landing page completa (capçalera, hero, productes, testimonis, peu) i un procés de checkout navegable (cistella, adreça, pagament, confirmació). Incorporar bones pràctiques d’UX i usabilitat.
- **Presentar el prototip davant del client:** justificar decisions de disseny, explicar el procés de compra i respondre preguntes amb professionalitat.
- **Aplicar l’economia circular al sector TIC:** reflexionar sobre la circularitat de la família professional d’informàtica i proposar accions concretes.

---

## 🧰 Competències treballades

- **DRP i còpies de seguretat:** seleccionar estratègies de còpia, realitzar còpies de seguretat amb diferents eines i mitjans, crear i restaurar imatges de sistema.
- **Accés remot:** instal·lar i configurar serveis SSH i RDP, utilitzar eines d’assistència remota, i documentar procediments per a tècnics i clients.
- **Serveis compartits:** configurar servidors NFS (fitxers) i CUPS (impressió), controlar permisos i nivells de seguretat.
- **Estandardització de servidors:** aplicar un protocol de configuració bàsica (SOP) en Ubuntu Server (xarxa, actualitzacions, usuaris, permisos).
- **Disseny web i UX:** crear prototips navegables amb Figma, justificar decisions de disseny, presentar solucions comercials.
- **Treball col·laboratiu amb Git:** fer forks, branques, pull requests i revisions de codi.
- **Sostenibilitat i economia circular:** identificar aspectes ASG, proposar accions per a un model de negoci circular.
- **Emprenedoria:** realitzar un estudi de mercat, segmentar, definir màrqueting mix i comunicar el projecte en vídeo.

---

## 🔗 Enllaços d’interès

- 👤 **Perfil de GitHub:** [github.com/guillembarjuan](https://github.com/guillembarjuan)
- 📌 **Tauler Kanban (Planner) – P03:** [Accedir al Planner del Projecte 04](https://planner.cloud.microsoft/webui/v1/plan/AHhl8IcsL0eMlXGDYdz3bpYACCHz?tid=c7b5981a-7820-4ac8-ae65-03515ea81317)
- 🧩 **Repositori base per al P01 (EverPia-Onboarding):** [https://github.com/SMX2n/EverPia-Onboarding](https://github.com/SMX2n/EverPia-Onboarding)
- 📘 **Guia de l’activitat P01:** [https://github.com/SMX2n/Projecte04-GuiaGitHub](https://github.com/SMX2n/Projecte04-GuiaGitHub)
- 🎨 **Prototip Figma (P02) – Game Station:** [Enllaç al prototip](https://www.figma.com/proto/aS74YmYB73ZMFtaqKFW1fU/Game-Station?node-id=1-2&p=f&t=mtvFoJ5SeLSZFvOO-1&scaling=min-zoom&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=1%3A2)
- 📂 **Carpeta P01 (GitHub col·laboratiu):** [`./Producte01`](./Producte01)
- 📂 **Carpeta P02 (Presentació Figma):** [`./Producte02`](./Producte02)
- 📂 **Carpeta P03 (Kanban):** [`./Producte03`](./Producte03)
- 📂 **Carpeta P04 (Economia circular):** [`./Producte04`](./Producte04)

---

## 👤 Autor

**Guillem Barjuan Alonso** – CFGM SMX  
Curs 2025-2026

---

*Aquest projecte demostra que després de tres projectes intensos a EverPia, hem passat de ser aprenents a professionals capaços de gestionar emergències, desplegar serveis, dissenyar solucions digitals i treballar en equip amb eines de codi. Som els herois anònims del backend, i aquesta carpeta professional és la prova del nostre valor.*
