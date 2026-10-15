<div align="center">
  <h1>🎓 IUT de Vélizy-Rambouillet — UVSQ</h1>
  <p><strong>Plateforme de développement des applications et outils internes de l'IUT</strong></p>

  <!-- Badges d'information et liens rapides -->
  <p>
    <a href="https://www.iut-velizy-rambouillet.uvsq.fr/">
      <img src="https://img.shields.io/badge/Site_Officiel-IUT_Vélizy--Rambouillet-005596?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Site IUT" />
    </a>
    <a href="https://www.uvsq.fr/">
      <img src="https://img.shields.io/badge/Université-UVSQ-008489?style=for-the-badge&logo=academia&logoColor=white" alt="UVSQ" />
    </a>
    <a href="https://ent.uvsq.fr/">
      <img src="https://img.shields.io/badge/Portail-ENT_UVSQ-2E3440?style=for-the-badge&logo=discourse&logoColor=white" alt="ENT UVSQ" />
    </a>
  </p>
</div>

---

### 👋 À propos de cette organisation

Bienvenue sur l'espace GitHub officiel de l'**IUT de Vélizy-Rambouillet** (composante de l'*Université de Versailles Saint-Quentin-en-Yvelines* — *Université Paris-Saclay*).

Cette organisation centralise le code source des applications pédagogiques, administratives et techniques développées en interne par le personnel, les enseignants et les étudiants (projets tutorés, SAÉ, stages et outils des services techniques).

---

### 🚀 Nos projets principaux

| Projet | Description | Technologies | Statut | Accès |
| :--- | :--- | :--- | :---: | :---: |
| **[edtpp](https://github.com/IUT-Velizy-Rambouillet/edtpp)** | Panneau d'affichage dynamique (emplois du temps et informations écrans) | ![PHP](https://img.shields.io/badge/-PHP-777BB4?style=flat-square&logo=php&logoColor=white) ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) | 🟢 Actif | 🔒 Interne |
| **[demo-repository](https://github.com/IUT-Velizy-Rambouillet/demo-repository)** | Dépôt de démonstration, de test et de prise en main GitHub | ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) | 🧪 Test | 🔒 Interne |
| *Futur projet* | *À venir — Outil interne ou projet départemental* | ![JavaScript](https://img.shields.io/badge/-JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black) | ⏳ Prévu | 🔒 Interne |

---

### 🏛️ Campus & Départements de l'IUT

Nos outils accompagnent le quotidien des équipes et des étudiants répartis sur nos deux sites :

* 📍 **Site de Vélizy-Villacoublay :**
  * 💻 **INFO** — Informatique
  * 🎨 **MMI** — Métiers du Multimédia et de l'Internet
  * ⚡ **GEII** — Génie Électrique et Informatique Industrielle
  * 🌐 **R&T** — Réseaux et Télécommunications
* 📍 **Site de Rambouillet :**
  * 💼 **GEA** — Gestion des Entreprises et des Administrations
  * 🤝 **TC** — Techniques de Commercialisation
  * 🧪 **GCGP** — Génie Chimique - Génie des Procédés

---

### 🛠️ Technologies & Standards utilisés

<p>
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
</p>

---

### 📌 Guide pour les membres (Étudiants, Enseignants & BIATSS)

#### 1. Accès aux dépôts privés
Si vous ne voyez pas les dépôts de votre projet sur la page d'accueil :
* Vérifiez que vous êtes bien connecté au compte GitHub ayant reçu l'invitation de l'organisation.
* En haut à droite de la page d'accueil de l'organisation, basculez l'affichage de **`View as: Public`** vers **`View as: Member`**.

#### 2. Flux de travail (Workflow Git)
Pour garantir la stabilité des applications en production (notamment sur les écrans et serveurs de l'IUT), merci de respecter ces règles :
1. **Branche principale protégée :** Ne poussez jamais directement sur la branche `main` (ou `master`).
2. **Branches de travail :** Créez une branche dédiée pour chaque évolution ou correction :
   * `feature/nom-de-la-fonctionnalite` (ex: `feature/meteo-panneau`)
   * `fix/nom-du-bug` (ex: `fix/affichage-horaires`)
3. **Pull Requests (PR) :** Une fois votre code testé localement, ouvrez une *Pull Request* vers `main` et demandez une relecture avant la fusion (*merge*).

#### 3. Convention de commits
Privilégiez des messages de commit clairs et préfixés :
* `feat:` ajout d'une nouvelle fonctionnalité
* `fix:` correction d'un bug
* `style:` modifications visuelles (CSS, mise en page)
* `docs:` mise à jour de la documentation (`README`, commentaires)

#### 4. Sécurité & Confidentialité 🔒
* **Aucun secret dans le code :** Ne commitez **jamais** de mots de passe, clés d'API, certificats ou identifiants de base de données.
* Utilisez systématiquement un fichier `.env` ignoré par Git (via `.gitignore`) et fournissez uniquement un fichier `.env.example` contenant des valeurs fictives.

---

<div align="center">
  <sub>📍 <b>IUT de Vélizy-Rambouillet</b> — 10-12 avenue de l'Europe, 78140 Vélizy-Villacoublay | 19 allée des Vignes, 78120 Rambouillet</sub>
</div>