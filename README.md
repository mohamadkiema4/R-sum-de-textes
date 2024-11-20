# Resume-de-textes
Ce projet explore la génération automatique de résumés via deux approches : **extractive** (sélection de phrases clés) et **abstractive** (reformulation via T5). En s’appuyant sur le jeu de données CNN/Daily Mail, il couvre la préparation, le développement des modèles et l’évaluation par BLEU et ROUGE, avec des pistes d’amélioration.
### README - Résumé de Textes

Ce projet propose une exploration approfondie de la génération automatique de résumés de textes en utilisant deux approches : 

1. **Résumé extractif** : sélection des phrases clés directement issues du texte source.  
2. **Résumé abstrait** : reformulation et génération de nouveaux résumés à l’aide du modèle T5.

#### Objectifs :  
- Développer des modèles performants pour générer des résumés précis et informatifs.  
- Comparer les performances des approches extractive et abstractive à l’aide de métriques standard (BLEU, ROUGE).  
- Identifier les limites de chaque méthode et proposer des stratégies d’amélioration.

#### Méthodologie :  
- **Préparation des données** : Utilisation du jeu de données CNN/Daily Mail, prétraitement avec spaCy et sauvegarde des sous-ensembles.  
- **Développement** : Implémentation des modèles basés sur SentenceTransformer pour l'extraction et T5 pour la génération.  
- **Évaluation** : Calcul des scores BLEU et ROUGE pour mesurer la qualité des résumés générés.

#### Résultats :  
- Le résumé extractif offre une approche rapide mais limitée en fluidité.  
- Le résumé abstrait est plus flexible et précis, mais exigeant en ressources.  

#### Perspectives :  
- Améliorations via segmentation des textes, fine-tuning sur des données spécifiques ou utilisation de modèles spécialisés comme Longformer.  

