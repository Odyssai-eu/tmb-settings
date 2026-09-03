# TMB Settings

Source de vérité des **TMB Settings** servies par le routeur (ex-CoeOS → Theseus).
Forgejo = source ; ce miroir GitHub public est ce que les box importent.

- `index.json` — la liste des settings + le défaut.
- `<nom>.json` — un setting : axes, registre de modèles, décideur.

La box tire le raw : `COEOS_SETTINGS_URL` → l'URL raw d'un setting ;
le catalogue = `index.json` + les fichiers par nom.
