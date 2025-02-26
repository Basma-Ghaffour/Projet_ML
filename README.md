# Projet web-scraping

## 1. Scraping

Pour extraire les données qui nous intéressent du site, nous avons créé 4 librairies : librairie_1, librairie_2, librairie_3 et librairie_4. Chacune d'entre elles permet de réaliser une partie de l'extraction des données, dans l'ordre de leur numérotation. L'objet final contenant les données extraites est disponible dans le document "liste_final.json" présent dans le répertoire. Il a été utilisé ultérieurement dans le projet pour la création et le nettoyage de la base de données.

Remarque : Du fait de l'approche que l'on a utilisée pour la création des librairies de cette partie, nous avons rencontré des difficultés à passer les tests sur ces librairies. Des problèmes d'importation des librairies que nous avons créées et qui sont directement utilisées dans les suivantes, ainsi que la non possibilitée d'empêcher la compilation complète à chaque test (librairie_1 exclu).



Une fonction permet ensuite de calculer le meilleur estimateur.

*NB : le meilleur modèle est recalculé si le scraping est relancé.*

Les prédictions obtenues sont stockées dans un tableau `resultat.csv`.

# Installation

- En téléchargeant le dossier :
```sh
py -m pip install C:/Users/Downloads/GHAFFOUR_JEAN_SONDEJI_PROJECT
```
