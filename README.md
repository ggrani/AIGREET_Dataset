# AIGREET_Dataset

Dataset of the AIGREET project on Green Investment Opportunities procurement files.

---
The files training_dataset.json, training_augmented_dataset.json,  and test_dataset.json contain a list of json objects with the following fields:
- **text_id** : the id of the instance
- **text** : the text extracted for a Green Investment Opportunity procurement file
- **green_label** : the target value, being 1 if the text refers to a Green Investment Opportunity, and 0 otherwise.

---




To extract them using python run the following commands:


> `import json`

> `file_path='dataset.json'  #the path to the file`

> `f = open(file_path)`

>`dict_files = json.load(f)`

**`dict_files`** is a list of dictionaries.
   
