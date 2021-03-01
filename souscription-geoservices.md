# Souscription à Géoservices

le site internet https://www.geoportail.gouv.fr/ met à disposition gratuitement certaines données de l'IGN. Il est possible à des applications tierces comme l'application mobile iphigénie ou des sites tiers de cartographie de tirer profit gratuitement de ces données à travers les [Géoservices IGN](https://geoservices.ign.fr/).

Dans le cadre de la démarche open-data engagée par le gouvernement français, Géoservices est accessible gratuitement aux particuliers depuis 2021, voir [communiqué de presse](https://www.ign.fr/sites/default/files/2020-12/cp_gratuite_donnees_2020.pdf). À date du 1 mars 2021, bien que l'accès soit gratuit, la procédure d'accès n'est pas simplifée, il est toujours nécessaire de demander auprès de Géoservices la création d'une clé personnelle afin d'accéder à leurs données.

Cette clé est ensuite à mentionner dans le fichier de configuration d'AlpineQuest décrivant comment accéder aux cartes IGN.

Voici les étapes permettant d'obtenir une clé Géoservices.

1. Ouvrir le formulaire de demande: https://www.sphinxonline.com/surveyserver/s/etudesmk/Geoservices_2021/questionnaire.htm#49
    ![formulaire-geoservices](./images/geoservices-form-1.png)
1. Choisir une clé pour un site Web (WMTS ...)
    ![formulaire-geoservices](./images/geoservices-form-2.png)
1. Utiliser le mode de sécurité "User-agent" avec comme valeur `AlpineQuest`
    ![formulaire-geoservices](./images/geoservices-form-3.png)
1. Renseigner vos informations personnelles et Commander la clé.
    ![formulaire-geoservices](./images/geoservices-form-4.png)
1. Une clé d'utilisation vous est envoyée par courriel, sous un jour ouvré en général.
