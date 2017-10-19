# Labeled-DLI32-corpus
DLI32 corpora with language labels for training Automatic Language identification models of written texts.

The files are in json format with reference to the original file, text and detected language as label.

```
{
  "text": "﻿Bonjour,  Voici quelques infos sur un sujet qui me passionne en tant que scientifique (chimiste)  
  Des études ont montré qu'une alimentation ciblée grâce aux conseils d'un médecin nutritionniste est très 
  importante et augmente le taux de survie et la qualité de vie  C'est pourquoi il est important de collaborer 
  avec un médecin nutritionniste qui connait bien l'oncologie (une grande partie d'entre eux travaillent à 
  l'hôpital ou le patient fait son traitement, ou directement dans le département d'oncologie ).  Celui-ci 
  devra absolument collaborer avec l'oncologue.  Il est important de travailler avec lui (et votre oncologue)
  dès l'annonce du diagnostic", 
  "file": "1.txt", 
  "lang": "fr"
 }
```

For more details, read the DLI32.pdf file available online.

Inspired by the following article and repo:

https://github.com/xprogramer/DLI32-corpus

K. Abainia, S. Ouamour and H. Sayoud, "Robust language identification of noisy texts: Proposal of hybrid approaches", International Workshop on Text-based Information Retrieval TIR’14, pp. 228-232.
