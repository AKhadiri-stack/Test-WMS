# Supports pédagogiques d’Alix Khadiri

Ces règles s’appliquent à tout support de cours et TP HTML créé ou modifié dans ce dépôt.

- Respecter la progression de la classe, la durée de la séance et les notions du référentiel. Utiliser la mise en page du WMS pédagogique comme référence, avec des visuels qui facilitent l’activité. Prévoir des exercices progressifs et un quiz de fin de séance.
- Afficher un espace Élève avec inscription claire, sélection de la classe ou du groupe et de l’élève, travail en solo ou en binôme et choix du partenaire. Enregistrer les saisies et confirmer la remise de la copie.
- Afficher un espace Professeur protégé côté serveur. Récupérer automatiquement les copies et les scores par élève, groupe ou binôme. Garder les codes, les listes nominatives et les corrigés privés hors du HTML public.
- Bloquer le copier-coller dans les champs de réponse des élèves, y compris via le menu contextuel. Préserver le fonctionnement des champs d’identification et des outils professeur.
- Produire la vidéo de la séquence avec NotebookLM, puis publier la vidéo sur YouTube Studio avec la visibilité convenue. Intégrer le lecteur dans le HTML avec un cadrage adaptatif au format 16:9 et un lien YouTube de secours. Vérifier la lecture depuis le lien partagé aux élèves.
- Prévoir l’impression en PDF du sujet et celle du corrigé depuis un support ou un espace professeur protégé.
- Avant de partager un lien, vérifier sur la page publiée la lecture vidéo, l’inscription en solo et en binôme, la sauvegarde, la remise et la réception dans l’espace Professeur, le blocage du copier-coller et l’impression. Signaler explicitement les éléments encore en attente ou impossibles à vérifier.

Le TP `tp-stock-disponible.html` donne un exemple de réception des remises. Les exigences ci-dessous s’appliquent à toute nouvelle publication.

## Exigences de publication pour les TP HTML élèves

Applique ces consignes à chaque nouveau TP HTML destiné à être utilisé par les élèves, ainsi qu’à toute mise à jour du circuit de remise.

- **Sauvegarde automatique.** Héberge les pages sur GitHub Pages et enregistre les réponses dans Supabase sous le code individuel, dès la saisie et même si le TP est inachevé. Conserve un brouillon local en cas de coupure, resynchronise-le à la reconnexion et indique clairement si la sauvegarde en ligne est confirmée. Vérifie la reprise après rechargement.
- **Copies et notes.** Dans l’espace professeur protégé, affiche les brouillons et les copies remises, avec recherche par code individuel, groupe et rôle lorsqu’il y en a plusieurs. Permets de saisir, modifier et relire la note et le commentaire. Le professeur récupère les copies via Supabase, sans dépôt manuel dans Pronote. Les élèves ne doivent pouvoir consulter ni les copies d’autres élèves ni les commandes de notation.
- **Copier-coller.** Bloque le collage et le copier-coller dans les champs de réponse, notamment via le clavier et le menu contextuel. Laisse le collage fonctionner dans le champ du code élève et dans les outils du professeur.
- **Alerte d’ajout soudain.** Signale au professeur l’apparition d’un bloc de texte en une seule modification d’un champ de réponse, y compris si aucun événement de collage n’est détecté. Remonte le code élève, la question, l’heure et le nombre de caractères ajoutés. Exclue le champ du code et la restauration automatique d’un brouillon. Présente l’alerte comme un signal à vérifier, sans sanction automatique.
- **Pendant le TP.** Signale les sorties et retours dans l’onglet ou la perte de focus de la page, avec leur durée quand elle est disponible. Le signal décrit ce que la page observe.
- **Recette avant diffusion.** Depuis les URLs qui seront envoyées, utilise un code fictif par rôle et un compte professeur de test. Saisis une réponse partielle, vérifie qu’elle arrive côté professeur avant validation, recharge la page et vérifie la reprise. Simule une coupure puis une reconnexion. Teste le collage autorisé du code, le collage bloqué dans une réponse et l’alerte sur ajout soudain sans événement de collage. Termine l’exercice, retrouve la copie par code, saisis une note, modifie-la puis recharge l’espace professeur et vérifie la valeur enregistrée. Pour Achat-Vente, vérifie aussi la transmission dans les deux sens et l’attribution à la bonne équipe. Consigne les résultats avant de diffuser les liens.
- **Seconde vérification.** Gemini peut relire le scénario de recette ou un cas fictif anonymisé. La validation de l’édition, de l’enregistrement et de la réception exige un essai réel dans le navigateur et dans Supabase.

## Mise en page à conserver

La page `eco-droit-contrat-institutions.html` est la référence visuelle. Pour tout nouveau support, partir de son HTML et de son CSS. Pour une mise à jour, conserver la structure et les styles de la page existante en les comparant à cette référence. Reprendre le menu latéral bleu nuit, les accents orange, la hiérarchie des titres, les cartes d’activité, les pictogrammes et les schémas intégrés. Ajouter les nouveaux exercices, lecteurs et espaces Élève et Professeur dans cette même structure et avec les mêmes composants visuels.

Avant livraison, comparer la page à la référence sur grand écran et en largeur Chromebook. Vérifier la navigation, la lisibilité des encadrés, les zones de réponse et l’impression. Modifier l’identité visuelle uniquement sur demande explicite d’Alix.
