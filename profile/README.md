<div align="center">

<img src="assets/gem_ico.png" alt="GEMMEO" width="110" />

# GEMMEO

**Écosystème d'applications métier pour le conseil comptable, social et fiscal.**

Calcul des cotisations, simulations financières, optimisation,
administration des licences et des utilisateurs — le tout sur une stack
technique unifiée.

</div>

---

## Applications métier

<table>
  <tr>
    <td width="64" align="center"><img src="assets/gemmsa_ico.png" width="48" /></td>
    <td><b>GEMMSA</b><br/>
    Simulation et calcul des <b>cotisations sociales agricoles (MSA)</b> :
    assiettes, abattements et cotisations par activité (viticulture, élevage,
    maraîchage / arboriculture, bois / ETA…), ATEXA, FMSE, VIVEA.</td>
  </tr>
  <tr>
    <td width="64" align="center"><img src="assets/gemcalc_ico.png" width="48" /></td>
    <td><b>GEMCALC</b><br/>
    Moteur d'<b>hypothèses et de simulations financières</b> : projections et
    scénarios autour des <b>prêts</b> et du financement.</td>
  </tr>
</table>

## Administration & socle

<table>
  <tr>
    <td width="64" align="center"><img src="assets/gemmanager_ico.png" width="48" /></td>
    <td><b>GEMMANAGER</b><br/>
    Plateforme <b>centrale d'administration</b> de l'écosystème : licences,
    utilisateurs, clients, rôles et droits (RBAC), accès aux services.
    Fournit l'<b>authentification commune</b> aux autres applications.</td>
  </tr>
  <tr>
    <td width="64" align="center"><img src="assets/gemclient_ico.png" width="48" /></td>
    <td><b>GEMCLIENT</b> <i>(GEMUTILISATEURS)</i><br/>
    Alimentation de la <b>base utilisateurs</b> d'un client GEMMEO directement
    dans GEMMANAGER, sans saisie manuelle.</td>
  </tr>
</table>

## APIs

<table>
  <tr>
    <td width="64" align="center"><img src="assets/gementreprises_ico.png" width="48" /></td>
    <td><b>GEMENTREPRISES</b><br/>
    <b>API d'alimentation des entreprises</b> : crée et enrichit
    automatiquement les fiches entreprises dans GEMMEO au lieu d'une saisie
    manuelle.</td>
  </tr>
</table>

## Documentation & formation

<table>
  <tr>
    <td width="64" align="center"><img src="assets/gemdocs_ico.png" width="48" /></td>
    <td><b>GEMDOCS</b><br/>
    <b>Documentation</b> de l'ensemble des APIs et services de l'écosystème
    GEMMEO.</td>
  </tr>
  <tr>
    <td width="64" align="center"><img src="assets/gemlearning_ico.png" width="48" /></td>
    <td><b>GEMLEARNING</b><br/>
    Plateforme d'<b>e-learning</b> pour tous les services GEMMEO : tutoriels
    vidéo, guides et accompagnement.</td>
  </tr>
</table>

---

## Stack technique

Tous les nouveaux développements GEMMEO partagent la même architecture, afin
qu'un développeur puisse passer d'un produit à l'autre sans réapprentissage.

| Couche        | Technologies                          |
|---------------|---------------------------------------|
| Frontend      | Vue 3 · TypeScript · Vite · Pinia     |
| Backend / API | Node.js · Hono                        |
| Base de données | MySQL                               |
| Conteneurs    | Docker                                |
| CI/CD         | GitHub Actions                        |
| Existant      | WebDev / WLangage (en cours de migration) |

---

## Gestion de projet

L'ensemble des développements est suivi de façon centralisée via le projet
**GEMMEO — Roadmap & Bug Tracker** :

- Kanban global multi-services
- Suivi des bugs et des évolutions
- Roadmap produits et versions cibles
- Documentation technique

---

<div align="center">
<sub>GEMMEO — suite logicielle métier · développée pour l'écosystème Cerfrance.</sub>
</div>
