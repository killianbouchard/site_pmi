# Double pendule – simulation interactive

Site statique (HTML + JavaScript, aucune dépendance, aucun build) : port JavaScript du projet Python PMI.

**Onglets**
- **Simulation** : animation, énergies (T, V, H) + erreur relative, portraits de phase repliés, 2ᵉ pendule (écart ε sur φ1).
- **Poincaré** : section de Poincaré (variable de section, valeur, axes au choix).
- **Carte de Lyapunov** : exposant de Lyapunov (Benettin) sur la grille (θ1, θ2).
- **Carte du chaos** : un pendule par pixel, animée en temps réel, zoom molette + déplacement souris.
- **Convergence Lyapunov** : λ(t) pour 5°, 20°, 45°, 90°, 135°, 170° (ex‑`Bonus/lyapunov_div.py`).

**Modèles** : double pendule (Euler, Euler symplectique, Verlet, RK4) et double pendule élastique (RK4).

**Non repris** : équations adimensionnées, GPU OpenCL (remplacé par un calcul CPU dans le navigateur).

Projet PMI – Ababsa Abir, Boislaville Lou, Bouchard Killian, Boulesteix Alexandre.
