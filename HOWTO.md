Comment soutenir une thèse au LAAS?
-----------------------------------

Voici un petit résumé de comment ça s'est passé pour moi avec pleins
d'informations plus ou moins en vrac.


0. Contexte
===========

Voici mon contexte. Selon votre établissement et votre école doctorale,
la marche à suivre peut changer.

 * Laboratoire/Groupe de recherche: LAAS, RIA, GEPETTO
 * Établissement: INP Toulouse
 * École doctorale: EDSYS


1. Rédaction
============

COMMENCEZ PAR LIRE CECI:
 - http://www.laas.fr/1-28834-Modalites-de-soutenance-de-these.php
 - http://www.scd.ups-tlse.fr/scd/guide_these.pdf
 - http://www.inp-toulouse.fr/fr/formation-initiale-1/choisir-sa-formation/doctorats.html

Mon PC a rendu l'âme 2 heures après avoir envoyé mon manuscrit à mes
rapporteurs pour relecture, utilisez Git, ça peut sauver votre thèse
;)

J'ai utilisé LateX (book), gimp, inkscape. Rédigez vite le texte, tout
le contenu sans mise en page (ou le minimum, par exemple itemize et
textbf). Idem pour les formules, faite au minimum car vous ne savez
pas si elle survivra à la fin de la rédaction. Une fois le contenu
rédigé, la majeure partie du travail est fait...

Utilisez un correcteur orthographique. Le minimum syndical s'appelle
ispell et est disponible sous Linux. Les utilisateurs d'emacs peuvent
également utiliser Flyspell qui permet d'intégrer ispell à emacs.
Pour ma part j'ai investi dans Antidote, un correcteur plus évolué
fonctionnant sous Linux/Mac/Windows
(http://www.druide.com/antidote.html).

Relisez-vous, supprimez les parties inutiles, corrigez le français,
etc.

J'ai ensuite réalisé les figures en tikz (ou plutôt recyclé des
figures d'anciens articles). Soignez les figures de vos articles et
réalisez-les en vectoriel (Inkscape ou Tikz). Cela vous sauvera un
jour ou l'autre... et gardez les sources de vos articles sous Git pour
pouvoir les retrouver plus tard.

Une thèse prend beaucoup de temps à compiler. Compilez les chapitres
dans des pdf séparés. Demandez de l'aide autour de vous pour la
relecture de chaque chapitre. Une fois que tout est prêt, vérifiez la
mise en page et envoyez le manuscrit final à votre directeur de thèse
pour avoir ses commentaires et sa validation.

La rédaction initiale m'a pris environ 1 mois et demi de
travail. L'intégration des commentaires des relecteurs et la
correction de problèmes supplémentaires détectés après coup m'a pris 2
semaines environ. Puis deux semaines sur les slides plus une semaine
de répétition et soutenance! Mes slides sont également disponibles et
ont été réalisées avec Beamer.


Concernant les slides: n'ayez pas peur, LACHEZ-VOUS! ;)
Un peu d'inspiration:
-http://www.slideshare.net/jessedee/steal-this-presentation-5038209
- http://www.slideshare.net/slide_ware/why-presentations-suck
- http://www.slideshare.net/ethos3/mr-presentation
- http://www.slideshare.net/EmilandDC/7-tips-to-create-visual-presentations
- http://www.slideshare.net/otikik/how-to-make-awesome-diagrams-for-your-slides

Dans mon cas:
 - 2 jours: choix des slides (avec un papier et un crayon)
 - 2 jours: choix des couleurs, des images pour le thème de base
 J'ai utilisé flick, istockphoto.com, et phototheque.cnrs.fr
 Achetez des images, la qualité n'étant quand même pas comparable...
- 4 jours: création des figures et du contenu
- relecture


PS: Quelque soit votre niveaux en LaTeX, travaillez avec
http://tex.stackexchange.com Ne perdez pas de temps sur vos problèmes
LateX. Si vous posez une question sur le site, elle trouvera une
réponse dans la demi-journée qui suit. Vous aurez le temps de
continuer à rédiger pendant ce temps...

PPS: ma gestion bibliographique est réalisée avec Mendeley
(http://www.mendeley.com/).


2. Les étapes
=============

Choisissez votre jury le plus rapidement possible, ainsi que la date
de la soutenance finale.

 * 21 mai: début de l'écriture, définition du plan, des rapporteurs.
 * début juin: envoi d'un mail aux rapporteurs pour leur proposer de relire le manuscrit.
 * mi-juin: rapporteurs OK
 * mi-juillet: envoi du manuscrit au rapporteur (pensez à leur demander s'ils souhaitent
qu'on leur envoie une version papier)
 * mi-juillet à mi-août: relecture du manuscrit par les rapporteurs, choix des autres membres du jury.
 * fin août: première passe de correction et envoi du manuscrit aux autres membres du jury.
 * début septembre: écriture des slides, répétitions.
 * 17 septembre: soutenance.
 * Après la soutenance, décompression ;) et deuxième passe de correction. Et enfin, dépôt du manuscrit.

3. Les étapes administratives
=============================

COMMENCEZ PAR LIRE CECI:
http://www.adum.fr/as/ed/edsys/page.pl?page=puSoutenance

0. Mettez à jour votre profil EDSYS, vérifiez que vous êtes à jour
dans vos formations, entrez-les dans le site ADUM. Idem pour les
papiers scientifiques.

1. Choix du jury. Vérifiez bien que le jury que vous allez proposer
respecte les différentes règles (HDR, parité professeur, chercheur,
etc.).

2. Remplissez le dossier de soutenance sur le site d'EDSYS (à faire dès que possible).

3. Vérifiez quand le dossier passe en commission. Une fois la
commission passée que le dossier a bien été envoyé à l'INPT et que
l'INPT a bien reçu le dossier (ne pas hésiter à se déplacer...).  Le
dossier de soutenance est ensuite renvoyé au directeur de
thèse. Vérifier que cela a bien été fait!

4. Soutenance. Vérification du PV de soutenance, du rapport et de
l'autorisation de reproduction (trois documents distincts).

5. Il faut ensuite donner ces documents au service doc/édition du
LAAS. C'est ensuite au doctorant d'aller porter son manuscrit final
sur CD-ROM (un seul document sur le CD, le PDF avec la bonne
couverture pour la thèse, disponible sur mon compte Git). Ne pas
oublier résumé en français, anglais et les mos-clés.

Note: la meilleure façon de recréer la couverture des thèses est de
prendre le template disponible sur le site du PRES ou sur ce compte
Git, de le remplir dans Acrobat Reader, d'imprimer le PDF rempli en
PDF (cf cups-pdf sous Ubuntu) et d'insérer le PDF rempli avec
includegraphics en LateX.

6. Envoyez ou portez le document à l'INPT. Si c'est nécessaire pour la
suite, demander une attestation de réussite. Les deadlines pour les
post-doc peuvent parfois être très courtes!
