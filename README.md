Write a Python program to simulate the functionality of a Smart Bin. The smart bin should collect data about the trash level, categorize waste into different bins (organic, recyclable, hazardous), and display a notification when the bin is full.

  
**Instructions:**

  
 1\. **Part 1: Trash Level Detection**

 • Create a function check\_trash\_level() that simulates a sensor detecting the fill level of the bin. The bin has a capacity of 100 units. The function should generate random trash levels between 0 and 100.

 • Display a message if the bin is over 75% full.

 2\. **Part 2: Waste Categorization**

 • Create a class SmartBin that categorizes trash into three types:

 • **Organic**

 • **Recyclable**

 • **Hazardous**

 • Define methods to add trash to each category. Each method should increase the respective bin’s fill level.

 • If any category is full (over 75 units), notify the user that the bin is almost full.

 3\. **Part 3: Bin Status Display**

 • Write a function display\_bin\_status() that shows how full each trash category bin is as a percentage.

 • If the total waste exceeds 90%, the system should trigger a notification to empty the bins.

 4\. **Part 4: User Interaction**

 • Allow the user to input the type of trash they want to add (organic, recyclable, hazardous) and the amount.

 • The program should add the trash to the corresponding bin and check if the bin is full after each addition.