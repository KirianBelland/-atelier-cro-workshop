# 🎯 Atelier d'Idéation CRO - Shopping Section

Site web interactif **collaboratif en temps réel** pour organiser et animer un atelier d'idéation CRO avec analyse des parcours utilisateurs, frictions identifiées et hypothèses d'AB tests.

## 🌐 Mode Collaboratif en Temps Réel

**Tous les participants peuvent modifier les données simultanément !**
- ✅ Synchronisation instantanée entre tous les utilisateurs
- ✅ Modifications visibles en temps réel
- ✅ Parfait pour animer un atelier avec plusieurs équipes

## 🚀 Accès Rapide

**Site en ligne :** https://kirianbelland.github.io/atelier-cro-workshop/

Ou ouvrir `index.html` localement dans votre navigateur.

## ✨ Fonctionnalités

### 📊 Analyse & Données
- Analyse Overview complète (volumes, devices, pays)
- Parcours utilisateurs détaillés
- Comportements in-page par page critique
- Frictions organisées par thèmes
- Hypothèses d'amélioration structurées
- Idées d'AB tests priorisées

### ✏️ Édition Dynamique
- ➕ **Créer** : parcours, pages, composants, thèmes, hypothèses, idées
- ✏️ **Modifier** : tous les éléments sont éditables
- 🏷️ **Catégoriser** : parcours bons/mauvais, thématiques
- 🗑️ **Supprimer** : gestion complète des éléments

### 🔄 Collaboration
- 🌐 **Temps réel** : modifications synchronisées instantanément
- 👥 **Multi-utilisateurs** : plusieurs personnes peuvent éditer simultanément
- 💾 **Sauvegarde auto** : toutes les modifications sont sauvegardées
- 📥 **Export** : JSON et PDF disponibles

## 🔧 Configuration Firebase (Optionnel)

Le site fonctionne en mode local par défaut. Pour activer le mode collaboratif :

1. Créez votre projet Firebase (voir `FIREBASE_SETUP.md`)
2. Remplacez la configuration Firebase dans `index.html` (ligne ~1600)
3. Tous les participants utiliseront le même lien et verront les modifications en direct !

**Statut visible dans l'en-tête :**
- 🌐 **Mode Collaboratif Actif** : Firebase connecté, modifications synchronisées
- 💾 **Mode Local** : Firebase non configuré, sauvegarde locale uniquement

## 📝 Utilisation pendant l'Atelier

### Option 1 : Mode Animateur Seul
- Ouvrez le site sur votre ordinateur
- Projetez votre écran
- Vous modifiez, les participants voient en direct

### Option 2 : Mode Collaboratif
- Configurez Firebase (5 minutes)
- Partagez le lien à tous les participants
- Chacun peut contribuer en temps réel
- Divisez les équipes par thématiques (Prix, Search, Chambres, etc.)

## 🎯 Déroulé d'Atelier Recommandé

1. **Présentation Overview** (15 min) : contexte et chiffres clés
2. **Analyse Parcours** (20 min) : identifier les parcours convertissants/non-convertissants
3. **Comportements In-Page** (25 min) : analyser chaque page critique
4. **Identification Frictions** (30 min) : groupes par thématique
5. **Formulation Hypothèses** (20 min) : framework Si/Alors/Impact
6. **Idéation AB Tests** (30 min) : proposer des tests concrets
7. **Priorisation** (20 min) : scoring ICE et roadmap

**Durée totale : 2h30**

---

## 🛠️ Support Technique

Besoin d'aide ? Consultez :
- `FIREBASE_SETUP.md` pour la configuration collaborative
- Issues GitHub : https://github.com/KirianBelland/atelier-cro-workshop/issues

---

**Créé pour les ateliers CRO Shopping (France & US)**  
Lead CRO : Kirian Belland | Club Med

