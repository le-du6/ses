# Signature Electronique Sécurisée
## Fiche descriptive du cours

## Enseignant : Benoit LEGER-DERVILLE

### Prérequis : Cours de Cryptologie
(cryptographie symétrique et asymétrique de niveau au moins débutant)
*[Sinon les aspects cryptos sont embraqués dans le cours]*

## Objectifs du cours
Ce cours propose d’appréhender les difficultés inhérentes à la mise en œuvre de la signature électronique au sein de projets réels à grande échelle (les radars automatiques, la verbalisation électronique, le passeport biométrique et la sécurisation des données de l'état civil).

L’un des objectifs est de faire prendre conscience aux élèves de la complexité des aspects organisationnels, juridiques et culturels d’une mise en œuvre effective de la signature électronique, malgré son niveau de sécurité technique théorique (cryptographique).

Dans un premier temps, et après quelques rappels cryptographiques, la finalité ainsi que les principes techniques et organisationnels de la signature électronique sont présentés. On expose ensuite le corpus réglementaire menant à la signature électronique sécurisée en y détaillant l’ensemble des aspects organisationnels (autorité, politique et prestataire de certification) et techniques (HSM, SSCD, nomes, application de vérification de signatures, RGS, autres).

Les apports concrets proposés aux élèves sont la présentation du caractère complexe et vulnérable des mises en œuvres (travaux pratiques), l’utilisation d’un corpus normatif riche mais peu connu, la synthèse des textes principaux et surtout la prise de conscience d’une méconnaissance généralisée de ce que représente l’intérêt de la signature électronique au sein des entreprises elles-mêmes.

## Contenu, plan du cours

Partie 1 : Introduction
- Rappels sur la signature électronique (cryptographie asymétrique, hachage, IGC, certificats).
- Introduction au contexte légal (lois et règlements).

Partie 2 : Appréhension du contexte juridique de la signature électronique
- Le contexte légal.
- Les formats de signature normalisés.

Partie 3 : Cas particulier de la signature électronique sécurisée.
- Aspects juridiques / Aspects organisationnels / - Aspects techniques.

Partie 4 : Les dispositifs de création de signature (normes et standards)
- Les aspects normatifs des SSCD et HSM.
- Les matériels et les solutions disponibles.

Partie 5 : Travaux Pratiques : « Mise en oeuvre de la Signature Electronique Sécurisée »
a) Introduction
Utilisation de OpenSSL
objectifs : appréhender l'utilisation de la signature avec OpenSSL *(PKCS#1, RFC 5280, ASN1, XMLDSIG, C14N, XAdES et XMLDSIG)* Travail élève : devenir autonome avec OpenSSL en 1h30
b) Rappels Cryptographiques
objectifs : appréhender l'utilisation de la signature avec OpenSSL
(PKCS#1, RFC 5280, ASN1, XMLDSIG, C14N, XAdES et XMLDSIG)
travail élève : devenir autonome avec OpenSSL en 1h30
c) Formats des fichiers
Analyse détaillée d'un certificat cryptographique de signature
objectifs : appréhender la complexité technique de la mise en oeuvre de la signature électronique sécurisée
travail élève : utiliser une application de création de signature (sécurisée)
d) Signature électronique au format XAdES
objectifs : appréhender la complexité technique de la mise en oeuvre de la signature électronique sécurisée
travail élève : analyse du format XAdES : comment vérifier une signature électronique sécurisée

## Partie 6 : Retours d’expériences réels :
Signature Fail ! Pourquoi cela ne fonctionne pas bien ? Les nouvelles normes européennes en préparation.
- Dématérialisation des transferts de l’état civil - ANTS
- Projet MINOS – Ministère de la Justice – DPICA – ANTS
- Projet PVe (Procès-verbal électronique) – DPICA

### Références et Bibliographie
Textes et lois - Corpus normatif
- Règlement Européen eIDAS.
- Directive européenne 1999/93/CE : principe d’équivalence entre la signature électronique et la signature manuscrite et libre circulation des services de certification électronique en Europe.
- Loi n°2000-230 du 13 mars 2000 portant adaptation du droit de la preuve aux technologies de l’information.
- Décret n° 2001-272 du 30 mars 2001 pour l’application de l’article 1316-4 du code civil et relatif à la signature électronique. Carte à puce répondant aux exigences du décret du 30 mars 2001, § I.1 (Certifiée conforme au Profil de Protection SSCD). Certificat délivré par un PSCE répondant aux exigences du décret du 30 mars 2001, § III.2 et 3 (Certifié conforme à la norme AFNOR Z74-400 et Exigences de l’Arrêté du 26 juillet 2004 (matériel et procédures)).
- Arrêté du 6 mai 2010 portant approbation du référentiel général de sécurité et précisant les modalités de mise en œuvre de la procédure de validation des certificats électroniques.

### Ouvrages et références :
- Sécurité de la dématérialisation (De la signature électronique au coffre-fort numérique, une démarche de mise en oeuvre): Dimitri MOUTON
- Synthèse sur la Signature Electronique Sécurisée (document de capitalisation interne de Stelau Conseil)
- Sécuriser ses échanges électroniques avec une PKI (Auteur(s) : Laurent Bellefin , Marie-Laure Laffaire , Thierry Autret - Editeur : Eyrolles)
- Cryptologie et signature électronique : aspects juridiques (Auteur(s) : BENSOUSSAN Alain, MARTIN Sylvain, POTTIER Isabelle)



