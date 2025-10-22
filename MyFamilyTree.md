
**Family Tree Application running on Apple iOS. **
  
**Introduction**
This is a basic , free and simple family tree application running on the Apple platform . It allows adding , storing and creating multiple family trees. As an added option you can add photos
It uses the Apple File system . No data will be shared by the application. Your data will be totally under your control
I am writing here a simple user manual
  
I will hence forward call the application : FTA
  
There are four main menu entries . I will explain them through the normal process of creating a family tree . Not the way the menus might appear
  
1- **Data input menu :**
You can add data to the FTA in two ways
The first is in bulk form . This is the easier way to create a tree. You create a text file , copy it to the clipboard (pasteboard) and paste it in the text editor that will be shown . When selecting  Parse , the FTA will check the data and parse it in a family tree. This will be explained later in more details
The second is by keying in individual family members . This is much slower. This feature can also be used to edit the family tree you presently have in the FTA. Whether this was fed to the FTA through bulk input or by loading a tree file
*++Bulk file description:++*
The bulk file should be created by a text editor . It should be a text file , hence no formatting
I will call it the dictionary file
Each member to be displayed will have a line
Example file :  NAME:Grandma; PARENTS:; SPOUSES:Grandpa; SIBLINGS:Aunt1, Aunt2;CHILDREN:Child1,Child2
NAME:Grandpa; PARENTS:; SPOUSES:Grandma; SIBLINGS:; CHILDREN: Son1, Son2
NAME:Son1; PARENTS: Grandma, Grandpa;SPOUSES: Spouse1; SIBLINGS: Son2; CHILDREN:Grandchild
NAME:Spouse1; PARENTS: MrA , MrsA;SPOUSES:Son1; SIBLINGS:; CHILDREN: Grandchild
NAME:Grandchild; PARENTS: Son1,Spouse1; SPOUSES:; SIBLINGS:;CHILDREN
  
    - [ ] As shown names within the fields are separated by commas, the fields are separated by a semicolon
    - [ ] Upper case and lower case do not make a difference
    - [ ] The order in which you add the lines makes no difference. The FTA will adjust
    - [ ] The most senior family member , to be shown on the top line of the tree, should have no Parents
    - [ ] You can use placeholders  instead of names , eg MrA and MrsA
    - [ ] Any member with no entry line  in the dictionary will not be displayed
    - [ ] Once you create the file , copy it to the clipboard and parse it in the Text Input field. Press Parse. You will get a confirmation if the FTA accepted your data
    - [ ] Now you can display the family and store it
  
2- **Display the family tree **
This is where you can display the tree and scroll through it
The family dictionary can be added to the FTA from two sources . The first is though the Data input menu as previously explained. The second is from the file handling menu where you can load and append previously entered data . This will be explained later
    - [ ] The tree will be displayed in colored levels
    - [ ] Married couples will be linked together
    - [ ] You can scroll in any direction
    - [ ] You can focus on a family member by clicking on his/her name. The tree will then show the directly related members
    - [ ] A key will take you back to the full tree display
  
**3- File Handling Menu **
File access is totally based on the Apple filing system and protection
You can select the file names and location but please let the  FTA select the file extensions
A technical note : the tree file uses the JSON format . It allows faster and better access. This is completely transparent to the user
You can save the existing family tree in two formats . A text format similar to the dictionary initially used to key in and parse the data . The second , better , faster format is called a tree file
To load a text file you have to go through the data entry menu and parse the data, then you can display it . A much better way is just to load the tree file . You can then immediately display the tree data it contains
  
The tree file allows you to merge family trees together to create a bigger on . Through the Append option . Let me explain
*++To merge family trees :++*
    - [ ] First add family tree 1 (FT1) and family tree 2 ( FT2) through the normal date entry process explained previously
    - [ ] Create and store tree files for FT1 and FT2
    - [ ] Load one of them , say FT1 . Display the tree if you want
    - [ ] From the File Handling Menu , select Append FT2
    - [ ] Display the family tree . It should show you the merged data from FT1 and FT2 . You can then save it as a tree file calling it FT3 , or whatever name you prefer
This is the way to merge and build larger family trees
  
**4- Image handling :**
This is an added option that just allows the display of family members photos
It has no effect whatsoever on the structure and display of the family trees
*++How to use it :++*
    - [ ] Create a folder where the photos will be stored and retrieved from
    - [ ] App a photo . This will trigger a standard Apple photo picker and you will be asked to enter a name for the photo
    - [ ] Please use the EXACT name of the family member
    - [ ] You can then browse all the photos by name
    - [ ] Once you have a family tree loaded in the FTA app , you can select the Browse Family Photos . You will be shown the existing photos of the loaded family members
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
**Family Tree Application running on Apple iOS. **
  
