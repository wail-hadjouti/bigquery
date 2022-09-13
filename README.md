# Test technique
https://unnest.notion.site/Test-technique-da7a51308fb441f0a81075bf95a7db43


En utilisant le [dataset public](https://cloud.google.com/bigquery/public-data/) 
bigquery de données GA4 `bigquery-public-data.ga4_obfuscated_sample_ecommerce` 
créer une visualistion (data studio, collab, matplotlib…) permettant d’analyser 
la donnée avec au minimum :

- Le nombre de sessions unique par mois. #sessions
- La part d’utilisateurs selon le navigateur. #utilisateurs, navigateur     #pourcentage 1/4
- La part d’utilisateurs mobiles. #utilisateurs, mobiles
- Le nombre de vues par utilisateur unique de la page d’acceuil.
- Les 10 sites les plus visités sur les 6 derniers mois.
- Le temps d’engagement utilisateur median par mois.
- Le referer qui amène le plus vers la page “Women apparel”.
- Combien de sessions ont visité plus de 10 page l’an dernier.

L’analyse peut se faire avec l’outil de votre choix (bigquery, python, datastudio…) 
Il faut juste nous renvoyer le lien vers un repository git contenant le code 
d’export/import de données et les requètes que vous avez faites si elles 
existent (ou bien un petit texte résumant le calcul) 
à l’adresse [antoine.puyo@unnest.co](mailto:antoine.puyo@unnest.co) .