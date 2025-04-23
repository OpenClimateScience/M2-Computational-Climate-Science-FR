[![DOI](https://zenodo.org/badge/938928059.svg)](https://doi.org/10.5281/zenodo.15270602)

# M2 : Science Climatique Computationnelle

> Comment analyser des jeux de données climatiques maillés avec des dimensions spatiales et temporelles ? Comment mesurer et modéliser la variabilité climatique ?

Le deuxième module de notre [programme de formation en science climatique ouverte](https://openclimatescience.github.io/curriculum) a pour objectif de préparer les apprenants à travailler avec des jeux de données climatiques maillés.

**À l’issue de ce module, vous serez capable de :**

- Identifier les indices utilisés pour la sécheresse météorologique, la sécheresse du sol, la demande atmosphérique en eau et le bilan hydrique.
- Charger et analyser efficacement de grands ensembles de données climatiques, y compris des séries longues.
- Calculer un indice de sécheresse.

## Contenu du module

1. [Gérer les dépendances logicielles](https://github.com/OpenClimateScience/M2-Computational-Climate-Science/blob/main/notebooks/01_Managing_Software_Dependencies.ipynb)  
2. [Travailler avec des données climatiques maillées](https://github.com/OpenClimateScience/M2-Computational-Climate-Science/blob/main/notebooks/02_Working_with_Gridded_Climate_Data.ipynb)  
3. [Indices climatiques et de sécheresse](https://github.com/OpenClimateScience/M2-Computational-Climate-Science/blob/main/notebooks/03_Climate_and_Drought_Indices.ipynb)  
4. [Traiter de longues séries climatiques en parallèle](https://github.com/OpenClimateScience/M2-Computational-Climate-Science/blob/main/notebooks/04_Processing_Long_Climate_Data_Records.ipynb)  
5. [Créer une analyse climatique reproductible](https://github.com/OpenClimateScience/M2-Computational-Climate-Science/blob/main/notebooks/05_Creating_a_Reproducible_Climate_Data_Analysis.ipynb)

## Démarrage

[Consultez notre guide d’installation ici.](https://github.com/OpenClimateScience/M1-Open-Climate-Data/blob/main/HOW_TO_INSTALL.md)

Vous pouvez exécuter les notebooks de ce dépôt via [GitHub Codespaces](https://docs.github.com/en/codespaces/overview) ou en utilisant [un conteneur de développement VSCode](https://code.visualstudio.com/docs/devcontainers/containers). Une fois votre environnement lancé, démarrez Jupyter Notebook avec :

```sh
# Créez un mot de passe personnel lorsque cela est demandé
jupyter server password

# Ensuite, lancez Jupyter Notebook et entrez votre mot de passe
jupyter notebook
```

**Les bibliothèques Python nécessaires peuvent être installées via `pip` :**

```sh
pip install xarray netcdf4 dask
```

## Compétences acquises

- Utiliser des noms de fichiers et dossiers clairs et structurés. (CC1.3)  
- Naviguer dans un système de fichiers en GUI ou CLI. (CC1.4)  
- Documenter les liens entre code, résultats et métadonnées. (CC1.5)  
- Utiliser un gestionnaire de paquets pour les dépendances. (CC1.10)  
- Comprendre les représentations numériques. (CC2.1)  
- Maîtriser les tableaux multidimensionnels. (CC2.3)  
- Évaluer la consommation de ressources d’un workflow. (CC2.5)  
- Comprendre les types de parallélisme et optimiser le workflow. (CC2.6)  
- Déboguer un workflow computationnel. (CC2.7)  
- Connaître les formats structurés (raster, vecteur, HDF5, netCDF4). (CC2.8)  
- Documenter avec commentaires et documentation externe. (CC4.3)  
- Écrire des fonctions simples sans effets de bord. (CC4.9)

## Jeux de données climatiques utilisés

- [Anomalies du stockage d’eau – NASA GRACE & GRACE-FO](https://podaac.jpl.nasa.gov/dataset/TELLUS_GRAC-GRFO_MASCON_CRI_GRID_RL06.1_V3)  
- Estimations mensuelles de précipitations (CHIRPS) : [CHIRPS](https://www.chc.ucsb.edu/data/chirps)  
- Évapotranspiration potentielle mensuelle : [TerraClimate](https://climatedataguide.ucar.edu/climate-data/terraclimate-global-high-resolution-gridded-temperature-precipitation-and-other-water)  
- Températures quotidiennes moyennes/min/max : [MERRA-2 NASA](https://gmao.gsfc.nasa.gov/reanalysis/MERRA-2/)

## Remerciements

Ce module a été rendu possible grâce au soutien du programme de formation "Transition to Open Science (TOPS)" de la NASA (80NSSC23K0864), dans le cadre du [programme TOPS de la NASA](https://nasa.github.io/Transform-to-Open-Science/).
