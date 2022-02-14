# Selection sort and Insertion sort
## Aim:
To write a program to perform selection sort and insertion sort using python programming.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Selection Sort Algorithm:
1.	Set the first unsorted element as the minimum
2.	For each of the unsorted elements, check if the element < current minimum.
3.	If yes, set the element as the new minimum.
4.	Swap minimum with first unsorted position.
5.	Repeat the steps 2 and 3 for all the elements in the array.
## Insertion Sort Algorithm:
1.	Set the first element as sorted element j.
2.	For each unsorted element X, check if current sorted element j >X.
3.	If yes, move sorted element to the right by 1.
4.	Break the loop and insert X.
5.	Repeat the steps 2 to 4 for sorting all the elements in the array.
## Program:
i)	#Selection Sort
```''' 
Program to sort the elements in the list using the Selection Sort algorithm.
Developed by: Mirudhula D
RegisterNumber: 21002651
'''
def selection_sort(nums):
    for i in range(len(nums)):
        lowest_index_value=i
        for j in range(i+1, len(nums)):
            if nums[j]<nums[lowest_index_value]:
                lowest_index_value=j
        nums[i],nums[lowest_index_value]=nums[lowest_index_value],nums[i]
    
    
    
    
    
list_of_nums = eval(input())
selection_sort(list_of_nums) # use the selection sort function
print(list_of_nums) # print the sorted list





```
ii)	#Insertion Sort
```

''' 
Program to sort the elements in the list using the Insertion Sort algorithm.
Developed by: your name
RegisterNumber: 
'''
def insertion_sort(nums):
    for i in range (1, len(nums)):
        value_to_insert=nums[i]
        j=i-1
        while j>=0 and nums[j] > value_to_insert:
            nums[j+1]=nums[j]
            j -= 1
        nums[j+1]=value_to_insert 
            
            
  
    
    
    
list_of_nums = eval(input())
insertion_sort(list_of_nums) # use the insertion sort function to get the sorted list
print(list_of_nums) # print the sorted list




```

## Output:
![image](https://user-images.githubusercontent.com/94828147/153798574-641c3f89-10bd-4ba7-9b9d-13f476879af0.png)
![image](https://user-images.githubusercontent.com/94828147/153798647-b781ca54-d8e3-4910-a8dc-52acb5ca1073.png)
![image](https://user-images.githubusercontent.com/94828147/153798696-5d054888-2a90-41e5-8f07-719064512bb7.png)
![image](https://user-images.githubusercontent.com/94828147/153798746-c9b7fdaa-b948-406d-8ff9-a39732a29305.png)



## Result:
Thus the program is written to perform selection sort and insertion sort using python programming.
