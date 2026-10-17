# REMOTE DNA — Politique de confidentialité

[English](./) · [العربية](ar.html) · [Español](es.html) · [Português](pt.html) · [中文](zh.html)

> Ceci est une traduction. En cas de différence, le [texte anglais](./) fait foi.

**Date d’entrée en vigueur :** 18 août 2026 · **Dernière mise à jour :** 17 octobre 2026

REMOTE DNA (« l’Application ») est une télécommande universelle pour téléviseurs
et climatiseurs, publiée par **Solar AI Systems** (Mohamed Khocha), Algérie.

Cette politique décrit exactement ce que l’Application collecte et ne collecte
pas. Elle est tenue à jour avec la version publiée.

## En bref

- Tout ce qu’il faut pour piloter vos appareils fonctionne **hors ligne**, sur
  votre téléphone.
- L’Application fonctionne **sans compte**. Le compte est facultatif et sert
  uniquement à restaurer une licence Pro payée sur un nouveau téléphone.
- Nous ne vendons jamais vos données et ne les utilisons jamais pour des profils
  publicitaires.

## 1. Données conservées uniquement sur votre appareil

Ce qui suit ne quitte jamais votre téléphone :

- Vos appareils enregistrés, leurs jeux de codes et toute touche apprise par
  l’Application (« Apprendre ma télé », « Réparer une touche »).
- Les préférences de langue, de thème et de présentation. Tant que vous n’avez
  pas choisi de langue, l’Application suit celle de votre téléphone, lue sur
  l’appareil.
- Votre clé de licence Pro et votre jeton de connexion (dans l’Android Keystore,
  en stockage chiffré).
- Les données d’appairage Wi‑Fi de vos téléviseurs : la clé qu’un téléviseur LG
  ou Samsung délivre quand vous acceptez la connexion, et pour Android TV un
  certificat client généré dans l’Android Keystore ainsi que l’empreinte du
  certificat du téléviseur. Elles permettent de se reconnecter sans redemander
  et ne servent que sur votre réseau domestique.

Désinstaller l’Application supprime tout cela.

## 2. Compte facultatif

Si — et seulement si — vous créez un compte, nous conservons sur notre serveur :

- Votre **adresse e‑mail**.
- Une **empreinte cryptographique** de votre mot de passe (PBKDF2-HMAC-SHA256).
  Nous ne conservons ni ne voyons jamais votre mot de passe réel.
- La date de création du compte et la licence Pro qui y est liée.

Finalité : restaurer votre licence Pro sur un nouveau téléphone et réinitialiser
votre mot de passe.

Les **e‑mails de réinitialisation** sont envoyés via Resend (resend.com). Seuls
votre adresse e‑mail et un code temporaire à 6 chiffres sont transmis.

Vous pouvez demander la suppression de votre compte à tout moment — voir la
section 8.

## 3. Paiements

Pro est un achat unique. Le mode de paiement dépend de l’endroit d’où vous avez
installé l’Application ; cette section indique le prestataire utilisé dans
chaque cas.

- **Si vous avez installé l’Application depuis Google Play** — le seul moyen
  d’achat intégré est **Google Play Billing**, géré via RevenueCat, qui identifie
  votre achat par un identifiant anonyme. Nous ne recevons aucune donnée de carte.
- **Si vous avez installé l’Application directement depuis notre site** (la
  version distribuée hors Google Play) — le paiement est traité par **Chargily
  Pay** sur sa propre page sécurisée. Vos données de carte sont saisies sur le
  site de Chargily et **ne sont jamais vues, traitées ni conservées par
  l’Application ni par nous**. Chargily nous transmet la référence, le montant et
  le statut de la transaction, et sa propre politique de confidentialité
  s’applique à ce que vous y saisissez. Ce moyen n’est pas proposé dans la version
  Google Play.

Dans les deux cas, nous ne conservons que la référence, le montant, le statut de
la transaction et la clé de licence émise.

## 4. Publicité

La version gratuite affiche des publicités diffusées par **Google AdMob** :

- une **publicité à l’ouverture** de l’Application (jamais au tout premier
  lancement, et au retour de l’arrière‑plan seulement après une longue absence) ;
- de temps en temps une **publicité plein écran entre deux écrans** ;
- une courte **vidéo avec récompense** toutes les trois utilisations de
  « Réparer une touche ».

Deux publicités plein écran sont toujours espacées d’au moins trois minutes. Il
n’y a pas de bannières. Si aucune publicité ne peut s’afficher, l’Application
continue sans elle.

- Les publicités sont demandées avec la **classification « G » (tout public)**
  uniquement, et démarrent **sans le son**.
- Dans l’EEE, au Royaume‑Uni et en Suisse, un **formulaire de consentement
  (Google UMP)** s’affiche avant toute demande de publicité, et votre choix est
  respecté.
