# TagFinder
 -----------
 DESCRIPTION
 ***********
 
 Due the difficulty to find especific equipments and instruments all over a oil & gas production platform
 I built this app.
 Since all equipments and instruments on a industry field are registred with a diferent tag number a built this app
 where we are able to create, edit and remove equipments by saving a tag and a local description of a especific
 equipment in a list.
 Also you can backup and recovery created lists.
 
------
STACKS
******
It was used: HTML + CSS + JAVASCRIPT + LOCALSTORAGE + PYTHON


*localstorage: used as database

*Python: used to create a logic to save the list in the localstorage 
 
 
 ------------
 INSTRUCTIONS
 ************
 
 *Buttons
 	*Show table: opens and closes the current list.
 	*Add: add the tag and description of a certain equipment to the current list.
 	*Search: searches for a certain equipment based on the tag filled in the tag inputs.
 	*Remove: removes a equipment from the current list based on the tag filled in the tag inputs.
 	*Backup: Saves the current list in a .json file.
 	*Restore: loads a .json list file.
 	*Clear: clears the current list.
 	
 *Inputs
 	*TAG inputs: To create, remove or edit a equipment you have to fill the tag inputs. The format of the tag code
 	in my company is "nn-ll-nnnn"(n:number;l:leter). But fell free to save in the format you want or fell
 	free to change the code to change the inputs.
 	*Description inputs: Don't forget to fill this input before "add". Fill with the place where this equipment is located. 
 	Otherwise the whole app idea will not make any senese. :)
 	 
----------
Developers
**********
Just me Gustavo Arndt.

-----
STYLE
*****
This app was made focused in efficiency so I didn't pay much attention to styling. :)


-----
NOTES
*****

Feel free to clone the repository: https://github.com/GustavArndt/TagFinder.git
Feel free to change the code.

Feel free to adapt to your own professional area. 
