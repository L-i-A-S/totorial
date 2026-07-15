## 📚 Sommaire

- [Prérequis](uploader_sur_t9.md#prérequis)
- [Définition](uploader_sur_t9.md#définition)
- [Préparation](uploader_sur_t9.md#préparation)
  - [Vérification du doublon](doublon.md)
  - [Création du .torrent](dotTorrent.md)
  - [Création du NFO](NFO.md)
- [Uploader sur T9](uploader_sur_t9.md#uploader-sur-t9) → [Guide détaillé](video_file.md)
- [Rendre disponible votre upload](uploader_sur_t9.md#rendre-disponible-votre-upload)


### Uploader un fichier vidéo (Film, série, ...)

#### Etape 1

Dans mon cas, j'upload dans la catégorie des films et sous catégorie des films  

<img width="893" height="752" alt="image" src="https://github.com/user-attachments/assets/11ba0cb6-0e52-4a93-a4e2-7d8875d8a915" />

<img width="898" height="685" alt="image" src="https://github.com/user-attachments/assets/bb850c53-0a44-49eb-8403-46d1db81c9c9" />

#### Etape 2

Dans les films & séries ( & ...), nous avons le plaisir de pouvoir utiliser la Génération Automatique, un bonheur et une simplification très agréable  

<img width="889" height="649" alt="image" src="https://github.com/user-attachments/assets/08d81193-3b6c-4cc7-9e9d-e80ff83e9485" />

#### Etape 3 

<img width="892" height="584" alt="image" src="https://github.com/user-attachments/assets/ae1b7cfa-593f-4710-8312-4c082d1c30cf" />

<img width="884" height="677" alt="image" src="https://github.com/user-attachments/assets/2c94f21f-d7a6-43fa-95e8-b579871ada3d" />

#### Etape 4 

<img width="889" height="753" alt="image" src="https://github.com/user-attachments/assets/470f1b61-4bd6-4a79-8530-6ea024840bca" />
 
Retournez sur l'onglet de MediaInfo et appuyez sur Copy to Clipboard  

<img width="951" height="406" alt="image" src="https://github.com/user-attachments/assets/737aa811-c52e-450c-8a21-596b974909c5" />

Collez dans la zone de texte

<img width="793" height="1028" alt="image" src="https://github.com/user-attachments/assets/b13a0671-34c9-4cdb-88ab-816c0e5c5061" />  

#### Etape 5 
Recherche sur TMDB de votre film/série  
Il est important de retirer les tags qui peuvent subsiter et de conserver que le nom du film  

<img width="800" height="471" alt="image" src="https://github.com/user-attachments/assets/c5b77a06-45ee-4a82-a113-f49c8afb1884" />

<img width="799" height="713" alt="image" src="https://github.com/user-attachments/assets/d4a1c42e-1786-47ab-9f2c-d90bdd31757e" />

#### Etape 6 

##### Titre & Infos techniques

<img width="1072" height="691" alt="image" src="https://github.com/user-attachments/assets/e6e33332-80f7-41ad-9b45-bb5e217c98ce" />

Là, il est nécessaire de respecter les conventions de nommage que vous donnent T9  
A la fois dans l'encart Format suggéré mais aussi dans les règles <url_T9>/rules  

<img width="472" height="94" alt="image" src="https://github.com/user-attachments/assets/d220a3b7-f3e0-421e-9728-68a4862cd5ec" />

Dans mon cas, on peut voir que le nom contient 2 fois le codec audio,  
Je vais donc en retirer 1 et conserver le codec audio FR, qui sera celui majoritairement utilisé sur un site francophone  
De plus, on peut voir que les tags Codec Vidéo et Codec Audio sont inversés  
Le nom correct selon la nomenclature T9 :  
<img width="466" height="29" alt="image" src="https://github.com/user-attachments/assets/1a8b50a1-705d-483d-8158-a4d48eddc581" />

Pour la fiche technique, vu que vous avez renseigné un NFO complet généré par MediaInfo  
Vous n'avez normalemnt rien à faire, tout a été complété !  

<img width="1010" height="582" alt="image" src="https://github.com/user-attachments/assets/77236bc6-9265-431f-a21e-945be3a5d63b" />

Un coup d'oeil ne fait pas de mal  

Il vous reste plus qu'à générer la présentation  

<img width="1010" height="58" alt="image" src="https://github.com/user-attachments/assets/c15f522e-ae86-4f39-8486-5153c57c31f1" />

##### Edition & Publication

Les TAGS   

<img width="250" height="82" alt="image" src="https://github.com/user-attachments/assets/47d4b312-3c3b-4f1f-a369-e560cde3be68" />

Un certain nombre de tags sont colorisés pour mettre en évidence certaines infos   
Exemple :  
<img width="156" height="475" alt="image" src="https://github.com/user-attachments/assets/118e537f-0aa4-4703-9fb0-452f5b585aaa" />

Vous pouvez ajouter comme tag, le(s) genre(s), le numéro de saison, d'épisodes, si c'est une série intégrale ou non, ... Informations utiles pour une meilleure recherche.  

Ensuite, vous avez la description faite en BBCode, elle est généralement très complète.  
Rien ne vous empeche d'ajouter des informations (avec une belle mise en forme)  
D'ajouter une signature si vous devenez un gros uploader ou releaser  

Dernière petite case,  
Le choix d'uploader à titre anonyme, libre à vous de cocher ou non.  

Et ensuite publier :   

<img width="1012" height="74" alt="image" src="https://github.com/user-attachments/assets/c59cdf6a-68eb-4fa8-a567-f93b2840352e" />  

S'il n'y a pas d'erreur, pas de doublon détecté (via le hash uniquement), il vous faut sauvegarder le torrent créé par T9  

<img width="585" height="643" alt="image" src="https://github.com/user-attachments/assets/e86434e1-7ecf-43be-af7c-368b0b4396dd" />