**Introduction**
This is a basic , free and simple family tree application running on the Apple platform . It allows adding , storing and creating multiple family trees. As an added option you can add photos
It uses the Apple File system . No data will be shared by the application. Your data will be totally under your control
I am writing here a simple user manual
  
I will hence forward call the application : FTA
  
There are four main menu entries . I will explain them through the normal process of creating a family tree . Not the way the menus might appear
  
1- **Data input menu :**
You can add data to the FTA in two ways
The first is in bulk form . This is the easier way to create a tree. You create a text file , copy it to the clipboard (pasteboard) and paste it in the text editor that will be shown . When selecting  Parse , FTA will check the data and parse it in a family tree. This will be explained in more details
The second is by keying in individual family members . This is much slower. But this feature will allow you to edit the data you presently have in the FTA. Whether this was fed to the FTA through bulk input or by loading a tree file
*++Bulk file description:++*
The bulk file should be created by a text editor . It should be a text file , hence no formatting.
I will call it the dictionary file
Each member to be displayed will have a line
Example file :  NAME:Grandma; PARENTS:; SPOUSES:Grandpa; SIBLINGS:Aunt1, Aunt2;CHILDREN:Child1,Child2
NAME:Grandpa; PARENTS:; SPOUSES:Grandma; SIBLINGS:;CHILDREN:Child1,Child2
NAME:Child1; PARENTS: Grandma, Grandpa;SPOUSES: Spouse1; SIBLINGS:Child2; CHILDREN:Grandchild
NAME:Spouse1; PARENTS: MrA , MrsA;SPOUSES:Child1; SIBLINGS:;CHILDREN:Grandchild
  
  
  
NAME:Grandchild; PARENTS: Child1,Spouse1; SPOUSES:; SIBLINGS:;CHILDREN
As shown names within the fields are separated by commas, the fields are separated by a semicolon
Upper case and lower case do not make a difference
The order in which you add the lines makes no difference. The FTA will adjust
The most senior family member , to be shown on the top line of the tree, should have no Parents
You can use placeholders  instead of names , eg MrA and MrsA
Any member with no entry line  in the dictionary will not be displayed
Once you create the file , copy it to the clipboard and parse it in the Text Input field. Press Parse. You will get a confirmation if the FTA accepted your data
Now you can display the family and store it
  
2- **Display the family tree **
This is where you can display the tree and scroll through it
The family dictionary can be added to the FTA from two sources . The first is though the Data input menu as previously explained. The second is from the file handling menu where you can load and append previously entered data . This will be explained later
The tree will be displayed in colored levels
Married couples will be linked together
You can scroll in any direction
You can focus on a family member by clicking on his/her name. The tree will then show the directly related members
A key will take you back to the full tree display
  
**3- File Handling Menu **
File access is totally based on the Apple filing system and protection
You can select the file names and location but please let the  FTA select the file extensions
A technical note : the tree file uses the JSON format . It allows faster and better access. This is completely transparent to the user
You can save the existing family tree in two formats . A text format similar to the dictionary initially used to key in and parse the data . The second , better , faster format is called a tree file
To load a text file you have to go through the data entry menu and parse the data, then you can display it . A much better way is just to load the tree file . You can then immediately display the tree data it contains
  
The tree file allows you to merge family trees together to create a bigger on . Through the Append option . Let me explain
*++To merge family trees :++*
First add family tree 1 (FT1) and family tree 2 ( FT2) through the normal date entry process explained previously
Create and store tree files for FT1 and FT2
Load one of them , say FT1 . Display the tree if you want
From the File Handling Menu , select Append FT2
Display the family tree . It should show you the merged data from FT1 and FT2 . You can then save it as a tree file calling it FT3 , or whatever name you prefer
This is the way to merge and build larger family trees
  
**4- Image handling :**
This is an added option that just allows the display of family members photos
It has no effect whatsoever on the structure and display of the family trees
*++How to use it :++*
Create a folder where the photos will be stored and retrieved from
App a photo . This will trigger a standard Apple photo picker and you will be asked to enter a name for the photo
Please use the EXACT name of the family member
You can then browse all the photos by name
Once you have a family tree loaded in the FTA app , you can select the Browse Family Photos . You will be shown the existing photos of the loaded members
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
