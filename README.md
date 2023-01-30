# parcelles
Trouver des parcelles de terrain en France


Filtre sur:
- Le code INSEE de la commune (obligatoire)
- La taille minimum de la parcelle en m2 (optionnel)
- La taille maximum de la parcelle en m2 (optionnel)


Le lien vers Google Maps pointe vers le centre de la parcelle. (Note: il est géométriquement possible que le centre soit en dehors de la parcelle)


Url de demo : https://gabrieldelepine.github.io/parcelles/


Idées de fonctionnalités pour les versions à venir:
- trier par section quand la taille est identique
- afficher une zone sur Google Maps et non un point unique (si possible)
- pouvoir mettre une parcelle en favori


Ressources
- Code INSEE et nom de la ville à partir du code postal https://public.opendatasoft.com/api/records/1.0/search/?dataset=correspondance-code-insee-code-postal&q=77100&facet=insee_com&facet=statut


APIs
- Module cadastre https://api.gouv.fr/les-api/api_carto_cadastre
- Opendatasoft https://public.opendatasoft.com/explore/dataset/correspondance-code-insee-code-postal/api/
