# Comment uploader sur T9

## 📚 Sommaire

- [Prérequis](uploader_sur_t9.md#prérequis)
- [Définition](uploader_sur_t9.md#définition)
- [Préparation](uploader_sur_t9.md#préparation)
  - [Vérification du doublon](doublon.md)
  - [Création du .torrent](dotTorrent.md)
  - [Création du NFO](NFO.md)
- [Uploader sur T9](uploader_sur_t9.md#uploader-sur-t9) → [Guide détaillé](video_file.md)
- [Rendre disponible votre upload](uploader_sur_t9.md#rendre-disponible-votre-upload)


## Prerequis 

- Lire les règles présentes sur la page des règles <url_T9>/rules ;
- Lire les questions/réponses présentes sur la page de la foire aux questions <url_T9>/faq ;
- Avoir un fichier qui n'existe pas sur le tracker. Les doublons sont interdits ;
- Avoir un fichier qui respecte les règles (voir lien plus haut).

## Definition

- Doublon : La release est déjà présente sur le site. Cela veut dire que votre fichier qui a été release par la team ABC, avec les codecs audio/vidéo, qualité, résolution, poids, taille etc ne peut pas déjà être présent.  
- NFO : MediaInfo fournit des informations techniques et les tags à propos de vos fichiers video et audio : https://mediaarea.net/MediaInfoOnline .  
- TMDB : Annuaire des films / séries : https://www.themoviedb.org .  
- BBCode : BBCode est un langage de balisage léger inventé pour simplifier la mise en forme des messages sur les forums de discussion internet. https://fr.wikipedia.org/wiki/BBCode .  

## Préparation

### Vérification du doublon

Merci de rechercher votre fichier sur <url_T9>/search :  
- N'hésitez pas à ne mettre que le nom "officiel" de la série, en FR ou/puis en EN ;  
- N'hésitez pas à ajouter le tag de votre qualité (1080p, 2160p,...) pour filtrer les résultats ;  
- N'hésitez pas à faire la recherche via l'outil de recherche assistée TMDB.  

Pour mon exemple, je vais uploader le film Thunderstruck (2012) (https://www.themoviedb.org/movie/119738-thunderstruck).  

<img width="1400" height="879" alt="image" src="https://github.com/user-attachments/assets/885ffae6-410c-4dc1-9971-2d015fa63ec4" />

Je n'ai pas besoin d'affiner plus la recherche car je n'ai pas beaucoup de résultats.  
Mais il ne faut pas hésiter à utiliser les différents filtres pour ajuster au maximum la recherche.  
Les filtres que je recommande sont :  
- Recherche dans : Titre ;  
- Catégorie / Sous Catégorie : Ce qui vous concerne ;  
- Tag : Résolution (1080p, 2160p, ...), Numéro de saison, ...  

Voir [Exemple de recherche de doublon](doublon.md)

### Création du .torrent

Voir [Création du .torrent](dotTorrent.md)
  
  
### Création du nfo
  
Voir [Création du NFO](NFO.md)

### Uploader sur T9

Rendez-vous sur "Uploader un torrent" <url_T9>/upload  

<img width="803" height="231" alt="image" src="https://github.com/user-attachments/assets/8fd321b3-d126-4056-8b2e-c6a72e2327e9" />

L'upload sur T9 se fait en 6 étapes si on passe par le mode "automatique" présent sur plusieurs catégories dont les films et les séries.  

Voir [Uploader un fichier vidéo (film, série, ...)](video_file.md)

### Rendre disponible votre upload

Dernière étape,  
Il vous faut ajouter votre torrent dans votre logiciel préféré de torrent.   
Exemple sur qBittorent :  

<img width="842" height="538" alt="image" src="https://github.com/user-attachments/assets/d3bb5199-226e-473a-983b-8d2a235e0155" />


<img width="982" height="907" alt="image" src="https://github.com/user-attachments/assets/0d3b92e6-0902-4be7-b2ec-38a1f3c6eea5" />

<img width="1011" height="27" alt="image" src="https://github.com/user-attachments/assets/6daac8f3-ecf2-4019-9f37-8130f0d0d8b8" />

<img width="979" height="21" alt="image" src="https://github.com/user-attachments/assets/7be06dd9-644a-4bcf-85b8-735dbf8f4eb7" />

Ensuite, c'est à la Team Pending ou au bot de valider votre upload.
