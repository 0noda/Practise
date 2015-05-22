# Practise
<strong>Todo: </strong></br>
For [R] </br>
1. Create database by MySQL contains tables such as "patient", "diagnoses", "list_d", pictures", "evidences", "objects"  </br>
1a. diagnoses has id, name, death_rate </br>
1b. dist_d (means list of diagnoses) has id, diagnosis_id(FOREIGN_KEY to id of diagnosis), patient_uniq_val(FOREIGN_KEY to unique_val of patient) </br>
<i>Lis_d needs for some anonymization.</i></br>
1c. patient has id, fullname, birth_date, sex, health_insurance_id, unique_val </br>
1d. pictures has id, picture, description, list_d_id(FOREIGN_KEY to id of list_d)  </br>
1e. evidences has id, name, picture_id(FOREIGN_KEY to id of pictures) </br>
1f  objects has id, string_data, evidence_id(FOREIGN_KEY to id of evidences)
</br>
For [S] </br>
Create program that afford:</br>
1. selected image areas </br>
2. save their type and coordinates as string_data </br>
3. save evidences list of selected areas</br>
For [K] </br>
1. Make report about work was done </br>
