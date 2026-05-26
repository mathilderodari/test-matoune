# Serpent's Quest — Snake Vibe Coding

Jeu Snake médiéval créé lors de l'atelier **Vibe Coding** de Wavestone. L'objectif : générer un jeu complet en une session, en collaborant avec une IA (Claude Code) comme co-pilote de développement — du design à la logique de jeu.

## Jouer

👉 [Ouvrir le jeu](https://mathilderodari.github.io/snake-vibe-groupe-a/)

> Le jeu fonctionne entièrement dans le navigateur, sans serveur ni installation.

## Contrôles

| Touche | Action |
|--------|--------|
| `←` `→` `↑` `↓` | Déplacer le serpent |
| `Entrée` | Démarrer / Rejouer |
| `Espace` | Pause / Reprendre |
| `W` `A` `S` `D` | Alternative aux flèches |

## Mécaniques de jeu

- 🍎 **Pomme** — +1 Denier, +1 segment
- ⭐ **Étoile Bonus** — +3 Deniers, +2 segments
- 💀 **Mur ou soi-même** — Game Over
- 🏆 **Meilleur score** sauvegardé localement (localStorage)

## Design

Le jeu utilise le système de design **Dragon's Ledger** — une esthétique médiévale fantasy avec :
- Palette parchemin, cramoisi et or
- Polices *Libre Caslon Text* & *EB Garamond*
- Bordures en fer forgé et sceaux de cire

## Construit avec

- [Claude Code](https://claude.ai/code) — assistant de développement IA (Anthropic)
- HTML / CSS / JavaScript vanilla
- [Tailwind CSS](https://tailwindcss.com)
- Carte de jeu définie dans `snake_map_vibe_coding.xlsx`
