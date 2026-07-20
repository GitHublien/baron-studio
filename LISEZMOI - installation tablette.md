# 🧳 VALISE TABLETTE — Baron Douphol

## Ce que c'est
Un studio **100 % autonome** : partition + traductions + audio + fiches,
qui marche **sans Internet, sans Reaper, sans ordinateur**. Dans la voiture,
en coulisses, partout.

## Installation sur la tablette Android (5 minutes)

1. **Brancher la tablette au PC en USB** → sur la tablette, choisir
   « Transfert de fichiers » dans la notification.
2. Dans l'explorateur Windows, copier **le dossier entier** `VALISE TABLETTE`
   vers la tablette, dans `Download` (ou `Documents`).
3. Copier aussi le dossier `PARTITIONS TABLETTE` (Offenbach), qui est dans
   `Concert-Offenbach-23juillet2026`.
4. Sur la tablette : ouvrir l'appli **Fichiers** → `Download/VALISE TABLETTE`
   → toucher **STUDIO.html** → ouvrir avec **Chrome**.
5. ⭐ Dans Chrome : menu ⋮ → « Ajouter à l'écran d'accueil » → tu auras une
   icône BARON directement sur le bureau de la tablette.

## ⚠️ LE TEST OBLIGATOIRE (avant de partir !)
Mode avion **activé** → ouvrir le studio → tourner 3 pages → lancer un audio.
Si tout marche en mode avion, tout marchera partout.

## Ce que le studio sait faire
- 📖 Les 127 pages (Actes I et II), tape à droite/gauche pour tourner
- 🗂 Sommaire par scène + mode « Pages Baron » (seulement tes pages)
- 📝 Traductions et indications de jeu sous chaque page (tes répliques en corail)
- 🎧 4 bandes : Chant/Piano × Acte 1/Acte 2
- 🔁 Boucle A→B (appuie sur A au début du passage, B à la fin → ça tourne en boucle)
- 🐢 Ralenti 70 % / 85 % sans changer la hauteur
- ⏪ −30s / −5s / +5s
- 📄 Bouton « Fiches » : le final par cases, les 56 temps, la scène des cartes,
  la partition PDF complète surlignée
- 💾 Il rouvre tout seul la dernière page où tu étais

## Ce que le studio ne fait PAS (honnêteté)
La **tourne de page automatique** synchronisée n'existe que dans le studio
Reaper du PC : la calibration est liée au montage Reaper, pas à ces MP3.
Sur la tablette, on tourne à la main — c'est voulu, et en pratique c'est
même mieux pour mémoriser.

## Si l'audio ne joue pas
Le dossier `audio/` doit contenir 4 fichiers MP3. S'il est vide, c'est que
le script Reaper `PREPARER_VALISE_TABLETTE.lua` n'a pas encore été lancé
sur le PC (Actions → ReaScript → Run), ou que la copie a sauté ce dossier.
