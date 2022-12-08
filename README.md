# Lassa fever time to diagnosis

## Motivation

Lassa fever is a viral haemorrhagic fever with a case fatality rate among severe cases estimated at 16.5%. The majority of infections (80%) are thought to lead to asymptomatic illness. Those that seek medical care following development of severe symptoms have generally poor outcomes with high morbidity and mortality. Treatment options are limited with Ribavarin the only approved treatment for this viral illness with concerns raised about the efficacy of treatment and the optimal timing of intervention, supportive care is therefore the mainstay of treatment in confirmed cases. Initial symptoms of Lassa fever are typically fever, malaise and loss of appetite with cardinal signs of clotting dysfunction and liver function derangement later sequelae of infection. The lack of distinguishing signs and symptoms at early stages of infection leads to potential misdiagnosis of acute Lassa fever as a parasitic (i.e. malaria), bacterial (i.e. bacterial pneumonia) or other viral infection in a region with a wide range of endemic infectious diseases. The lack of point-of-care diagnostics and limited availability likely contributes to misdiagnosis and delay of treatment in Lassa fever cases. 

## Data extraction

To quantify the delay from presentation with symptoms to confirmation or suspicion of Lassa fever a systematic search of the literature and published case reports was conducted. The following search terms were used to identify suitable records in OVID Medline and Web of Science.

  1. Lassa fever OR Lassa mammarenavirus
  2. Case-control OR Cohort OR Case series OR Case report OR Observational OR Randomised Controlled Trial OR Cross-Sectional
  3. Epidemiological OR Epidemiology
  4. 1 AND (2 OR 3)
  
MEDLINE (2022-12-07) - 478 records

Additionally searches were performed on PROMED, WHO Outbreak Reports and the Nigeria Centre for Disease Control for individual level data.

Studies were included if they included data on date of symptom onset and date of clinical suspicion or date of confirmation of *Lassa mammarenavirus* infection. Where studies did not report individual level data corresponding authors were contacted to explore data sharing opportunities. If data remained unavailable and studies report aggregated values for time between symptom onset and confirmation of case status individual values were simulated mean and standard deviation or median and interquartile range as appropriate assuming a normal distribution (unless otherwise indicated).

Participants/populations: Individuals regardless of age with confirmed or suspected Lassa fever using the following case definition.

Case definition of Lassa fever will follow NCDC National guidelines for the management of LF, 2018.

Confirmed LF: any criteria for suspected LF AND positive Lassa RT-PCR from any body fluid.

Suspected Lassa fever will be defined as:
History of fever (body temperature measured above 38°C more than 24 hours without the use of antipyretics) beginning 3 to 21 days prior to presentation, with one or more of the following conditions: 
  + Abdominal pain
  + Vomiting
  + Diarrhoea
  + Sore throat
  + Myalgia
  + Generalized body weakness
  + Abnormal bleeding (mucosal bleeding, punctures sites bleeding, uncontrolled intra operational and/or immediate post operational bleeding).

OR

Neonates (with or without signs and symptoms) from women infected by Lassa virus. 

The following reinforce the index of suspicion.
  + Absence of response to standard anti-malaria treatment and treatment for other common infectious causes of fever within 48-72 hours.
  + History of recent contact with a probable or confirmed case of LF within 21 days of onset of fever.
  + History of recent travel to high risk/burden area of LF within 21 days of onset of fever.
  + Contact with body fluids or tissues of a dead patient with a febrile illness, symptoms and signs highly suggestive of LF leading to death within 21 days of onset of fever. 
  
Intervention or exposure: Not assessed but will be recorded if available for descriptive purposes.

Comparator or control: Not extracted

Main outcome: Time do diagnosis from first symptom onset.

Additional outcome: Outcome of illness, i.e. death or reported morbidity.

Studies will be managed using Zotero reference manager with data extracted into a Google Sheet document. All data cleaning and processing will be conducted using the R statistical programming language with reproducible code stored in a GitHub repository. Titles and/or abstracts of records will be screened and selected using the eligibility criteria. 

Data will be extracted on 1) country where infection occurred, 2) country where suspicion/confirmation was made, 3) date of symptom onset, 4) date of clinical suspicion, 5) date of confirmation, 6) method of confirmation, 7) outcome of illness, 8) patient characteristics, treatment and study information.

Risk of bias assessment:

Bias in the ascertainment of symptom onset will not be possible to assess from included studies as effort in obtaining accurate dates from patients will not be reported by studies. Sytmptom onset dates reported in studies may also be biased as studies are likely to focus on hospitalised individuals who will present with more severe symptoms that may preclude accurate recording of symptom onset dates (i.e. patients present with altered mental status). No formal risk of bias will be performed but data will be extracted on the method of selection of patients into the included studies.

## Analysis

Data were summarised the main outcome of time to diagnosis from first symptom onset will be analysed and unadjusted odds ratios will be calculated for disease outcome by number of days after symptom onset confirmation was made.