# Conformité à compléter avant publication

Le site a été préparé pour limiter les risques RGPD et LCEN, mais il ne peut pas être
légalement complet sans les informations réelles de l'entreprise.

## Renseigné

- Identité légale de l'éditeur : GEYSSE Guillaume, entrepreneur individuel.
- Adresse administrative : Mas de Figuières, 34520 La Vacquerie-et-Saint-Martin-de-Castries.
- SIREN : 897 588 182 — SIRET : 897 588 182 00021 — TVA : FR35 897 588 182.
- Responsable de publication : Larzac Numeric et GEYSSE Guillaume.
- Téléphone : 06 47 59 74 65 — Email : guillaume.geysse@gmail.com.
- Nom de domaine : geysse-elagage.fr (canonique sans www).
- Immatriculation : RNE (le Répertoire des Métiers a été supprimé au 01/01/2023).
  Reste à vérifier sur l'extrait RNE si la mention "entreprise relevant du secteur
  des métiers et de l'artisanat" figure : si oui, elle peut être ajoutée aux mentions légales.
- Assurance RC professionnelle : zone de couverture d'environ 50 km autour de l'adresse administrative.
- Conditions commerciales : devis gratuits valables 2 mois, aucun acompte, paiement par virement,
  chèque ou espèces à l'issue de la prestation, délai d'intervention de 15 jours à 1 mois.
- Droit de rétractation : 14 jours (contrats hors établissement). Le délai d'intervention étant
  supérieur, les travaux commencent normalement après expiration du délai.
- Formation : Attestation de grimpe niveau initial (seule qualification affichée sur le site).
- Prise de contact exclusivement téléphonique : aucun formulaire, aucune collecte de données par le site.

## À compléter avant mise en ligne définitive

- Assurance RC pro : nom de l'assureur, numéro de contrat, détail des garanties.
  Point à vérifier auprès de l'assureur : la couverture doit inclure explicitement
  l'élagage sur corde sans limitation de hauteur (certains contrats plafonnent à 5 m).
- Autres certifications éventuelles (CS Arboriste-Élagueur, CACES, secourisme...) :
  ne les afficher que si elles peuvent être prouvées. À ce jour, seule l'attestation de grimpe niveau initial
  est mentionnée. La section s'intitule "Formation & compétences" et non "Certifications",
  pour ne rien revendiquer au-delà des justificatifs disponibles.
- Médiateur de la consommation désigné, obligatoire pour les litiges avec consommateurs.
- Joindre le formulaire de rétractation à chaque devis signé au domicile du client
  (obligation légale pour les contrats hors établissement).
- Hébergeur principal réellement utilisé (les mentions légales listent plusieurs prestataires possibles).
- Liens réseaux sociaux : encore à "#" dans content.json ; à renseigner pour activer
  le champ sameAs du JSON-LD.

## Points techniques traités

- Suppression des appels navigateur à Google Fonts, Tailwind CDN, Pravatar et proxy CMS externe.
- Carte Google Maps chargée uniquement après consentement explicite du visiteur.
- Formulaire de contact et bouton WhatsApp retirés : contact téléphonique uniquement.
- En-têtes Netlify de sécurité (CSP, HSTS, X-Frame-Options) et politique de cache.
- Redirection 301 de www vers le domaine canonique sans www.
