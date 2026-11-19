# Vidéos quotidiennes MZL (YouTube, Shorts, TikTok)

Chaîne YouTube « MZL Maroc » (@mzlmaroc, ID UC_lW0gNFUOOIGrJbtd9ZohA). Publication publique autorisée par l'utilisateur. N'invente aucun chiffre, prix ou client. Ne modifie rien d'autre sur la chaîne ni sur TikTok.

## Méthode YouTube (navigateur intégré)
1. Ouvre https://studio.youtube.com/channel/UC_lW0gNFUOOIGrJbtd9ZohA/videos/upload?d=ud (fenêtre d'import).
2. Sans cliquer sur le sélecteur de fichier, en JavaScript : trouver input[type=file] (y compris dans les shadowRoot) ;
   b = await fetch('<URL>').then(r=>r.blob()) ; f = new File([b], '<nom>.mp4', {type:'video/mp4'}) ; DataTransfer → input.files ; dispatchEvent(new Event('change',{bubbles:true})).
   Le téléchargement peut dépasser 45 s : lancer le script, attendre, puis vérifier que le champ titre apparaît.
3. Titre : clic, ctrl+a, taper le titre (Shorts : ajouter « #Shorts »). Description : gabarit ci-dessous.
4. « Non, elle n'est pas conçue pour les enfants », Suivant ×3, « Publique », Publier (si hors écran : JavaScript, chercher #done-button dans les shadowRoot et .click()). Vérifier le message de mise en ligne / traitement.

URL vidéo classique (16:9) : https://zakaria-mzl.github.io/carnet-de-forme/mzl-videos/mzl-<fichier classique>
URL Short (9:16) : https://zakaria-mzl.github.io/carnet-de-forme/mzl-videos/vertical/<fichier vertical>

Gabarit de description :
« <phrase produit>. Fabrication MZL dans notre atelier de Mers El Kheir, près de Rabat, livraison et pose partout au Maroc.
En savoir plus : <page>
Devis gratuit 7 j/7 de 8 h à 23 h : https://www.mzl.ma/contactus
WhatsApp : +212 7 07 05 05 55
#maroc #mzl <hashtag> »

## Méthode TikTok (Claude in Chrome — le navigateur intégré bloque le chargement de fichiers sur TikTok)
1. Onglet Chrome https://www.tiktok.com/tiktokstudio/upload. Si la page de connexion s'affiche : sauter TikTok et le signaler (ne jamais saisir de mot de passe).
2. D'abord mcp__remote-devices__device_stage_files sur C:\Users\ADMIN\Pictures\photos mzl\selection reseaux sociaux\videos-publicitaires\tiktok\<fichier vertical> (versions de moins de 3,8 Mo), puis find « input file » et mcp__claude-in-chrome__file_upload (origin https://www.tiktok.com) avec le chemin STAGÉ /mnt/user-data/uploads/Pictures/photos mzl/selection reseaux sociaux/videos-publicitaires/tiktok/<fichier vertical> (le chemin Windows est refusé). Si une fenêtre « vérifications automatiques » apparaît : Annuler. Cliquer dans la zone de texte de la légende avant ctrl+a/Backspace.
3. Légende : « <titre> – <phrase produit>. Devis gratuit 7 j/7 : www.mzl.ma – WhatsApp +212 7 07 05 05 55 #maroc #mzl <hashtag> #fabriquéaumaroc ». Visibilité : Tout le monde. Publier. Vérifier. Au moindre avertissement de TikTok : arrêter et prévenir.

## Liste (ordre de publication) — fichier vertical | fichier classique | titre | page | phrase produit | hashtag
Déjà publiés le 19/11/2026 : vidéo classique chalets (https://youtu.be/IkcNRLbVmj4) ; Short kiosques (02). TikTok : kiosques (02) publié le 19/11 (en cours d'examen).
1. 02-kiosques-bois.mp4 | 02-kiosques-bois.mp4 | Kiosques en bois au Maroc pour événements et food courts | https://www.mzl.ma/kiosque-bois-maroc | Kiosques en bois démontables sur mesure pour food courts, cafés, boutiques et événements ; références : Trophée Hassan II de golf, finale LGCT Rabat, Jazzablanca | #kiosquebois
2. 01-chalets-bois.mp4 | 01-chalets-bois.mp4 | Chalets en bois au Maroc, de 24 à 180 m² | https://www.mzl.ma/chalet | Chalets et bungalows en bois démontables de 24 à 180 m² | #chaletbois
3. 07-abris-de-piscine.mp4 | 07-abris-de-piscine.mp4 | Abris de piscine sur mesure au Maroc | https://www.mzl.ma/abri-de-piscine | Abris de piscine bas, mi-hauts et hauts | #abripiscine
4. 03-fenetres-baies-vitrees.mp4 | 03-fenetres-baies-vitrees.mp4 | Fenêtres et baies vitrées aluminium au Maroc | https://www.mzl.ma/baies-vitrees | Fenêtres et baies vitrées aluminium à rupture thermique, double vitrage | #menuiseriealuminium
5. 10-pergolas-carports.mp4 | 10-pergolas-carports.mp4 | Pergolas et carports sur mesure au Maroc | https://www.mzl.ma/pergolas-carports | Pergolas et carports sur mesure | #pergola
6. 09-verandas.mp4 | 09-verandas.mp4 | Vérandas sur mesure au Maroc | https://www.mzl.ma/verandas | Vérandas sur mesure | #veranda
7. 17-villas-cle-en-main.mp4 | 17-villas-cle-en-main.mp4 | Villas clé en main au Maroc | https://www.mzl.ma/villas-cle-en-main | Villas clé en main avec un seul interlocuteur | #cleenmain
8. 15-hotels-restaurants-cle-en-main.mp4 | 15-hotels-restaurants-cle-en-main.mp4 | Hôtels et restaurants clé en main au Maroc | https://www.mzl.ma/hotels-cle-en-main | Hôtels, restaurants et lounges clé en main | #hotel
9. 06-portails-clotures-garage.mp4 | 06-portails-clotures-garage.mp4 | Portails, clôtures et portes de garage au Maroc | https://www.mzl.ma/portails-clotures | Portails, clôtures et portes de garage sur mesure | #portail
10. 12-parquets-sols-lambris.mp4 | 12-parquets-sols-lambris.mp4 | Parquets, sols et lambris en bois au Maroc | https://www.mzl.ma/parquets-sols-lambris | Parquets, sols et lambris en bois | #parquet
11. 18-charpente-metallique.mp4 | 18-charpente-metallique.mp4 | Charpente métallique au Maroc | https://www.mzl.ma/charpente-metallique | Charpentes métalliques sur mesure | #charpentemetallique
12. 08-terrasse-coulissante-piscine.mp4 | 08-terrasse-coulissante-piscine.mp4 | Terrasse coulissante de piscine au Maroc | https://www.mzl.ma/abri-de-piscine | Terrasse coulissante qui couvre la piscine | #piscine
13. 04-volets-persiennes-stores.mp4 | 04-volets-persiennes-stores.mp4 | Volets, persiennes et stores sur mesure au Maroc | https://www.mzl.ma/volets-persiennes | Volets, persiennes et stores sur mesure | #volets
14. 05-portes.mp4 | 05-portes.mp4 | Portes sur mesure au Maroc | https://www.mzl.ma/portes | Portes en bois, aluminium et métal | #portes
15. 11-amenagements-exterieurs.mp4 | 11-amenagements-exterieurs.mp4 | Terrasses en bois et aménagements extérieurs au Maroc | https://www.mzl.ma/amenagements-exterieurs | Aménagements extérieurs et terrasses en bois | #terrassebois
16. 14-agencement-interieur.mp4 | 14-agencement-interieur.mp4 | Agencement intérieur sur mesure au Maroc | https://www.mzl.ma/mobilier-amenagement-interieurs | Agencement intérieur et mobilier sur mesure | #agencement
17. 13-salons-canapes.mp4 | 13-salons-canapes.mp4 | Salons et canapés sur mesure au Maroc | https://www.mzl.ma/mobilier-amenagement-interieurs | Salons et canapés sur mesure | #salonmarocain
18. 16-boutiques-cle-en-main.mp4 | 16-boutiques-cle-en-main.mp4 | Boutiques clé en main au Maroc | https://www.mzl.ma/projet-cle-en-main | Agencement de boutiques et commerces clé en main | #boutique
19. 19-corps-de-metier.mp4 | 19-corps-de-metier.mp4 | Tous corps de métier, un seul interlocuteur | https://www.mzl.ma/projet-cle-en-main | Menuiserie, métal, aluminium et agencement réunis | #renovation
20. 20-mzl-film-de-marque.mp4 | film-de-marque.mp4 | MZL, fabriqué au Maroc | https://www.mzl.ma/a-propos | De l'atelier de Mers El Kheir au montage sur chantier | #fabriqueaumaroc

Chaque jour : prends l'entrée la plus haute pas encore publiée pour CHAQUE canal (vidéo classique, Short, TikTok) — les canaux peuvent être à des numéros différents.
