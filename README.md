# Tutoriel 

Une série de pages interactives pour créer des activités d'algorithmique en lycée (classe de 2nde, France). Le langage est JavaScript, avec jQuery et aussi Python 2.7.

## Utilisation

    cd tutorial
    pip install -r requirements.txt
    python make.py

Cela créera des pages Web statiques dans le dossier `build` que vous pourrez envoyer où vous le voulez.
Allez dans le dossier "tutorial > chapters" et modifiez les fichiers yaml.
Refaites un make.py pour metre à jour le dossier build.

## Dépendances

- Le moteur de templates [mako](http://www.makotemplates.org)
- Le format de données [YAML](http://www.yaml.org), via [PyYAML](http://pyyaml.org)

## Pédagogie

L'idée est de mettre en oeuvre le travail conjoint de la géométrie et de l'algorithmique, tel que suggéré par Jill-Jenn Vie ( http://jill-jenn.net/conferences/#geometrie-dans-les-jeux-video ).
Le niveau est celui de la classe de 2nde.
Une autre implémentation utilisant blockly au lieu du javascript est en cours d'élaboration ici : http://beaubiat.fr/Algo-avec-blockly/blockly/blockly_et_graphique/

## Contributeurs

- Bill Mill @llimllib
- Benny Daon @daonb
- Jill-Jênn Vie @jjvie (traduction)
- Paul Byache @byache (activités pédagogiques)
