# translate
Translate questionaries

The script has three main sections: (i) loggin in, (ii) extract information from the questionary, and (iii) pass the extracted information into the translate interface in the webside

1. Loggin in:

Use the species to fill the respective species questionary, status if there is more than one version of the questionary like old or new, and use username and password in the first section to use an apitest interface 

 

If a non-test interface is required then fill credentials in username and password and remove the ##:
 

 


2. Extract information from the questionary
-Identify a path where the word questionary is saved and copy it in the path:

 

-Define a redirect pattern by looking the first part of the sentences according to the language (for example for Dutch “als, ga naar”, and define help text  markers 

 

3. Pass the extracted information
The script has three counting parameters, item_index, category_counter and question_counter. The starting point will be 0, meaning that the process will start from the first item (in the interface of the webside), the first category, and the first question in the first category. The item, category and questions, can be stetted to continue if the script doesn’t run from starting to end. 

 
