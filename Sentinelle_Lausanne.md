# 🔭 Sentinelle Lausanne — Semaine du 6 mai 2026

**Déploiement Netlify :** ⚠️ **Échec auto** — réseau sandbox bloqué (HTTP 403 `blocked-by-allowlist` sur `api.netlify.com`)
**Action requise :** déploiement manuel via drag & drop du ZIP sur https://app.netlify.com/sites/gilded-sunburst-623e60/deploys
**ZIP prêt :** [deploy.zip](computer:///sessions/zen-exciting-mccarthy/mnt/Downloads/deploy.zip) (17 kB, contient `index.html` à la racine)
**HTML source mis à jour :** [REGIS_GOALS_APP_2026.html](computer:///sessions/zen-exciting-mccarthy/mnt/Downloads/REGIS_GOALS_APP_2026.html)
**URL publique (après déploiement) :** https://gilded-sunburst-623e60.netlify.app

**Événements vérifiés :** 13 événements avec URL source confirmée
**Catégories couvertes :** philo · theatre · music · famille · socio
**Fenêtre `hot:true` :** 6 → 12 mai 2026 (9 événements)

---

## ⚡ Cette semaine (hot — 6 → 13 mai)

### 🏛️ Mer 6 mai · Soirée philo Vincent Fornerod
Groupe vaudois de philosophie · soirée hors-cycle · gratuit
→ https://philo-vaud.ch/

### 💃 Mer 6 → Dim 10 mai · Fête de la Danse Lausanne
Spectacles, performances, ateliers (AVDC, Arsenic, Théâtre Sévelin 36) · gratuit
→ https://fetedeladanse.ch/lausanne/

### 🎤 Jeu 7 mai · Imany + Bleu Satellite — Les Docks
Voodoo Cello Tour · **sold out** (à surveiller en cas de retour billet)
→ https://www.docks.ch/en/programme/

### 🎨 Jeu 7 → Dim 10 mai · Lausanne Art Fair (8e éd.)
Beaulieu · 80 galeries · 2 500 œuvres · billets dès 15 CHF en ligne
→ https://beaulieu-lausanne.com/en/calendar/lausanne-art-fair-2026/

### 🎤 Ven 8 mai · Damso — BĒYĀH Tour
Vaudoise Aréna, Prilly · 20h · tournée internationale
→ https://vaudoisearena.ch/en/events/damso-beyah-tour-1

### 🎤 Sam 9 mai · Puma Blue + Salpa — Les Docks
Indie / jazz / dream-pop · **only Swiss show** · ~40 CHF
→ https://www.docks.ch/en/programme/

### 🎭 Sam 9 mai · Récital autour de Rigoletto — TKM
Foyer du TKM · collaboration Opéra de Lausanne · ~50 min · 20h
→ https://www.tkm.ch/

### 🎼 Mar 12 mai · Chœur universitaire & Sinfonietta — Cathédrale
Concert 20h · Cathédrale de Lausanne
→ https://www.cathedrale-lausanne.ch/accueil/agenda/

### 🎼 Mar 12 mai · Vevey Spring Classic — Final
Strauss / Beethoven / Mozart · Cameristi della Scala · Salle del Castillo, Vevey
→ https://vd.leprogramme.ch/

---

## 📅 Prochainement (14 → 31 mai)

### 🎸 Ven 15 mai · Ultra Vomit — Les Docks
Metal parodique français · ~35 CHF
→ https://www.docks.ch/en/programme/

### 🌱 Mer 20 mai · Fête de la Nature — Parc Louis-Bourget
14h–20h · animations flore & faune, castors, oiseaux, ateliers durabilité · gratuit
→ https://www.lausanne.ch/vie-pratique/nature/evenements-sorties/fete-de-la-nature-en-ville.html

### 🎤 Ven 22 mai · Calogero — Concert acoustique
Salle Métropole, Lausanne · tournée acoustique 150+ dates · billets dès 75 CHF
→ https://sallemetropole.ch/evenements/calogero/

### 🍷 Sam 23 → Dim 24 mai · Caves Ouvertes Vaudoises
200 caves, 8 AOC, 79 cépages · pass 20 CHF (incl. bon 20 CHF + Mobilis)
→ https://www.mescavesouvertes.ch/

---

## 💡 Suggestions personnalisées pour Régis

**1. 🏛️ Café philo Picpic — modèle à observer mercredi 6 mai**
La soirée Vincent Fornerod (philo-vaud.ch) tombe pile sur ton créneau Café philo Picpic du mercredi 20h. Y aller comme observateur permet de calibrer ton format avant le lancement Q2 (Goal #23). Si la date ne marche pas, le Café Philo Lausanne tourne tous les 15 jours au Benjamin Bar (Hotel de la Paix, dimanche 19h) — un autre format à étudier.

**2. 👧 Cléo — week-end famille à coût zéro**
La **Fête de la Danse** (6–10 mai, gratuit, lieux multiples) coche les cases sortie famille + culture + budget. Activité bonifiante côté coparenting et activable spontanément le samedi 9 ou dimanche 10. Plan B : Lausanne Art Fair (espace ouvert au public, billets enfants -12 ans souvent gratuits).

**3. 🍷 Réseau (Goal #21 : 12 nouvelles personnes) — Caves Ouvertes 23-24 mai**
Format idéal pour rencontrer du monde sans la pression d'un networking event. Pass Mobilis inclus dans le billet 20 CHF, donc déplacement vignoble vaudois sans logistique. Cibler 2-3 nouveaux contacts dans la journée et marquer le compteur du Goal #21.

---

## 🛠️ Notes techniques

- **EVENTS_DB** : 13 événements (anciens événements ≤ 5 mai supprimés, fenêtre roulante 6 → 31 mai).
- **Catégories** : `philo` (1), `theatre` (2), `music` (7), `famille` (1), `socio` (2). Aucun `squash` ce mois-ci (calendrier squashromandie.ch ne renvoie pas de tournoi confirmé pour mai 2026 — à recontrôler la semaine prochaine).
- **URLs** : toutes vérifiées via web search. Les liens Docks pointent vers la page programme générale (la page événement individuelle change après chaque concert).
- **Déploiement** : ZIP `deploy.zip` dans Downloads + copie dans `~/Documents/.goals_config/deploy/`. Le sandbox bash bloque `api.netlify.com` (proxy allowlist) → drag & drop manuel requis sur app.netlify.com.
