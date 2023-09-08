# Caroli Releases
* [2023 Releases](#2023-releases)

---

## 2023 Releases

### v2.0-2023-08-25

All classes are reviewed to ensure right cross referencings, IRIs, IDs, obo namespaces, labels, definitions, related synonyms, alternative IDs, data base cross references, and definition sources.
Definitions without sources in the previous version were removed.
Some of the symptoms and diseases weren't in their ontologies, so we added them to carolio:
* "variceal bleeding"
* caroli syndrome


For the following classes from other ontologies, i.e. Symptom, or Human Disease ontologies, that did not have an original definition, we added definition and provided scientific references:
* liver disease
* symptom
* abdominal symptom
* altered mental status
* hepatic abscess
* hematochezia
* right upper quadrant abdominal tenderness
* abdominal symptom
* abdominal discomfort
* abdominal tenderness
* digestive system symptom
* feces and droppings symptom


The "symptom status" label was renamed to "symptom recurrence status" and moved under "value partition" class and became an exhustive class.
Proper names were replaced for treatment classes, with their definitions and sources.
Definitions are added to pain scales


|   | OWL | Properties |
| --- | --- | --- |
| Applied | [CaroliO_V.A.2.0.20230825.owl](CaroliO_V.A.2.0.20230825.owl) | [CaroliO_V.A.2.0.20230825.properties](CaroliO_V.A.2.0.20230825.properties) |
| Basic | [CaroliO_V.B.2.0.20230825.owl](CaroliO_V.B.2.0.20230825.owl) | [CaroliO_V.B.2.0.20230825.properties](CaroliO_V.B.2.0.20230825.properties) |




### [v1.5](v1.5)

Colangiocarcinoma route has updated based on DO
"abdomen discomfort" was wrongly located in digestive system symptoms with dyspepsia as name. We consulted with Dr. Steve J. Scaglione and changed the route and name.
Stool symptptom category was replaced with an existing category in symptoms ontology: "feces and droppings symptom"
Altered mental status was wrongly positioned under neurological and physiological symptom. I changed it to be under nurves system symptom, as symptom ontology has it.

#### 2023-08-19

|   | OWL | Properties |
| --- | --- | --- |
| Basic | [CaroliO_VB1.5.20230819.owl](CaroliO_VB1.5.20230819.owl) | [CaroliO_VB1.5.20230819.properties](CaroliO_VB1.5.20230819.properties) |

#### 2023-08-17

|    | OWL |
| --- | --- |
| Basic | [CaroliO_VB1.5.20230817.owl](CaroliO_VB1.5.20230817.owl)


### [v1.4-2023-07-26](v1.4)

* Added http://purl.obolibrary.org/obo/IAO_0000115 (definition) and re-defined classes with it. 
* Added other common annotation properties id, has alternative id, has_related_synonym, has_obo_namespace, database_cross_refernce, 	
* Remove annotation property:rdfs:comment and replace it with the new proper annotation properties.
* Use re;atop
* Fixed other issues with annotations and make all cross references correct.

|    | OWL | Properties |
| --- | --- | --- |
| Basic | [CaroliO_VB1.4.20230726.owl](https://github.com/TootooniLab/CaroliO/blob/0025ca2bb10511fe698d9b518a0d9ae0d697d5e4/src/ontology/releases/v1.4/CaroliO_VB1.4.20230726.owl) | [CaroliO_VB1.4.20230726.properties](https://github.com/TootooniLab/CaroliO/blob/0025ca2bb10511fe698d9b518a0d9ae0d697d5e4/src/ontology/releases/v1.4/CaroliO_VB1.4.20230726.properties) |


### [v1.3-2023-07-25](v1.3)

Changed IRI and added OBO namespace

|   | OWL | Properties | 
| --- | --- | --- |
| Basic | [CaroliO_VB1.3.20230725.owl](https://github.com/TootooniLab/CaroliO/blob/0025ca2bb10511fe698d9b518a0d9ae0d697d5e4/src/ontology/releases/v1.3/CaroliO_VB1.3.20230725.owl) | [CaroliO_VB1.3.20230725.properties](https://github.com/TootooniLab/CaroliO/blob/0025ca2bb10511fe698d9b518a0d9ae0d697d5e4/src/ontology/releases/v1.3/CaroliO_VB1.3.20230725.properties) | 


### [v1.2-2023-07-20](v1.2)

|    | OWL | Properties |
| --- | --- | --- |
| Applied | [CaroliO_VA1.2.20230720.owl](https://github.com/TootooniLab/CaroliO/blob/0025ca2bb10511fe698d9b518a0d9ae0d697d5e4/src/ontology/releases/v1.2/CaroliO_VA1.2.20230720.owl) | [CaroliO_VA1.2.20230720.properties](https://github.com/TootooniLab/CaroliO/blob/0025ca2bb10511fe698d9b518a0d9ae0d697d5e4/src/ontology/releases/v1.2/CaroliO_VA1.2.20230720.properties) |
| Basic | [CaroliO_VB1.2.20230720.owl](https://github.com/TootooniLab/CaroliO/blob/0025ca2bb10511fe698d9b518a0d9ae0d697d5e4/src/ontology/releases/v1.2/CaroliO_VB1.2.20230720.owl) | [CaroliO_VB1.2.20230720.properties](https://github.com/TootooniLab/CaroliO/blob/0025ca2bb10511fe698d9b518a0d9ae0d697d5e4/src/ontology/releases/v1.2/CaroliO_VB1.2.20230720.properties) | 


### [v1.1-2023-02-07/2023-02-08](v1.1)

|    | OWL | Properties |
| --- | --- | --- |
| Applied | [CaroliO_VA1.1.20230207.owl](https://github.com/TootooniLab/CaroliO/blob/0025ca2bb10511fe698d9b518a0d9ae0d697d5e4/src/ontology/releases/v1.1/CaroliO_VA1.1.20230207.owl) | [CaroliO_VA1.1.20230207.properties](https://github.com/TootooniLab/CaroliO/blob/0025ca2bb10511fe698d9b518a0d9ae0d697d5e4/src/ontology/releases/v1.1/CaroliO_VA1.1.20230207.properties) | 
| Basic | [CaroliO_VB1.1.20230208.owl](https://github.com/TootooniLab/CaroliO/blob/0025ca2bb10511fe698d9b518a0d9ae0d697d5e4/src/ontology/releases/v1.1/CaroliO_VB1.1.20230208.owl) | [CaroliO_VB1.1.20230208.properties](https://github.com/TootooniLab/CaroliO/blob/0025ca2bb10511fe698d9b518a0d9ae0d697d5e4/src/ontology/releases/v1.1/CaroliO_VB1.1.20230208.properties) |


### [v1.0-2023-01-31](v1.0)

|    | OWL | Properties |
| --- | --- | --- |
| Applied | [CaroliO_VA1.0.20230131.owl](https://github.com/TootooniLab/CaroliO/blob/0025ca2bb10511fe698d9b518a0d9ae0d697d5e4/src/ontology/releases/v1.0/CaroliO_VA1.0.20230131.owl) | [CaroliO_VA1.0.20230131.properties](https://github.com/TootooniLab/CaroliO/blob/0025ca2bb10511fe698d9b518a0d9ae0d697d5e4/src/ontology/releases/v1.0/CaroliO_VA1.0.20230131.properties) | 
| Basic | [CaroliO_VB1.0.20230131.owl](https://github.com/TootooniLab/CaroliO/blob/0025ca2bb10511fe698d9b518a0d9ae0d697d5e4/src/ontology/releases/v1.0/CaroliO_VB1.0.20230131.owl) | [CaroliO_VB1.0.20230131.properties](https://github.com/TootooniLab/CaroliO/blob/0025ca2bb10511fe698d9b518a0d9ae0d697d5e4/src/ontology/releases/v1.0/CaroliO_VB1.0.20230131.properties) |







