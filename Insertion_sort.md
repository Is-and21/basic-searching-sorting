Algorithm for insertion sort

Start with the second element as (index 1); index for the iteration purpose
compare current element with the previous
shift all larger elements one position right 
Insert the current element in the position
Repeat the ssame for all elements in the list


# Insertion Sort Pseudocode
START

function insertionSort(list):

  for i = 1 to length(list) - 1:
    key = list[i]
    j = i - 1

  while j >= 0
  AND 
  list[j] > key:
      list[j + 1] = list[j]
      j = j - 1

  list[j + 1] = key

  return list
  
END
