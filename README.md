### "# Developpement_JakartaEE_TP9" 

#### Objectif
Ce TP vise à comprendre et personnaliser le mécanisme d’authentification de Spring Security.
L’objectif est de remplacer la page de connexion par défaut de Spring par un formulaire HTML personnalisé, tout en gérant :
* les erreurs de connexion,
* les redirections après authentification,
* la déconnexion,
* et la différenciation des accès selon les rôles.
Ce TP fait suite au TP (authentification en mémoire) et introduit la notion de flux d’authentification contrôlé par l’application.

#### Création du projet
<img width="959" height="479" alt="Création du projet" src="https://github.com/user-attachments/assets/5852c5f6-36e5-4354-bfac-60fd5c2104b4" />

#### Structure du projet 
<img width="959" height="503" alt="Structure de projet" src="https://github.com/user-attachments/assets/2f3270d6-3b76-4e94-9874-8d12b66d51b9" />


#### Exécution

##### Tentative d’accès sans login
<img width="958" height="502" alt="Execution1" src="https://github.com/user-attachments/assets/150ddc0e-6e04-46f5-8236-6a08dba229bc" />

##### Connexion réussie
###### Admin
<img width="959" height="504" alt="CNX admin" src="https://github.com/user-attachments/assets/ebd94656-d248-409a-9688-9dea1da95667" />
<img width="959" height="497" alt="Home" src="https://github.com/user-attachments/assets/b9b87a49-1222-4272-af54-16596dc97e4a" />
<img width="959" height="500" alt="espace Admin" src="https://github.com/user-attachments/assets/177e076b-f1ad-46bf-b830-003d9cf459f2" />

###### User 
<img width="959" height="503" alt="CNX user" src="https://github.com/user-attachments/assets/c8d5119a-6046-4bab-bc46-86861b25a4da" />
<img width="959" height="497" alt="Home" src="https://github.com/user-attachments/assets/5960e44f-a914-4138-af74-9b136061f8c3" />
<img width="959" height="500" alt="User dashbord" src="https://github.com/user-attachments/assets/ddcce227-6d39-4a34-b535-549d945b9779" />


##### Mauvais mot de passe
<img width="959" height="482" alt="MOT DE PASSE INCORRECTE" src="https://github.com/user-attachments/assets/1f7c9e4d-116f-49c6-8c0b-23c541466b78" />

##### Déconnexion
<img width="1919" height="953" alt="image" src="https://github.com/user-attachments/assets/d16a56ac-0500-4c86-99bc-7d5243c22098" />

##### Accès à /admin/dashboard sans rôle
<img width="959" height="500" alt="Admin non dans User" src="https://github.com/user-attachments/assets/8a292e4a-35a1-451e-96d6-e01e662e8de2" />





