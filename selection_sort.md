ALgorithm:

Divide the list into parts(sort ,unsort)
Find the minimum
swap the first elemeent with the minimum
Repeat (finding and swaping)
the list will get sorted




selection sort pseudo code:

START
def selection_sort(list):
    n = length of list
    
    for i from 0 to n - 1:
        min_index = i 
        
        for j from i + 1 to n - 1:
            if list[j] < list[min_index]: 
                min_index = j  
        
        if min_index ≠ i:  
            swap list[i] and list[min_index]
    
    return list
END
