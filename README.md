[![DOI](https://zenodo.org/badge/742518754.svg)](https://zenodo.org/doi/10.5281/zenodo.13820296)

# M2 : Science Climatique Computationnelle

> Comment analyser des jeux de données climatiques maillés avec des attributs spatiaux et temporels ? Comment mesurer et modéliser la variabilité climatique ?

Le deuxième module de notre [curriculum de science climatique ouverte](https://openclimatescience.github.io/curriculum) est centré sur la préparation des apprenant·e·s à travailler avec des jeux de données climatiques maillés.

**À la fin de ce module, vous serez capable de :**

- Découvrir les indices disponibles pour la sécheresse météorologique, l’humidité du sol, la demande atmosphérique en eau, et le bilan hydrique des sols.
- Charger et analyser efficacement de grands jeux de données climatiques, y compris des séries temporelles longues.
- Calculer un indice de sécheresse.

## Contenu

1. [Gérer les dépendances logicielles](https://github.com/OpenClimateScience/M2-Computational-Climate-Science-FR/blob/main/notebooks/M2.1%20-%20Gestion%20des%20d%C3%A9pendances%20logicielles.ipynb)  
2. [Travailler avec des données climatiques maillées](https://github.com/OpenClimateScience/M2-Computational-Climate-Science-FR/blob/main/notebooks/M2.2%20-%20Travailler%20avec%20des%20donn%C3%A9es%20climatiques%20grindt%C3%A9es.ipynb)  
3. [Indices climatiques et de sécheresse](https://github.com/OpenClimateScience/M2-Computational-Climate-Science-FR/blob/main/notebooks/M2.3%20-%20Indices%20climatiques%20et%20de%20s%C3%A9cheresse.ipynb)  
4. [Traiter des séries climatiques longues en parallèle](https://github.com/OpenClimateScience/M2-Computational-Climate-Science-FR/blob/main/notebooks/M2.4%20-%20Traitement%20simultan%C3%A9%20des%20enregistrements%20de%20donn%C3%A9es%20climatiques%20de%20longue%20dur%C3%A9e.ipynb)  
5. [Créer une analyse climatique reproductible](https://github.com/OpenClimateScience/M2-Computational-Climate-Science/blob/main/notebooks/05_Creating_a_Reproducible_Climate_Data_Analysis.ipynb]https://github.com/OpenClimateScience/M2-Computational-Climate-Science-FR/blob/main/notebooks/M2.5%20-%20Cr%C3%A9ation%20d'une%20analyse%20reproductible%20des%20donn%C3%A9es%20climatiques.ipynb)

## Démarrage

[Consultez notre guide d'installation ici.](https://github.com/OpenClimateScience/M1-Open-Climate-Data/blob/main/HOW_TO_INSTALL.md)

Vous pouvez exécuter les notebooks de ce dépôt via [Github Codespaces](https://docs.github.com/en/codespaces/overview) ou comme [conteneur de développement VSCode](https://code.visualstudio.com/docs/devcontainers/containers). Une fois le conteneur lancé, ouvrez Jupyter Notebook en exécutant :

```sh
# Créez un mot de passe lorsque demandé
jupyter server password

# Puis lancez Jupyter Notebook ; entrez votre mot de passe
jupyter notebook
```

**Les bibliothèques Python nécessaires aux exercices peuvent être installées avec le gestionnaire de paquets `pip` :**

```sh
pip install xarray netcdf4 dask
```

## Résultats d'apprentissage

- Utilise des noms de fichiers et de dossiers significatifs mais concis. (CC1.3)  
- Utilise un gestionnaire de paquets pour les dépendances. (CC1.10)  
- Navigue dans un système de fichiers via GUI et CLI. (CC1.4)  
- Documente les relations code-résultats-métadonnées. (CC1.5)  
- Comprend les types numériques. (CC2.1)  
- Utilise des tableaux multidimensionnels. (CC2.3)  
- Analyse l'utilisation des ressources. (CC2.5)  
- Maîtrise les types de parallélisation. (CC2.6)  
- Sait déboguer un flux de travail. (CC2.7)

## Jeux de données climatiques utilisés

- [Anomalies du stockage d’eau terrestre - NASA GRACE/GRACE-FO](https://podaac.jpl.nasa.gov/dataset/TELLUS_GRAC-GRFO_MASCON_CRI_GRID_RL06.1_V3)  
- Estimations de précipitations mensuelles en Afrique - [CHIRPS](https://www.chc.ucsb.edu/data/chirps)  
- Évapotranspiration potentielle mensuelle - [TerraClimate](https://climatedataguide.ucar.edu/climate-data/terraclimate-global-high-resolution-gridded-temperature-precipitation-and-other-water)  
- Températures journalières - [MERRA-2 de la NASA](https://gmao.gsfc.nasa.gov/reanalysis/MERRA-2/)

## Remerciements

Ce curriculum a été rendu possible grâce à une subvention du programme de formation TOPS (Transition to Open Science) de la NASA (80NSSC23K0864), qui fait partie du [programme TOPS de la NASA](https://nasa.github.io/Transform-to-Open-Science/).
