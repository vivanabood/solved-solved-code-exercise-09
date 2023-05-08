Download Link: https://assignmentchef.com/product/solved-solved-code-exercise-09
<br>
Setup:You will be working with a premade project provided to you that can be downloaded here.

Grading:Please refer to the CE:09 tab of this rubric to understand the grading procedures for this assignment.

Deliverables:You will compress and upload a file named “FirstnameLastname_CE09.zip” with the following contents with the following names:

● Project – Folder containing your entire project and all files necessary to build the project(csproj, .cs files, App.config, and Properties folder).

Be sure to upload the correct project and all required files the first time as only one submission will be allowed. No extra time or consideration will be given if the wrong files are uploaded.

Instructions:For this assignment you will start with a simple application that loads in an array of Characters from a JSON file. Initially the program lets the user choose whether to display the array of Characters, sort them, or search them. Only the display functionality works as you will be implementing the sort and search capabilities. You will not be modifying the Main method, instead there are two methods that Main calls for sorting and searching called SortCharacters and SearchCharacters and you will start your implementations in these two methods. There are 3 fields that the user needs to be able to sort and search by: Name, equippedWeapon’s Name, and TotalDefense. You can use any sort method or algorithm that you choose to and only ascending order needs to be supported. Search must be done with your own binary search implementation. The search should simply output either the index of the object or the object’s information upon finding a match.

The following guidelines are the grading categories for this assignment:

Binary Search

● The Binary Search algorithm is used to search the Name property.

● The Binary Search algorithm is used to search the Weapon Name property.

● The Binary Search algorithm is used to search the TotalDefense property.

Sorting

● The Character array can be sorted by the Name property.

● The Character array can be sorted by the Weapon Name property.

● The Character array can be sorted by the TotalDefense property.

Extra Information

Tips and hints:

● You don’t need to keep all of your code in the SortCharacters and SearchCharacters methods, you can make additional classes or methods as you see fit.

● You can add methods to the Character and Weapon class if needed.

● Feel free to look through the Utility class and note the Data Member tags in the Character class to see how the JSON object serialization was done.

Go back through your code and check for the following:

● All variables and methods are named appropriately.

● Member variables should have either protected or private access.

● Anytime the user is asked for input the expected input is made clear to the user.

● Any information being output to the user should be clear and concise.

● The user should be clearly informed of what is occurring throughout the application. When values change or objects are instantiated information about this occurrence should be displayed.

● Make sure nothing accesses an object that doesn’t exist.