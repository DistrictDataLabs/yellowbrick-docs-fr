.. -*- mode: rst -*-

Contributing
============

Yellowbrick est un projet open source soutenu par une communauté qui acceptera avec gratitude et humilité toutes les contributions que vous pourriez apporter au projet. Grande ou petite, toute contribution fait une grande différence ; et si vous n'avez jamais contribué à un projet open source auparavant, nous espérons que vous commencerez avec Yellowbrick !

Principalement, le développement de Yellowbrick concerne l'ajout et la création de *visualiseurs* &mdash; des objets qui apprennent des données et créent une représentation visuelle des données ou du modèle. Les visualiseurs s'intègrent aux estimateurs, transformateurs et pipelines de scikit-learn pour des objectifs spécifiques et, par conséquent, peuvent être simples à construire et à déployer. La contribution la plus courante est donc un nouveau visualiseur pour un modèle ou une famille de modèles spécifique. Nous verrons plus tard en détail comment construire des visualiseurs.

Au-delà de la création de visualiseurs, il existe de nombreuses façons de contribuer:

- Soumettre un rapport de bogue ou une demande de fonctionnalité sur `GitHub issues`_.
- Ajoutez un carnet Jupyter à notre `examples gallery`_.
- Aidez-nous avec les :doc:`user testing <../evaluation>`.
- Ajoutez à la documentation ou aidez-nous avec notre site web, `scikit-yb.org`_
- Écrire des tests unitaires ou d'intégration pour notre projet.
- Répondre aux questions sur `GitHub issues`_, `mailing list`_, `Stack Overflow`_, and `Twitter`_.
- Traduire notre documentation dans une autre langue.
- Écrire un billet de blog, tweeter ou partager notre projet avec d'autres.
- Enseigner à quelqu'un comment utiliser Yellowbrick.

Comme vous pouvez le voir, il y a de nombreuses façons de s'impliquer et nous serions très heureux que vous nous rejoigniez ! La seule chose que nous vous demandons est de respecter les principes d'ouverture, de respect et de considération des autres tels que décrits dans le :doc:`../code_of_conduct`.

.. note:: If you're unsure where to start, perhaps the best place is to drop the maintainers a note via our mailing list: http://bit.ly/yb-listserv.

.. _`examples gallery`: https://github.com/DistrictDataLabs/yellowbrick/tree/develop/examples
.. _`scikit-yb.org`: http://www.scikit-yb.org
.. _`GitHub issues`: https://github.com/DistrictDataLabs/yellowbrick/issues
.. _`mailing list`: http://bit.ly/yb-listserv
.. _`Stack Overflow`: https://stackoverflow.com/questions/tagged/yellowbrick
.. _`Twitter`: https://twitter.com/scikit_yb

.. toctree::
    :caption: Contributing Guide
    :maxdepth: 2

    getting_started
    developing_visualizers
    advanced_development_topics
