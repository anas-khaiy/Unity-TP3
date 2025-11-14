# Unity-TP3

# Introduction de l’application
Cette application a été réalisée en utilisant Unity et le SDK Vuforia.
Elle permet d’afficher en réalité augmentée (AR) quatre organes du corps humain : le cœur, l’estomac, l’œil et le cerveau.
Lorsque l’utilisateur pointe la caméra vers une image spécifique, l’application reconnaît cette image (Image Target) et affiche automatiquement le modèle 3D correspondant.
Le but de cette application est d’offrir une expérience interactive, éducative et immersive pour mieux comprendre l’anatomie humaine.

# Étapes de réalisation du projet
## 1.  Définition du concept et des objectifs
- Déterminer le type d’application : application éducative en réalité augmentée.
- Choisir les organes à afficher : heart, stomach, eye, brain.
- Définir l’interaction : affichage automatique du modèle 3D lors de la détection d’une image cible.


## 2. Préparation des ressources
- créer les images qui serviront comme Image Targets.
<img width="100" height="150" alt="heartImg" src="https://github.com/user-attachments/assets/2f5c195f-5e31-41e4-81a5-ffe24cf43a78" />
<img width="100" height="150" alt="eyeImg" src="https://github.com/user-attachments/assets/b4893f79-b3e6-4078-b386-e47e7845ae73" />
<img width="100" height="150" alt="brainImg" src="https://github.com/user-attachments/assets/b81f3b1d-3ae7-4e86-9d94-ce2b8e0c7e04" />
<img width="100" height="150" alt="stomachImg" src="https://github.com/user-attachments/assets/148e3cc5-8fc6-4433-b9ef-4c0c684fc793" />


- Obtenir les modèles 3D des organes : cœur, estomac, œil, cerveau.


<img width="200" height="230" alt="image" src="https://github.com/user-attachments/assets/6b55f859-6599-47f8-82c9-f2f0c36ff543" />
<img width="200" height="230"  alt="image" src="https://github.com/user-attachments/assets/393ba855-d4c9-48d5-9757-1a462308c6eb" />
<img width="200" height="230"  alt="image" src="https://github.com/user-attachments/assets/418e58c0-aedb-40cb-8fd2-2629c4c76558" />
<img width="200" height="230"  alt="image" src="https://github.com/user-attachments/assets/2a678044-748b-4078-ae83-0faa77c9ee09" />

## 3. Création d’une base de données Vuforia
- Accéder au site de Vuforia Target Manager.
- Créer une nouvelle database.
- Importer les 4 images qui serviront de marqueurs (heart target, stomach target, eye target, brain target).
- Vérifier la qualité de chaque image.
- Générer puis télécharger la Image Target Database au format Unity Package.
- Importer cette base de données dans Unity.

<img width="400" height="370" alt="image" src="https://github.com/user-attachments/assets/4a86302b-a548-4b86-9dd7-aec13f23a14c" />


## 4. Configuration de Vuforia dans Unity
- Installer le Vuforia Engine dans Unity.
- Activer Vuforia dans le Player Settings.
- Ajouter un ARCamera dans la scène.
- Importer la database Vuforia et l’activer dans le projet.

<img width="1000" height="540" alt="image" src="https://github.com/user-attachments/assets/ca44eb79-d207-490d-b29e-0bfd84bca00b" />


##  5. Création des Image Targets
- Pour chaque organe : 
Ajouter un Image Target dans la scène Unity.
- Dans les paramètres Inspector, sélectionner : 
Database: ta base de données Vuforia + 
Image Target: l’image correspondante Ajuster l’échelle et la position.
- Les 4 Image Targets :   Heart Image Target + Stomach Image Target + Eye Image Target + Brain Image Target

## 6. Ajout des modèles 3D

- Pour chaque Image Target :
Importer le modèle 3D correspondant + Placer le modèle comme enfant (child) de l’Image Target.
- Ajuster :
l’échelle, + la rotation, + la position.


## 7. Tests et ajustements

- Tester l’application sur PC avec la webcam et sur smartphone.
- Vérifier :
- la vitesse de détection,
- la stabilité du modèle 3D,
- la fluidité de la rotation.


## 8. Build final
- Choisir la plateforme (Android et iOS).
- Configurer les options :
- permission de la caméra,
- Target Device
- Générer l’APK (Android) et le build Xcode (iOS).

## 9. Files
- Projet : https://drive.google.com/file/d/1iLPFbVvY58tBF0Ef67xr3QLrS5UqqnMd/view?usp=sharing
- Apk : https://drive.google.com/file/d/1h5nGQK7OjdFJr_DfPD9KJ81ciWOSRawH/view?usp=sharing
- demo : https://youtube.com/shorts/2tEMseTpvgs


















