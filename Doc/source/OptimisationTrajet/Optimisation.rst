

Partie Algorithme d'optimisation
==================================

Dans cette partie le but recherché est de permettre de calculer le prix le moins cher entre deux sorties d'autoroutes selon un nombre maximum de sorties intermédiaires.
Par exemple un utilisateur qui voudrait aller de Montpellier est à Carcassone ouest et qui souhaiterait réaliser un maximum de 3 sorties intermédiaires peut utiliser notre 
programme python qui lui permettra de savoir où sortir pour minimiser le coût du trajet. Sous la contrainte de 3 sorties maximum, il se peut que le trajet demandé soit 
minimal en moins de 3 sorties et cela sera détaillé l'output de notre programme.

Ce programme est fait pour être utilisé facilement nous avons regrouppé toutes les fonctionnalités du package dans une seule fonction qui une fois executée
permet de faire apparaitre des widgets interractifa et de choisir, parmi les sorties disponibles, un point d'entrée et un point de sortie de l'autoroute.
Le widget du nombre de sorties ne concerne que l'opimisation du trajet car elle vous permet de choisir combien de sorties intermédiaires maximum que vous souhaitez réaliser
pendant votre trajet.

Il vous suffit donc d'executer la fonction ``Optimisation_trajet`` pour faire apparaître les widgets et plannifier votre trajet. 

.. danger::
 Attention seules les sorties qui vous sont proposées sont valides. Il n'est pas possible par exemple d'optimiser le trajet entre Nîmes ouest et Perpignan nord.
 Attention également à vérifier que les points d' entrée/sorties soient valides. Par exemple il est impossible d'aller de Pamiers Nord à Pamiers Sud et de Pamiers Sud 
 à Pamiers Nord. Si vous obtenez un message d'erreur il est très probable que le problème vienne de là. Une autre source d'erreur est celle de demander un nombre trop 
 grand de sorties intermédiares. Nous vous prions donc d'entrer un nombre de sorties adapté à votre trajet au rique de rencontrer un message d'erreur.

  


Exemple d'utilisation 
=====================

.. figure:: opti_trajet.gif
   :height: 400
   :width: 700
   :scale: 70
   :align: center
   :class: with-shadow
   :alt: OptimisationTrajet

