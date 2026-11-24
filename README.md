# ExamForge v1.1

**Application de création d'épreuves**  
**Conçu et développé par Kamguia Aimé.**

ExamForge est une application web autonome permettant de préparer des sujets d'évaluation, de les prévisualiser et de les imprimer au format A4/PDF.

## Démarrer

Ouvrir `index.html` dans un navigateur récent (Microsoft Edge, Google Chrome ou Firefox). Aucune installation ni connexion Internet n'est nécessaire pour utiliser l'application localement.

## Fonctionnalités

- Informations de l'épreuve : métier, module, année, type, durée et note maximale.
- Création de sections et de questions numérotées.
- Sous-questions, barème par question et espaces de réponse.
- Aperçu instantané de la mise en page.
- Impression et enregistrement en PDF.
- Export d'une épreuve individuelle en HTML.
- Bibliothèque locale d'épreuves.
- Export et import de la bibliothèque complète au format JSON.
- Mise en page adaptée aux écrans mobiles.
- Affichage du total des points attribués.

## Où sont enregistrées les épreuves ?

Les épreuves sont conservées dans le stockage local du navigateur (`localStorage`) sur l'appareil utilisé. Elles ne sont pas envoyées à un serveur.

**Important :** les données locales ne sont pas automatiquement partagées entre plusieurs ordinateurs ou navigateurs. Utiliser régulièrement **« Exporter sauvegardes »** pour créer un fichier JSON, puis **« Importer sauvegardes »** sur un autre appareil pour les restaurer.

## Modèle d'épreuve

L'application comprend actuellement un modèle de sujet configuré pour RICHY PROFESSIONAL SCHOOL OF MICROFINANCE. Cette mention concerne le modèle de document généré et ne constitue pas la signature de l'auteur de l'application.

## Publication

L'application est un site statique : `index.html` suffit pour l'héberger sur un service comme GitHub Pages. Aucun serveur applicatif n'est requis.

Une publication publique doit respecter les droits liés aux noms, logos et documents de tiers éventuellement présents dans les modèles.

## Structure

- `index.html` : page d'entrée pour l'hébergement statique.
- `examforge.html` : fichier principal de l'application.
- `LISEZ-MOI.txt` : guide rapide en français.

**© 2026 Kamguia Aimé — ExamForge.**
