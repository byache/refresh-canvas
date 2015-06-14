# Tutoriel de casse-briques

Une série de pages interactives pour créer un jeu de casse-briques en JavaScript avec jQuery. En Python 2.7.

## Utilisation

    cd tutorial
    virtualenv venv  # Pas nécessaire
    . venv/bin/activate  # Idem
    pip install -r requirements.txt
    python make.py

Cela créera des pages Web statiques dans le dossier `build` que vous pourrez envoyer où vous le voulez.

Pour tester les pages, si vous avez Python 3 :

    cd build
    python3 -m http.server

Puis allez sur http://localhost:8000/

## Dépendances

- Le moteur de templates [mako](http://www.makotemplates.org)
- Le format de données [YAML](http://www.yaml.org), via [PyYAML](http://pyyaml.org)

## Contributeurs

- Bill Mill @llimllib
- Benny Daon @daonb
- Jill-Jênn Vie @jjvie (traduction)
