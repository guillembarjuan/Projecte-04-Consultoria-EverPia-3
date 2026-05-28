# P01 – GitHub. Treballant de forma col·laborativa: forks i pull request

## 📌 Descripció del producte

Aquest producte consisteix a **simular el flux de treball professional de Git i GitHub** que s’utilitza a EverPia per a la col·laboració en equip. Fins ara havíem treballat de manera individual; ara aprenem a coordinar-nos com ho fem a la consultora real: amb forks, branques, pull requests i revisions de codi.

L’activitat reprodueix el procés d’**Onboarding** (incorporació) de nous consultors a EverPia. Es parteix d’un repositori central de l’empresa (`EverPia-Onboarding`) i cada membre de l’equip n’ha de fer un *fork*, crear una nova branca, afegir la seva fitxa personal i obrir una *pull request* perquè el **Team Leader** (líder d’equip) la revisi i l’integri.

Aquest és un dels fluxos de treball més utilitzats al sector tecnològic i una habilitat clau per a qualsevol professional IT.

---

## 🎯 Objectius específics

- Dominar el flux de treball col·laboratiu de GitHub: **fork**, **branca**, **commit**, **pull request** i **merge**.
- Simular la jerarquia d’un equip professional (Team Leader i membres).
- Aprendre a fer **revisions de codi** i a gestionar pull requests.
- Centralitzar la documentació de l’equip en un repositori compartit.
- Utilitzar el `README.md` per presentar la feina de cada membre.

---

## 👥 Rols dins l’equip

Per a aquesta activitat, cada grup ha designat:

- **Team Leader (Líder d’Equip):** responsable de revisar i aprovar les pull requests, així com de mantenir el repositori central actualitzat.
- **Membres de l’Equip:** cada membre fa un fork del repositori central, crea la seva branca, afegeix la seva fitxa personal i obre una pull request.

El meu rol va ser de **membre de l’equip** (o Team Leader, segons correspongui – ajusta-ho si cal).

---

## 🔧 Flux de treball seguit

### 1. Repositori base

L’empresa EverPia proporciona un repositori base amb l’estructura inicial:

🔗 [Repositori base: EverPia-Onboarding](https://github.com/SMX2n/EverPia-Onboarding)

### 2. Fork del repositori

Cada membre de l’equip (inclòs jo) va crear una **còpia personal (fork)** del repositori al seu compte de GitHub.

### 3. Clonació local i creació de branca

Es va clonar el fork a l’ordinador local i es va crear una nova branca amb el nom de l’usuari o la tasca a realitzar.

### 4. Afegir la fitxa personal

Dins la carpeta corresponent (per exemple `team-members/`), cada membre va crear un arxiu en Markdown amb el seu nom, rol a EverPia, habilitats i contacte.

### 5. Commit i push

Es van pujar els canvis a la branca del fork (no a `main`).

### 6. Obrir una Pull Request (PR)

Des de GitHub, cada membre va obrir una **pull request** dirigida a la branca `main` del repositori central (`EverPia-Onboarding`).

### 7. Revisió i merge (Team Leader)

El Team Leader va revisar cada PR, va comprovar que el contingut fos correcte i va procedir a **fusionar-la (merge)** al repositori central. En cas d’incidències, es van sol·licitar canvis.

### 8. Actualització del fork local

Un cop aprovada la PR, cada membre va sincronitzar el seu fork amb el repositori central per tenir la versió més actualitzada.

---

## 📁 Contingut lliurat

- **Fork personal** del repositori `EverPia-Onboarding` al meu compte de GitHub.
- **Fitxa personal** en Markdown dins de la carpeta `team-members/`.
- **Pull request** oberta, revisada i aprovada (captura de pantalla o enllaç a la PR tancada).
- **Repositori central actualitzat** amb les fitxes de tots els membres de l’equip.

---

## 🔗 Enllaços d’interès

- 📌 **Repositori base (EverPia-Core):** [https://github.com/SMX2n/EverPia-Onboarding](https://github.com/SMX2n/EverPia-Onboarding)
- 📘 **Guia de l’activitat:** [https://github.com/SMX2n/Projecte04-GuiaGitHub](https://github.com/SMX2n/Projecte04-GuiaGitHub)
- 👤 **El meu fork personal:** (afegeix aquí l’enllaç al teu fork, per exemple: `https://github.com/guillembarjuan/EverPia-Onboarding`)
- 🔁 **Pull request creada:** (afegeix enllaç a la PR si està disponible)

---

## 💡 Aprenentatges clau

- **Diferència entre fork i branca:** el fork és una còpia sencera del repositori al teu compte; la branca és una línia de desenvolupament dins d’un mateix repositori.
- **Flux professional:** mai es treballa directament sobre `main` en un entorn col·laboratiu. Es fan servir branques i pull requests.
- **Revisió de codi (Code Review):** el Team Leader pot comentar línies concretes, demanar canvis o aprovar la PR. Això millora la qualitat i evita errors.
- **Sincronització:** després d’una PR aprovada, cal actualitzar el fork local per no treballar amb una versió desactualitzada.
- **Comunicació en equip:** les pull requests inclouen descripcions, comentaris i etiquetes, que faciliten la coordinació.

---

## 👤 Autor

**Guillem Barjuan Alonso** – CFGM SMX  
Projecte 04 – Consultoria EverPia 3  
Data de realització: segon trimestre del curs 2025-2026

---

*Aquest producte demostra que la tecnologia no només és servidors i xarxes: la veritable potència s’assoleix quan sabem treballar en equip utilitzant les eines de col·laboració que ofereix GitHub. A EverPia, cada pull request és una oportunitat per aprendre junts.*
