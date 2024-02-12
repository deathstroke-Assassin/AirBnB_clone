The console
-----------

How to start:
------------

write: ./console.py

------------
how to use:
------------

1. help

	views all commands 
1.2 help (command name)
	
	views info about a certain command

2. all

	Prints all string representation of all instances based or not on the class name

3. show

	Prints the string representation of an instance based on the class name and id

4. create 

	creates a class

5. destroy

	removes a class

6. update

	 Updates an instance based on the class name and id by adding or updating attribute

7. EOF / quit

	exit the console

---------------
Examples
---------------
1.
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  all  count  create  destroy  help  quit  show  update

2.
(hbnb) help all
Prints all string representation of all instances.

3.
root@2ee845ee6c0c:/AirBnB_clone# ./console.py
(hbnb) quit
root@2ee845ee6c0c:/AirBnB_clone#

4.

(hbnb) create BaseModel
e5a9932e-4121-4a4f-8281-c31bacfbe3ec

5.

(hbnb) all BaseModel
["[BaseModel] (e5a9932e-4121-4a4f-8281-c31bacfbe3ec) {'id': 'e5a9932e-4121-4a4f-8281-c31bacfbe3ec', 'created_at': datetime.datetime(2024, 2, 12, 7, 27, 1, 826145), 'updated_at': datetime.datetime(2024, 2, 12, 7, 27, 1, 826160)}"]
(hbnb)


6.

(hbnb) show BaseModel e5a9932e-4121-4a4f-8281-c31bacfbe3ec
[BaseModel] (e5a9932e-4121-4a4f-8281-c31bacfbe3ec) {'id': 'e5a9932e-4121-4a4f-8281-c31bacfbe3ec', 'created_at': datetime.datetime(2024, 2, 12, 7, 27, 1, 826145), 'updated_at': datetime.datetime(2024, 2, 12, 7, 27, 1, 826160)}
(hbnb)