- AdMob peut traiter des identifiants de l’appareil pour diffuser les publicités
  et limiter leur fréquence, conformément à la
  [politique de confidentialité de Google](https://policies.google.com/privacy).
- **Les utilisateurs Pro ne voient aucune publicité**, et aucune requête
  publicitaire n’est faite pour eux.

## 5. Contribution facultative de codes (le « réseau génétique »)

Elle est **désactivée par défaut** et exige votre consentement explicite.

Si vous l’activez et choisissez de partager les codes d’un appareil, nous
recevons :

- Le protocole infrarouge, l’adresse et les codes de touches de cet appareil.
- La marque ou le modèle que vous avez saisi, et la version de l’Application.
- Un **identifiant aléatoire généré sur votre appareil à l’installation** — servant
  uniquement à compter les contributeurs distincts, afin de valider les codes à
  la majorité.

Cela ne contient **ni nom, ni e‑mail, ni numéro de téléphone, ni position, ni
identifiant publicitaire**, et ne peut pas être relié à vous. Vous pouvez
désactiver la contribution à tout moment dans les réglages.

## 6. Rapports de plantage

Des rapports de plantage anonymes sont envoyés à **Sentry** (région de données
UE) **uniquement en cas de plantage de l’Application**. Un rapport contient
l’erreur technique, la version de l’Application et le modèle et la version
système de l’appareil. Les informations personnelles sont explicitement
désactivées, et les rapports ne servent jamais à la publicité.

## 7. Autorisations

- `TRANSMIT_IR` — pour émettre des signaux infrarouges via l’émetteur IR de
  votre téléphone. Ce sont des impulsions lumineuses à sens unique, qui ne
  portent aucune information personnelle.
- `CAMERA` — utilisée **uniquement** quand vous choisissez « Importer par QR »
  pour scanner un code de partage, ou « Trouver par modèle » pour lire le numéro
  de modèle sur l’étiquette d’un appareil. Tout est traité sur votre appareil :
  la photo d’une étiquette est **supprimée dès qu’elle a été lue**, et **aucune
  photo ni vidéo n’est conservée ou envoyée**. Vous pouvez la refuser, tout le
  reste continue de fonctionner.
- **Choisir une photo** — dans « Trouver par modèle », vous pouvez aussi choisir
  une photo d’étiquette déjà prise. Le sélecteur de photos d’Android ne donne à
  l’Application que cette photo, sans autorisation de stockage ; elle est lue sur
  votre appareil, la copie faite pour la lecture est supprimée, et rien n’est envoyé.
- `INTERNET` — nécessaire uniquement pour les fonctions facultatives ci‑dessus
  (compte, paiement, publicités, rapports de plantage, mises à jour du
  catalogue). Toutes les fonctions de télécommande marchent réseau coupé.
- **Découverte du réseau local** — quand vous utilisez le contrôle Wi‑Fi,
  l’Application cherche les téléviseurs connectés sur votre propre réseau
  (SSDP/DIAL et mDNS), et quand vous saisissez l’adresse IP d’un téléviseur, elle
  vérifie quels ports de contrôle répondent sur cette seule adresse pour
  reconnaître son système. Elle ne communique qu’avec l’appareil choisi, et ce
  trafic reste dans votre réseau domestique.
- `AD_ID` (identifiant publicitaire) — déclaré par Google AdMob pour les
  publicités décrites à la section 4. Les utilisateurs Pro ne font aucune requête
  publicitaire.

L’Application ne demande **pas** les autorisations micro, position, contacts,
téléphone, SMS ou stockage de fichiers.

## 8. Vos droits et la suppression des données

- **Supprimer les données locales :** désinstallez l’Application, ou effacez ses
  données dans les paramètres Android.
- **Supprimer votre compte et tout ce qui y est lié** (e‑mail, empreinte du mot
  de passe, lien avec la licence) : dans l’Application, ouvrez **Moi → Compte →
  Supprimer définitivement le compte**. L’enregistrement est effacé
  immédiatement — sans demande, sans attente. Une licence Pro payée est
  **dissociée, jamais révoquée** : la clé reste valable et peut être réactivée
  plus tard. Si vous ne pouvez pas accéder à l’Application, écrivez‑nous à
  l’adresse ci‑dessous depuis l’e‑mail du compte et nous l’effacerons sous
  30 jours.
- **Retirer votre consentement à la contribution de codes :** désactivez‑la dans
  les réglages. Les codes déjà partagés sont anonymes et ne peuvent pas être
  reliés à vous.

## 9. Enfants

L’Application est un outil tout public. Elle ne s’adresse pas aux enfants et
nous ne collectons pas sciemment de données les concernant.

## 10. Modifications

Si une future version change ces pratiques, cette politique est mise à jour
**avant** la publication de cette version, et le lien dans l’Application pointe
vers le texte révisé.

## 11. Contact

Questions, demandes de suppression ou toute autre demande :

**solar.ai.systems@gmail.com**

Solar AI Systems — Algérie
