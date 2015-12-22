# Fiche descriptive du cours : Signature Electronique Sécurisée
## Enseignant : Benoit LEGER-DERVILLE

### Prérequis : Cours de Cryptologie (cryptographie symétrique et asymétrique de niveau au moins débutant) [Sinon les aspects cryptos sont embraqués dans le cours].

## Objectifs, Résumé du cours ou de l'activité pédagogique
Ce cours propose d’appréhender les difficultés inhérentes à la mise en œuvre de la signature électronique au sein de projets réels à grande échelle.

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
a) Introduction - utilisation de OpenSSL
-  objectifs : appréhender l'utilisation de la signature avec OpenSSL
(PKCS#1, RFC 5280, ASN1, XMLDSIG, C14N, XAdES et XMLDSIG)
-  Travail élève : devenir autonome avec OpenSSL en 1h30
b) Rappels Cryptographiques
-  objectifs : appréhender l'utilisation de la signature avec OpenSSL
(PKCS#1, RFC 5280, ASN1, XMLDSIG, C14N, XAdES et XMLDSIG)
-  Travail élève : devenir autonome avec OpenSSL en 1h30
c) Formats des fichiers - Analyse détaillée d'un certificat cryptographique de signature
- objectifs : appréhender la complexité technique de la mise en oeuvre de la signature électronique sécurisée
-  Travail élève : utiliser une application de création de signature (sécurisée)
d) Signature électronique au format XAdES
- objectifs : appréhender la complexité technique de la mise en oeuvre de la signature électronique sécurisée
-  Travail élève : analyse du format XAdES : comment vérifier une signature électronique sécurisée

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


 
Secure Electronic Signature 
Secure Digital Signature 

Managing Instructor :	 Benoit LEGER-DERVILLE 
Objectives, Course or academic activity summary
This course is about understanding the difficulties inherent in the implementation of electronic (or digital) signature in real large-scale projects.

One of the main purpose is to make students aware about the complexity of organizational, legal and cultural aspects of effective digital signature implementation, despite its theoretical security level (cryptography).

Initially and after a few cryptographic reminders, the goal as well as technical and organizational principles of the digital signature are presented to the students. Then is exposed the body of rules leading to the secure digital signature in there detailing all organizational (PKI authority, certification practice statement and provider certification) and technical aspects (HSM, SSCD, international standards, signature verification application, RGS, others).

The practical benefits offered to students are the understanding of the complex and vulnerable set of works (practical work), the use of a rich but but unfamiliar body of standards, the synthesis of the main legal texts and especially the awareness of widespread ignorance of what represents the interests of the digital signature within companies themselves.

Contents, course overview (or teaching subject activity)
Part 1: Introduction
- Reminders on digital signatures (asymmetric cryptography, hash functions, PKI, certificates).
- Introduction on the legal context (laws and regulations).
Part 2: Apprehension of the legal context of the digital signature
- The legal context.
- The standardized digital signatures formats.
Part 3: Case of the secure digital signature.
- Legal / Practical / Technical aspects.
Part 4: The Secure Signature Creation Devices (norms and standards)
- The normative aspects of SSCD and HSM.
- The available hardware and solutions.
Part 5 : Tuorial : « Implementation of the Secure Digital Signature »
a) Intro - OpenSSL command line tool
-  Goals : understanding electronic signature with OpenSSL 
(PKCS#1, RFC 5280, ASN1, XMLDSIG, C14N, XAdES and XMLDSIG)
-  Students work : become self-sufficient with OpenSSL in 1h30
b) Cryptographic reminder
-  Goals : understanding electronic signature with OpenSSL 
(PKCS#1, RFC 5280, ASN1, XMLDSIG, C14N, XAdES and XMLDSIG)
-  Students work : become self-sufficient with OpenSSL in 1h30
b) File formats - Detailed analysis of a digital certificate
- Goals : understanding the technical complexity of implementing advanced electronic signature
-  Students work : use of a signature creation application
d) XAdES digital signature
- Goals : understanding the technical complexity of implementing advanced electronic signature
- Students work : XAdES analysis : how to verify an advanced digital signature

Part 6: Real case study :
Signature Fail! Why is this not working? New coming EU regulations.
- Digital vital records - ANTS
- MINOS - Ministry of Justice - DPICA - ANTS
- PVe (electronic parking fines) - DPICA

References and Bibliography :
Texts and laws – normative corpus
- EU Directive 1999/93/EC: equivalence between digital signatures and handwritten signatures and free movement of digital certification services in Europe.
- Act No. 2000-230 of 13 March 2000 adapting the law of evidence to information technologies.
- Decree No. 2001-272 of 30 March 2001 for the application of Article 1316-4 of the Civil Code related to digital signatures. Smart card that meets the requirements of the decree of March 30, 2001, § I.1 (certified in SSCD Protection Profile). Certificates issued by a PSCE meeting the requirements of the decree of March 30, 2001, § III.2 and 3 (Certified to AFNOR Z74-400 requirements and the Order of 26 July 2004 (hardware and procedures)).
- Order of May 6, 2010 approving the RGS (General Security Repository) and specifying the modalities for digital certificates validatiion procedures.
Books and references:
- Sécurité de la dématérialisation (De la signature électronique au coffre-fort numérique, une démarche de mise en oeuvre): Dimitri MOUTON
- Summary on the Secure Digital Signature (internal document Stelau Conseil)
- Securing digital communication with a PKI (Authors: Laurence Bellefin, Marie-Laure Laffaire, Thierry Autret - Publisher: Eyrolles)
- Cryptography and digital signatures: legal aspects (Authors): Alain Bensoussan, Sylvain Martin, Isabelle Pottier)


