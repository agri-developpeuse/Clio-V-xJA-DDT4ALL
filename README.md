# Clio-V-xJA-DDT4ALL
Documentation de DDT4ALL / RenOLink pour Clio 5 (xJA) 2021


## introduction
Voici la documentation que j'ai pu creer à partir de mon experience personelle avec DDT4ALL et RenOLink sur ma Clio 5. 
Les deux logiciels sont assez intuitifs, mais les fichiers de modification des calculateurs peuvent être un peu difficiles à comprendre. 


## DISCLAIMER !! 
Attention, chaque voiture est différente, donc ce qui fonctionne chez moi ne fonctionnera pas forcément chez vous et inversement. Assurez-vous de faire un scan de votre voiture pour que les logiciels utilisent bien les fichiers adaptés à votre configuration materielle. De manière générale, ne modifiez aucune option dont vous ne connaissez pas précisément l'utilité. Je ne pourrai en aucun cas être tenue responsable en cas de dommage sur votre véhicule.


## Sécurité
Pour que la connexion entre les logiciels et votre véhicule fonctionne, il faudra contourner la gateway qui bloque l'accès en ecriture sur le canBus de la voiture. Il y'aura peut-être un tutoriel à l'avenir, pour le moment essayez de vous renseigner sur internet, la question à déja été abordée de nombresuses fois, vous devriez trouver assez facilement.


## Liste des calculateurs et utilité
Voici la liste des calculateurs présents dans ma voiture ainsi que leur utilité : 

| Module | Nom du fichier | Utilité |
| :---- |:----| :----|
| Navigation-UCC-ITM | A-IVI v1.11 | Eazylink (branche 2 chez moi) |
| EPS | CMFB_CEPS_TKP_V4_13 | Pas testé |
| Parking Sonar | USA_CMFB_V_3_3 | Radar de recul |
| UCH | C1A_BCM_DDT_8_2_0 | Programation des options |
| UPC-EMM | DDT_USM_C1A_BR2_SW65 | Gestion batterie / start&stop etc... |
| HVAC | CAMAN_up_CMFB_C1A_DENSO_BJA_PP_V5.5 | Gestion climatisation / ventilation |
| FRRAD | RADAR_C1A_LS_V5.5 | Radar avant (distances de securité) |
| Airbag-SRS | RSA_C1A_ACU_CONTINENTAL_V5_3 | Calculateur des airbags !! DANGER NE PAS TOUCHER !! |
| TDB | Cluster_C1A_RUN2_V2.20 | Tableau de bord / icockpit |
| MIU | Central Panel CMFB_CDp2_7_9.3_20220902 | Panneau de contrôle ventilation ? pas testé |
| FCAM | FrontCamera_C1A_V3.20 | Caméra du pare-brise avant (detection des lignes / panneaux) |
| DCM Renault | TCU_AIVC_v2.29 | Pas testé |

La communication se fait exclusivement en DiagOnCAN à 500 kbps (pas besoin d'utiliser les autres protocoles lors du scan).



