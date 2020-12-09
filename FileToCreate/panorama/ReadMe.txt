0Créer les chiffres avec des 000 devant max (9999) => seulement sur le nom des instances (DAS et Point).
/!\ suppr import toutes les fonctions !

<-- fichier d'import Point -->

column1
(constructeur)/DI = position du fichier

DI_n_n_n = des instances DI
--> pour DEF DI_module_ligne_adresse
--> pour siemsens "DI_ZD" + zone + "_" + adresse
--> pour chubb DI_Tableau_Ligne_AdressePhysique
--> pour finesecure "DI_ZD" + ZONE + "_" + Bus_Adresse

column 2
créer un dossier temporaire pour stocker les fichierszone
/(constructeur)/DI/nomchier/(zone)

column 3
on supprime parametre

suite remplissage avec les infos ne pas oublier le V/
--> Def V/adresse V/libelle V/ligne et V/module
--> Siemens V/zone V/adresse V/parentlibelle V/libelle V/mosbusadresse (libelle = description)
--> Chubb V/tableau V/Ligne V/adressephysique V/registregbus V/libelle V/numzone V/octet V/boucle
--> finesecure V/zone V/bus_adresse V/libelle V/adresse

<-- Di/DAS -->
column 1
(constructeur)/DAS

Das_n_n = des instances DAS
--> DEF DAS_module_adressephysique
--> Siemens DAS_nom
--> Chubb DAS_numerosatellite_adresseDCT
--> finesecure Voie_busnum_Voienum
--> finescure Mdlo : DAS_Busnum_voienum_mdlonum


column 2
créer un dossier temporaire pour stocker les fichierszone
/(constructeur)/DAS/nomchier/

column3
--> Comme le premier on recup les valeurs get par les parseurs.

<-- Funtion -->
column 1
(constructeur)/FONCTION

--> Function nom instance
--> Chubb FONCTION _ 'numero'
--> DEF séparé en 2 types de fonction attention a mettre les deux séparateur dinstance fonction et fonctionevac
- FONCTION_'adresselogique'
--> Finesecur séparé en 2 types de fonction attention a mettre les deux séparateur dinstance fonction et fonction_UGA
-FONCTION_'numero'_'racknumero'
--> Siemens séparé en 2 types de fonction attention a mettre les deux séparateur dinstance fonction et fonction_UGA
-FontionUGA_'adressemodbus'
-Fontion_'adressemodbus'

column2
/(constructeur)/Fonction/nomufichier/FCT
/(constructeur)/Fonction/nomufichier/FCTUGA

column3+
--> Comme le premier on recup les valeurs get par les parseurs.
