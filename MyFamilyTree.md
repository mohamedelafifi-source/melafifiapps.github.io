Family Tree Application running on Apple iOS. 

Introduction
This is a basic , free and simple family tree application running on the Apple platform . It allows adding , storing and creating multiple family trees. As an added option you can add photos 
It uses the Apple File system . No data will be shared by the application. Your data will be totally under your control  

I will hence forward call the application : FTA

There are five  main menu entries . I will explain them through the normal process of creating a family tree 
1- Location :
- [ ] Here you will select the Storage Folder , where your family files photos etc will be stores. You can have as many as you need
- [ ] The name and path of the folder will be shown
- [ ] You can copy the path for your own use. But please be cautious about changing the file extensions
- [ ] Preferably the folder should be on iCloud or any cloud service
- [ ] Please note that most menus will be disabled  till you select the folder

2- File Handling Menu 
File access is totally based on the Apple filing system and protection 
You should have selected the folder you want to use from the Location menu
You can select the file names but please let the  FTA select the file extensions
A technical note : the tree file uses the JSON format . It allows faster and better access. This is completely transparent to the user
You can save the existing family tree in two formats . A text format similar to the dictionary initially used to key in and parse the data . The second , better , faster , format is called a tree file
The FTA will show you the list of tree files in the folder. Select the one you want to use. This is the faster and easier way
To load a previously saved text file you have to go through the data entry menu and parse the data, then you can display it 


The tree file allows you to merge family trees together to create a bigger one . Through the Append option . Let me explain 
To merge family trees :

    - [ ] First add family tree 1 (FT1) and family tree 2 ( FT2) through the normal date entry process explained previously 
    - [ ] Create and store tree files for FT1 and FT2
    - [ ] Load one of them , say FT1 . Display the tree if you want 
    - [ ] From the File Handling Menu , select Append FT2
    - [ ] Display the family tree . It should show you the merged data from FT1 and FT2 . You can then save it as a tree file calling it FT3 , or whatever name you prefer 
This is the way to merge and build larger family trees

3- Data Entry menu :

    - [ ] You can add data to the FTA in two ways 
    - [ ] The first is in bulk form . This is the easier way to create a tree. You create a text file , copy it to the clipboard (pasteboard) and paste it in the displayed text editor  . When selecting  Parse , the FTA will check the data and parse it in a family tree. This will be explained later in more details 
    - [ ] The second is by keying in individual family members . This is much slower. This feature can also be used to edit the family tree you presently have in the FTA. Whether this was fed to the FTA through bulk input or by loading a tree file 
    - [ ] Please note that the display of individual family members will be in alphabetical order
    - [ ] When editing ,  the original family dictionary will be used .  This is similar to the data you entered initially. Not the relationships that the FTA created in the tree view.
    - [ ] If you want to permanently save the changes you made , you need to go to File Handling and save to a Tree file or Text file. You can also replace the old Tree file you started with
    - [ ] Pressing Refresh will display the modifications 
    - [ ] Please note that a warning will be issued when changes are made
    - [ ] Please note that if you have a previously loaded tree file and you parse a new text file , the data of both trees will be merged 

Bulk file description:
The bulk file should be created by a text editor . It should be a text file , hence no formatting
I will call it the dictionary file 
Each member to be displayed will have a line  
Example file :  NAME:Grandma; PARENTS:; SPOUSES:Grandpa; SIBLINGS:Aunt1, Aunt2;CHILDREN:Child1,Child2
NAME:Grandpa; PARENTS:; SPOUSES:Grandma; SIBLINGS:; CHILDREN: Son1, Son2
NAME:Son1; PARENTS: Grandma, Grandpa;SPOUSES: Spouse1; SIBLINGS: Son2; CHILDREN:Grandchild
NAME:Spouse1; PARENTS: MrA , MrsA;SPOUSES:Son1; SIBLINGS:; CHILDREN: Grandchild
NAME:Grandchild; PARENTS: Son1,Spouse1; SPOUSES:; SIBLINGS:;CHILDREN 

    - [ ] The main fields are : NAME , PARENTS , SPOUSES ,  SIBLINGS and CHILDREN
    - [ ] Please use short names as much as possible , preferably without spaces as the names can be used as file names as will be shown later in the photos menu 
    - [ ] As shown names within the fields are separated by commas, the fields are separated by a semicolon 
    - [ ] Upper case and lower case do not make a difference
    - [ ] The order in which you add the lines makes no difference. The FTA will adjust the relationships 
    - [ ] The most senior family member , to be shown on the top line of the tree, should have no Parents. Just use a space character. This is very important
    - [ ] You can use placeholders  instead of names , eg MrA and MrsA
    - [ ] Better not to use the same name in the placeholder . So use MrAA,MrsAA, Then MrAB, MrsAB etc
    - [ ] Any member with no entry line  in the dictionary will not be displayed
    - [ ] Once you create the file , copy it to the clipboard and parse it in the Text Input field. Press Parse. You will get a confirmation if the FTA accepted your data 
    - [ ] Now you can display the family and store it 
    - [ ] Important Note : You can use the option of Clear All data to clear the existing family tree data from the app. It will NOT delete any file only the data in the FTA
    - [ ] As mentioned earlier if you do not Clear All Data, the newly parsed bulk data will be merged with the existing tree data

4- Display the family tree : The View menu
This is where you can display the tree and scroll through it . Line by line I.e. by family level 
The family dictionary can be added to the FTA from two sources . The first is through the Data Entry menu as previously explained. The second is from the file handling menu where you can load and append previously entered data . This will be explained later

    - [ ] The tree will be displayed in colored levels
    - [ ] Married couples will be linked together
    - [ ] You can scroll per level  in any direction
    - [ ] You can focus on a family member by clicking on his/her name. The tree will then show the directly related members
    - [ ] A key will take you back to the full tree display 


5- Image handling : The Photo menu
This is an added option that just allows the display of family members’  photos 
It has no effect whatsoever on the structure and display of the family trees
How to use it :

    - [ ] You can Reset the photo index file. The will create a new , empty photo index file. Please be warned that it will erase the exiting one
    - [ ] You should have selected the folder you want to use from the Location menu
    - [ ] App a photo . This will trigger a standard Apple photo picker and you will be asked to enter a name for the photo
    - [ ] Please use the EXACT name of the family member 
    - [ ] You can then browse all the photos by name 
    - [ ] Once you have a family tree loaded in the FTA app , you can select the Browse Family Photos . You will be shown the existing photos of the loaded family members 

