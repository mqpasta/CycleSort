# CycleSort
GROUP MEMBERS:MUHAMMAD HARIS MALIK|17B-003-cs| FAIZA SHAHAB|17B-046-cs| HIRA BHATTI|17-059-cs
DEFINITION: Cycle sort is a comparison algorithm which forces array to be factored into number of cycles where each of them rotated to produced sorted array.
TIME COMPLEXITY: In cycle sort time complexity is same in all cases which is "O(n^2)".
WORKING: Cycle sort works in a cyclic way like first we will iterate the loop and the 1st element and the 0th index of the array will be set as a new variable e.g'item' and the position,i. Then there will be a second loop which will run i+1 to array.lenght and it will check if the current element is less than item it will increase the position i. After this there will be a condition if the i will be equal to the position it will countinue. and if item is equal to array[position] it will increase the pos by 1 and then it will swap item,array[position].But if position is not equal to i then the same condition will work that a second loop which will run i+1 to array.lenght and it will check if the current element is less than item it will increase the position i and if item is equal to array[position] it will increase the pos by 1 and then it will swap item,array[position].
