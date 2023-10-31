# Base de données sur la gestion de la pandémie de COVID-19 au Québec

## À propos

Ce dépôt contient deux bases de données (quotidienne et hebdomadaire) portant sur la gestion de la pandémie de COVID-19 au Québec. Ces données ont été collectées par l'équipe de recherche du Pr. Éric Montpetit dans le cadre d'un projet portant sur les politiques publiques mises en oeuvre durant la pandémie. 

De façon générale, ces deux bases de données contiennent des données sur : 

- Les politiques publiques mises en oeuvre (sévérité)
- Les projections d'hospitalisations des experts
- La situation épidémiologique (cas, morts, hospitalisations, vaccination)
- L'opinion publique (soutien aux mesures gouvernementales)
- L'adhésion de la population aux mesures sanitaires fondamentales
- Les sentiments des décideurs (incertitude, sentiments négatifs), ainsi que le niveau de preuve, provenant d'une analyse du langage naturel de l'ensemble des conférences de presse données par le gouvernement durant la pandémie. [Un autre dépôt contient l'ensemble des codes, des données, et des conférences de presse liés ces analyses].(https://github.com/Lemorphic/QC.Uncertainty_COVID)

## Description des données

La base de données quotidienne `QC.COVID_data_daily.csv` et hebdomadaire `QC.COVID_data_weekly.csv` disposent des mêmes noms de variables. 

Ces bases de données sont composées des variables suivantes. Les liens fournies renvoient aux sources primaires des données collectées et assemblées dans ces bases de données.  

   - date/week : Jour ou semaine
   - wave : Vagues de contamination officielle [définies par l'Institut national de santé publique du Québec (INSPQ)](https://www.inspq.qc.ca/covid-19/donnees/ligne-du-temps)
   - SI : Indice de sévérité des mesures sanitaires (interdiction des rassemblements, masques obligatoires, fermeture des écoles, fermeture des restaurants etc.) et des mesures vaccinales (vaccination obligatoire, passeport vaccinal, etc.) [provenant de l'Institut de recherche sur les politiques publiques (IRPP)](https://centre.irpp.org/fr/data/politiques-provinciales-sur-la-pandemie-de-covid-19) et inspiré du [projet international Oxford Covid Government Response Tracker](https://www.bsg.ox.ac.uk/research/covid-19-government-response-tracker).
   - SPHM : Indice de sévérité des mesures sanitaires seules sans les mesures vaccinales [provenant de l'IRPP](https://centre.irpp.org/fr/data/politiques-provinciales-sur-la-pandemie-de-covid-19/)
   - SVAX : Indice de sévérité des mesures vaccinales [provenant de l'IRPP](https://centre.irpp.org/fr/data/politiques-provinciales-sur-la-pandemie-de-covid-19/)
   - UNC : Indice des sentiments d'incertitude exprimés par les décideurs politiques et les représentants de la Santé publique [durant les conférences de presse données durant la pandémie](https://github.com/Lemorphic/QC.Uncertainty_COVID).
   - EVD : Indice du niveau de preuve scientifique exprimés par les décideurs politiques [durant les conférences de presse données durant la pandémie](https://github.com/Lemorphic/QC.Uncertainty_COVID).
   - NEG : Indice des sentiments négatifs au sujet de la pandémie exprimés par les décideurs politiques [durant les conférences de presse données durant la pandémie](https://github.com/Lemorphic/QC.Uncertainty_COVID).
   - SAT1 : Satisfaction de la population sur "la façon dont le gouvernement gère la situation" [provenant du Gouvernement du Québec](https://www.quebec.ca/sante/problemes-de-sante/a-z/coronavirus-2019/rapports-sondages-covid19)
   - SAT2 : Satisfaction de la population faces "aux mesures mises en place pour combattre la pandémie" par le gouvernement du Québec [provenant de la firme de sondages Léger](https://leger360.com/fr/sondages/tracker-nord-americain-de-leger/)
   - ADH1 : Adhésion de la population à trois mesures sanitaires fondamentales (lavage des mains, distanciation physique en société, éviter les rassemblements) [proveant de l'INSPQ](https://www.inspq.qc.ca/covid-19/sondages-attitudes-comportements-quebecois)
   - ADH2 : Adhésion de la population à deux mesures sanitaires fondamentales (lavage des mains, distanciation physique en société) [proveant de l'INSPQ](https://www.inspq.qc.ca/covid-19/sondages-attitudes-comportements-quebecois)
   - PRJ100 : Projections du besoin hospitalier pour la semaine suivante ramenées sur 100 [provenant de l'Institut d'excellence en santé et en services sociaux (INESSS)](https://www.inesss.qc.ca/covid-19/risques-dhospitalisation-et-projections-des-besoins-hospitaliers.html)
   - CC100 : Indice sur 100 du nombre de cas confirmés de COVID-19, [données provenant de l'INSPQ](https://www.inspq.qc.ca/covid-19/donnees).
   - CD100 : Indice sur 100 du nombre de morts confirmées de la COVID-19, [données provenant de l'INSPQ](https://www.inspq.qc.ca/covid-19/donnees).
   - TH100 : Indice sur 100 du nombre d'hospitalisations dues à la COVID-19, [données provenant de l'INSPQ](https://www.inspq.qc.ca/covid-19/donnees).
   - VAX100 : Indice sur 100 du nombre de personnes vaccinées contre la COVID-19, [données provenant de l'INSPQ](https://www.inspq.qc.ca/covid-19/donnees).
   - CC : Nombre brut de cas confirmés de COVID-19, [données provenant de l'INSPQ](https://www.inspq.qc.ca/covid-19/donnees).
   - CD : Nombre brut de morts confirmées de la COVID-19, [données provenant de l'INSPQ](https://www.inspq.qc.ca/covid-19/donnees).
   - TH : Nombre brut d'hospitalisations dues à la COVID-19, [données provenant de l'INSPQ](https://www.inspq.qc.ca/covid-19/donnees).
   - VAX : Nombre brut de personnes vaccinées contre la COVID-19 par jour (données de l'INSPQ, voir ci-dessous)
   - PRJ : Projections brutes du besoin hospitalier pour la semaine suivante ramenées sur 100 [provenant de l'Institut d'excellence en santé et en services sociaux (INESSS)](https://www.inesss.qc.ca/covid-19/risques-dhospitalisation-et-projections-des-besoins-hospitaliers.html)