# 🧘 POMODORO RITUEL - Minuterie de Concentration

## Application Mobile de Productivité et d'Ambiance Sonore.

Bienvenue dans le dépôt du projet **POMODORO RITUEL**. Ce module est conçu pour transformer vos sessions de travail et de révision en un rituel structuré et sans distraction, en combinant la technique Pomodoro avec un environnement sonore immersif.

### 🧠 Objectif du Projet

L'objectif de POMODORO RITUEL est de fournir un outil *minimaliste* et *esthétique* pour structurer les cycles de travail et de repos, améliorer la concentration grâce à l'ambiance sonore, et suivre le temps total de focus accumulé.

---

### ✨ Fonctionnalités Clés (Focus Minuterie)

| Catégorie | Description | Statut |
| :--- | :--- | :--- |
| **Minuterie** | Cycles de **FOCUS** et **PAUSE** entièrement personnalisables (durées et répétitions). | ✅ Fonctionnel |
| **Ambiance** | Sélecteur d'ambiances sonores (Pluie, Cheminée, etc.) jouant en boucle pendant les sessions. | ✅ Fonctionnel |
| **Esthétique** | Thèmes Dynamiques (Clair/Sombre) et minuterie circulaire avec affichage clair du temps restant. | ✅ Fonctionnel |
| **Suivi** | Statistiques totales du temps de focus accumulé (via AsyncStorage). | ✅ Fonctionnel |
| **Contrôle** | Boutons de Pause, Reprise et Réinitialisation immédiate du cycle. | ✅ Fonctionnel |

---

### 🛠️ Technologies & Esthétique

| Composant | Technologie | Note |
| :--- | :--- | :--- |
| **Audio** | `expo-av` | Gestion des sons d'ambiance en arrière-plan. |
| **Stockage** | `AsyncStorage` | Persistance des statistiques et du temps de focus total. |
| **Haptique** | `Vibration` | Feedback physique pour marquer le début et la fin des cycles. |
| **Design** | Typographie Serif (Baskerville/serif) | Style élégant, minimaliste, avec une forte lisibilité. |

---

### ⚙️ Configuration & Lancement

Ce projet nécessite des dépendances Expo spécifiques pour l'audio et le stockage, ainsi que des assets locaux (fichiers MP3).

#### Installation des dépendances

```bash
# Installation des dépendances Expo pour l'audio et le stockage
npx expo install expo-av @react-native-async-storage/async-storage
