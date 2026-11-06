# MaintiDoc — Livrable 1

## Membres
- AMRANE
- MAMMOU

## Objectif
Créer un assistant documentaire multimodal d'aide à la maintenance, capable de rechercher des informations dans des documents techniques, d'exploiter des images et de préparer des tickets soumis à validation humaine.

## Familles étudiées
- Famille 1 : boîtiers électroniques automobiles (ECU, calculateurs, PCB).
- Famille 2 : faisceaux électriques, câbles et connecteurs automobiles.

## Contenu du ZIP
- `L1_MaintiDoc_AMRANE-MAMMOU_Rapport.pdf` : rapport (parties 2.1 à 2.6).
- `L1_MaintiDoc_AMRANE-MAMMOU_LienGitHub.txt` : URL du dépôt GitHub.
- `README.md` : membres, objectif et structure.
- `L1_MaintiDoc_AMRANE-MAMMOU_Corpus/` : documents, inventaire et prompts.

## Structure GitHub attendue
```text
maintidoc/
├── README.md
├── .gitignore
├── docs/diagrammes/
└── corpus/
    ├── inventaire.csv
    ├── prompts_corpus.md
    ├── documents/
    │   ├── famille_1/
    │   └── famille_2/
    └── images/
```

## Règles
Chaque document doit être nommé avec son `document_id` et figurer dans `inventaire.csv`, et inversement. Vérifier les licences et les informations techniques. Identifier les documents synthétiques. Ne déposer aucun secret, mot de passe, clé API ou donnée personnelle.

**État :** squelette de démarrage à compléter. Le corpus réel et le rapport complet restent à produire et vérifier.
