# Base de données sur la gestion de la pandémie de COVID-19 au Québec

## À propos (English below)

Ce dépôt contient deux bases de données (quotidienne et hebdomadaire) portant sur la gestion de la pandémie de COVID-19 au Québec. Ces données ont été collectées par l'équipe de recherche du Pr. Éric Montpetit dans le cadre d'un projet portant sur les politiques publiques mises en oeuvre durant la pandémie dans la province de Québec, Canada. 

De façon générale, ces deux bases de données contiennent des données sur : 

- Les politiques publiques mises en oeuvre (sévérité)
- Les projections d'hospitalisations des experts
- La situation épidémiologique (cas, morts, hospitalisations, vaccination)
- L'opinion publique (soutien aux mesures gouvernementales)
- L'adhésion de la population aux mesures sanitaires fondamentales
- Les sentiments des décideurs (incertitude, sentiments négatifs) ainsi que le niveau de preuves scientifiques [provenant d'une analyse du langage naturel de l'ensemble des conférences de presse données par le gouvernement du Québec durant la pandémie. Un autre dépôt contient à cet égard l'ensemble des codes, des données, et des conférences de presse liés ces analyses](https://github.com/Lemorphic/QC.Uncertainty_COVID).

## Description des données

La base de données quotidienne `QC.COVID_data_daily.csv` et hebdomadaire `QC.COVID_data_weekly.csv` disposent des mêmes noms de variables. 

Ces bases de données sont composées des variables suivantes (les liens fournis renvoient aux sources primaires des données collectées et assemblées dans les deux bases de données) :

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

## Membres du projet

[Éric Montpetit](https://pol.umontreal.ca/repertoire-departement/professeurs/professeur/in/in14714/sg/%C3%89ric%20Montpetit/), département de science politique, Université de Montréal.

[Antoine Lemor](https://pol.umontreal.ca/repertoire-departement/charges/charge-de-cours/in/in35295/sg/Antoine%20Lemor/), département de science politique, Université de Montréal.

[Maria Alejandra Costa](https://www.linkedin.com/in/mar%C3%ADa-alejandra-costa-37065442/?locale=en_US), département de science politique, Université de Montréal.

[Louis-Robert Beaulieu-Guay](https://scholar.google.com/citations?user=LvgfEn0AAAAJ&hl=fr), département de science politique, Université de Montréal.


## À venir

Mise à jour des bases de données avec de nouveaux indices de perceptions de la population provenant de l'INSPQ, ainsi que d'indices provenant [de nouvelles analyses du langage naturel des conférences de presse.](https://github.com/Lemorphic/QC.Uncertainty_COVID)


# Database on the Management of the COVID-19 Pandemic in Quebec

## About

This repository contains two databases (daily and weekly) on the management of the COVID-19 pandemic in Quebec. These data were collected by the research team of Prof. Éric Montpetit as part of a research project on the public policies implemented during the pandemic.

These two databases contain data on:

- Public policies implemented to fight the pandemic (stringency)
- Experts' hospitalization projections
- The epidemiological situation (cases, deaths, hospitalizations, vaccination)
- Public opinion (support for government measures)
- The population's adherence to fundamental sanitary measures
- The sentiments of policymakers (uncertainty, negative sentiments), as well as the level of evidence, [coming from a comprehensive NLP analysis of all the press conferences given by the government of Quebec during the pandemic. Another repository contains all the codes, data, and press conferences related to these analyses.](https://github.com/Lemorphic/QC.Uncertainty_COVID)

## Data Description

The daily database `QC.COVID_data_daily.csv` and the weekly database `QC.COVID_data_weekly.csv` have the same variable names.

These databases are composed of the following variables (the provided links hereafter refer to the primary sources of the data collected and assembled in these databases) :

   - date/week: Day or week
   - wave: Official contamination waves [defined by the Quebec National Institute of Public Health (INSPQ)](https://www.inspq.qc.ca/covid-19/donnees/ligne-du-temps)
   - SI: Stringency Index of sanitary measures (ban on gatherings, mandatory masks, school closures, restaurant closures, etc.) and vaccine measures (mandatory vaccination, vaccine passport, etc.) [from the Institute for Research on Public Policy (IRPP)](https://centre.irpp.org/fr/data/politiques-provinciales-sur-la-pandemie-de-covid-19) and inspired by the [international Oxford Covid Government Response Tracker project](https://www.bsg.ox.ac.uk/research/covid-19-government-response-tracker).
   - SPHM: Stringency Index of sanitary measures alone without vaccine measures [from the IRPP](https://centre.irpp.org/fr/data/politiques-provinciales-sur-la-pandemie-de-covid-19/)
   - SVAX: Stringency Index of vaccine measures [from the IRPP](https://centre.irpp.org/fr/data/politiques-provinciales-sur-la-pandemie-de-covid-19/)
   - UNC: Index of uncertainty sentiments expressed by political decision-makers and public health representatives [during press conferences given during the pandemic](https://github.com/Lemorphic/QC.Uncertainty_COVID).
   - EVD: Index of the level of scientific evidence expressed by political decision-makers [during press conferences given during the pandemic](https://github.com/Lemorphic/QC.Uncertainty_COVID).
   - NEG: Index of negative sentiments about the pandemic expressed by political decision-makers [during press conferences given during the pandemic](https://github.com/Lemorphic/QC.Uncertainty_COVID).
   - SAT1: Population satisfaction with "the way the government is handling the situation" [from the Government of Quebec](https://www.quebec.ca/sante/problemes-de-sante/a-z/coronavirus-2019/rapports-sondages-covid19)
   - SAT2: Population satisfaction with "the measures put in place to fight the pandemic" by the Quebec government [from the Léger polling firm](https://leger360.com/fr/sondages/tracker-nord-americain-de-leger/)
   - ADH1: Population adherence to three fundamental sanitary measures (hand washing, physical distancing in society, avoiding gatherings) [from the INSPQ](https://www.inspq.qc.ca/covid-19/sondages-attitudes-comportements-quebecois)
   - ADH2: Population adherence to two fundamental sanitary measures (hand washing, physical distancing in society) [from the INSPQ](https://www.inspq.qc.ca/covid-19/sondages-attitudes-comportements-quebecois)
   - PRJ100: Experts' projections of hospitalizations for the following week scaled to 100 [from the Institute for Excellence in Health and Social Services (INESSS)](https://www.inesss.qc.ca/covid-19/risques-dhospitalisation-et-projections-des-besoins-hospitaliers.html)
   - CC100: Index (out of 100) of the number of confirmed COVID-19 cases, [data from the INSPQ](https://www.inspq.qc.ca/covid-19/donnees).
   - CD100: Index (out of 100) of the number of confirmed COVID-19 deaths, [data from the INSPQ](https://www.inspq.qc.ca/covid-19/donnees).
   - TH100: Index (out of 100) of the number of COVID-19 hospitalizations, [data from the INSPQ](https://www.inspq.qc.ca/covid-19/donnees).
   - VAX100: Index (out of 100) of the number of people vaccinated against COVID-19, [data from the INSPQ](https://www.inspq.qc.ca/covid-19/donnees).
   - CC: Raw number of confirmed COVID-19 cases, [data from the INSPQ](https://www.inspq.qc.ca/covid-19/donnees).
   - CD: Raw number of confirmed COVID-19 deaths, [data from the INSPQ](https://www.inspq.qc.ca/covid-19/donnees).
   - TH: Raw number of COVID-19 hospitalizations, [data from the INSPQ](https://www.inspq.qc.ca/covid-19/donnees).
   - VAX: Raw number of people vaccinated against COVID-19 per day (data from INSPQ, see below)
   - PRJ: Raw projections of hospital needs for the following week scaled to 100 [from the Institute for Excellence in Health and Social Services (INESSS)](https://www.inesss.qc.ca/covid-19/risques-dhospitalisation-et-projections-des-besoins-hospitaliers.html)

## Project Members

[Éric Montpetit](https://pol.umontreal.ca/repertoire-departement/professeurs/professeur/in/in14714/sg/%C3%89ric%20Montpetit/), Department of Political Science, University of Montreal.

[Antoine Lemor](https://pol.umontreal.ca/repertoire-departement/charges/charge-de-cours/in/in35295/sg/Antoine%20Lemor/), Department of Political Science, University of Montreal.

[Maria Alejandra Costa](https://www.linkedin.com/in/mar%C3%ADa-alejandra-costa-37065442/?locale=en_US), Department of Political Science, University of Montreal.

[Louis-Robert Beaulieu-Guay](https://scholar.google.com/citations?user=LvgfEn0AAAAJ&hl=fr), Department of Political Science, University of Montreal.


## Coming Soon

Updating the databases with new indices of perceptions of the population during the pandemic (fear, etc.) from the INSPQ, as well as new indices from [natural language analyses of press conferences.](https://github.com/Lemorphic/QC.Uncertainty_COVID)
