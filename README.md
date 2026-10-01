# Gabriel Resende

**Développeur full stack Java / Angular** — Pau, France · télétravail ou mobile France entière<br>
[LinkedIn](https://www.linkedin.com/in/gabriel-resende747/) · [Portfolio](https://resendecode.github.io/portfolio/) · gabrielresende02@proton.me

🇫🇷 Français · 🇬🇧 [English below](#english)

---

## À propos

Diplômé du Master Technologies Internet (UPPA, 2026). Pendant mon stage de fin d'études chez
UPDAT3D, studio de rendu 3D pour l'horlogerie, j'ai été le seul développeur de l'entreprise :
six mois pour remplacer une application vitrine mono-client par une plateforme SaaS multi-client,
conçue, testée, documentée et mise en production de bout en bout. Je cherche un premier poste de
développeur full stack ou backend où cette autonomie est un atout.

## Ce que j'ai construit récemment

**Gecko — plateforme de Digital Asset Management pour rendus 3D** (avril – septembre 2026)

Une grande marque horlogère y consulte ses catalogues de rendus, approuve les versions et laisse
ses retours. Le dépôt est privé (produit de l'entreprise) ; je le présente volontiers en entretien.

- **Backend** — API REST Spring Boot 4 / Java 25, modèle de domaine riche (agrégat, invariants dans
  les entités), JPA / PostgreSQL, migrations Flyway, import rejouable des données legacy.
- **Frontend** — SPA Angular 21 (standalone, signals, zoneless) : galerie, fiche projet, visionneuse
  360°, comparaison de versions, éditeur de projet, tableau de bord admin, revue client avec
  commentaires épinglés sur le rendu.
- **Sécurité** — JWT avec refresh token rotatif en cookie HttpOnly `SameSite=Strict`, rôles, CSP
  stricte, en-têtes HTTP durcis.
- **Stockage objet** — Cloudflare R2 via AWS SDK S3 : upload direct navigateur → bucket par URL
  pré-signée, versions immuables, livraisons vidéo multi-ratio.
- **Mise en production** — VPS, Docker Compose, Caddy, nginx, Cloudflare ; CI GitHub Actions qui
  teste puis publie les images sur GHCR ; sauvegardes et monitoring via systemd. En service depuis
  août 2026.
- **Qualité et transmission** — tests d'intégration sur PostgreSQL embarqué, tests Jest, glossaire de
  domaine, ADR et notes techniques pour la reprise du projet.

## Dépôts à regarder

| Dépôt | Ce que c'est |
|---|---|
| [2025_SocioPulse](https://github.com/resendecode/2025_SocioPulse) | Projet tuteuré avec Capgemini — réseau social Angular / Laravel / MySQL, authentification et déploiement Docker |
| [ProjectManager](https://github.com/resendecode/ProjectManager) | Projet de génie logiciel — Angular / Spring Boot, UML et SRS |
| [BetterFood](https://github.com/resendecode/BetterFood) | Informations nutritionnelles par code-barres (OpenFoodFacts), Java |
| [jenkinsrepo](https://github.com/resendecode/jenkinsrepo) | Pipeline CI/CD Jenkins avec Docker et Maven |

## Stack

Java · Spring Boot · Hibernate · Flyway · PostgreSQL · TypeScript · Angular · RxJS · Jest ·
Docker · GitHub Actions · Caddy · nginx · Cloudflare · Linux · S3 / R2 / MinIO

---

<a name="english"></a>
## English

**Full-stack developer, Java / Angular** — Pau, France · remote or willing to relocate within France

Master's in Internet Technologies (UPPA, 2026). During my final-year internship at UPDAT3D, a 3D
rendering studio for the watch industry, I was the company's only developer: six months to replace a
single-client showcase app with a multi-client SaaS platform, designed, tested, documented and
deployed to production end to end. Looking for a first full-stack or backend position where that
autonomy is an asset.

**Gecko — Digital Asset Management platform for 3D renders** (April – September 2026). A major watch
brand browses its render catalogues, approves versions and leaves feedback. The repository is private
(company product); happy to walk through it in an interview.

- **Backend** — Spring Boot 4 / Java 25 REST API, rich domain model (aggregate, invariants in the
  entities), JPA / PostgreSQL, Flyway migrations, replayable import of legacy data.
- **Frontend** — Angular 21 SPA (standalone, signals, zoneless): gallery, project page, 360° viewer,
  version comparison, project editor, admin dashboard, client review with comments pinned on the render.
- **Security** — JWT with rotating refresh token in an HttpOnly `SameSite=Strict` cookie, roles,
  strict CSP, hardened HTTP headers.
- **Object storage** — Cloudflare R2 through the AWS S3 SDK: direct browser-to-bucket upload via
  pre-signed URLs, immutable versions, multi-ratio video deliveries.
- **Production** — VPS, Docker Compose, Caddy, nginx, Cloudflare; GitHub Actions CI that tests then
  publishes images to GHCR; backups and monitoring through systemd. Live since August 2026.
- **Quality and handover** — integration tests on embedded PostgreSQL, Jest tests, domain glossary,
  ADRs and technical notes for whoever takes over.

Languages: Portuguese (native), French (bilingual), English and Spanish (C1).
