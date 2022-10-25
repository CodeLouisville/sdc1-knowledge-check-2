# Knowledge Check 2 for Software Course 1


1. Create a new project
2. Create a new object and then create another object that inherits from it.  Each object should have at least 1 property.  Example from the pet store: first class is Animal, second class is Cat and it inherits from Animal.
3. Paste the following template in the Program file:

```
Console.WriteLine("How many records do you want to add? ");
var numberOfRecords = int.Parse(Console.ReadLine());

var recordList = new List<MyClass>();
for (int i = 0; i < numberOfRecords; i++)
{
	// In this loop, populate the object's properties using Console.ReadLine()
	var myClass = new MyClass();

	Console.WriteLine("Enter the value for ");
	myClass. = Console.ReadLine();
    

	recordList.Add(myClass);
}

// Print out the list of records using Console.WriteLine()


```
 
4. Replace “MyClass” with the child class that you made in step 2.  
5. You should allow the user to add data for every property in your class.  So with the cat example, the user should be able to add values for every property of Cat which includes the properties from Animal.
6. Print the objects in recordList to the screen
7. Upload to a new repository on your Github account.
8. Turn in the knowledge check in Google Classroom. Make sure you include the link to your new GitHub repository when you "Turn In" the assignment.
