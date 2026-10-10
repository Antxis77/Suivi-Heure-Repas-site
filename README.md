# Suivi Heure & Repas — site

Site statique (HTML + CSS, sans framework, sans cookie ni traceur) publié avec GitHub Pages :
https://antxis77.github.io/Suivi-Heure-Repas-site/

- `index.html` — présentation de l'app
- `support.html` — assistance et FAQ
- `confidentialite.html` — politique de confidentialité
- `cgu.html` — conditions d'utilisation

La FAQ de `support.html` est générée depuis le dépôt de l'app (source unique avec la FAQ intégrée) :

```bash
python3 scripts/export_faq.py ../Suivi-Heure-Repas-site/support.html
```
